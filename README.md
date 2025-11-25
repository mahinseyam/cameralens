📸 Camera Lens
A 2D Social Media Influence Simulation Game (OCR A-Level Computer Science NEA)

Camera Lens is a 2D sketch-style narrative game where the player uses an in-game phone camera to capture moments around a college environment.
Every photo you take influences NPC behaviour, triggers events, and branches the story toward different endings — showing how selective media can shape perception, trends, and “clout culture.”

Inspired by We Become What We Behold, this project expands the idea into a realistic school setting with dynamic NPCs, event-driven storytelling, and social-media-themed mechanics.

🎯 Features
📷 Interactive Camera System

Zoom, pan, and capture gameplay events

Flash animation + colour feedback (green = success, red = error)

Each capture broadcasts an event into the game world

🧍 Dynamic NPC Behaviour (FSM)

NPCs follow finite state patterns (Idle → Patrol → React)

Behaviour changes based on what the player photographs

Designed using Finite State Machines for clarity and modularity

🔀 Branching Narrative

Multiple storyline outcomes (e.g., Detention, School Fight, Safe Path)

JSON-based narrative graph

Replayable — different photos lead to different consequences

🎨 Minimal Sketch Aesthetic

Lightweight 2D hand-drawn style

Clean interface to focus on choices & consequences

Fast browser performance

🔊 Audio & Accessibility

Volume sliders (Master / Music / SFX)

Sound reacts to events

Accessible UI feedback and clear structure

📱 In-Game Photo Gallery

Stores all captured photos

Lets players reflect on what they chose to highlight

Core to the game’s message about selective media

🧩 Technical Architecture

Camera Lens uses a modular, event-driven architecture:

Main Game UI – Game loop & initialization

Camera Module – Capture mechanics, zoom, UI states

NPC Module – FSM-based NPC behaviour

Game State Manager – Event triggers & narrative branching

UI Module – Menus, gallery, buttons, on-screen feedback

Sound Module – Music, SFX, volume sliders

🧠 Key Computational Techniques

Abstraction & decomposition

Event-driven programming

Observer pattern

Finite State Machines (FSMs) for NPCs

JSON-driven narrative graph

Modular system design for maintainability

🛠️ Tech Stack

JavaScript

PixiJS (2D rendering)

HTML5 + CSS3

JSON for events, config, and narrative

VS Code

Git for version control

🧪 Testing Strategy
✔️ Iterative Development Testing

Zoom boundaries

Rapid photo captures

NPC state transitions

UI component consistency

Triggering and handling invalid / missing events

✔️ Post-Development Testing

Stress testing

Save data integrity

Usability testing with external users

Full evaluation against SMART criteria

🎓 Educational Purpose

Camera Lens is designed not just as a game, but as a lesson in media literacy.
It helps players understand how:

selective photography

trending behaviour

and digital influence

shape real-world narratives.

Ideal for students, educators, and discussions around social media psychology.

🚀 Status

This project is part of my OCR A-Level Computer Science NEA.
Improvements, extra endings, and more features may be added in future iterations.

📬 Contact

For feedback, suggestions, or collaboration, feel free to reach out.
