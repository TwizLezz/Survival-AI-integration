# Survival-AI-integration
🏰 Palace — AI Survival Game
A pixel-art survival game powered by Unity ML-Agents, where an AI agent learns through reinforcement learning to gather resources, fight enemies, and build structures — all on its own.

🤖 Concept
Palace is an experiment in emergent AI behaviour. Rather than scripting NPC logic manually, the agent is trained using reinforcement learning to figure out survival on its own. Over time it learns to:

🪓 Gather resources from the environment (wood, materials)
⚔️ Fight enemies and threats
🏗️ Build structures to progress and survive

The goal is to see how complex and intelligent the behaviour becomes purely through training.

🧠 Tech — ML-Agents
Built with Unity ML-Agents Toolkit, using:

Reinforcement Learning — the agent learns by trial and error, receiving rewards for good actions and penalties for bad ones
Observations — agent perceives its position, velocity, nearby resources, and distance to targets
Continuous actions — smooth movement in any direction
Automatic chopping — resources are collected on contact, triggering reward signals


🚧 Current Status
Early Experiment / In Development

 Agent movement and navigation
 Tree detection and chopping
 Reward system for resource gathering
 Episode reset and training loop
 Enemy AI and combat
 Building system
 Multiple resource types
 Full training curriculum
 UI and game loop


🛠️ Built With

Engine: Unity
Language: C#
AI: Unity ML-Agents (Reinforcement Learning)
Art Style: Pixel art

📌 Notes
This project started as an experiment with ML-Agents and reinforcement learning. The vision is a full survival game where the AI genuinely learns to play rather than following hard-coded rules. More systems coming soon.
