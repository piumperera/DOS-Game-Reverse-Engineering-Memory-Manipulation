# DOS-Game-Reverse-Engineering-Memory-Manipulation
Reverse engineering a legacy DOS game (DOOM) to analyze and manipulate runtime memory, including identifying and modifying player health using Cheat Engine and a debugger.

📌 DOS Game Reverse Engineering & Memory Manipulation
This project demonstrates practical reverse engineering techniques by analyzing a legacy DOS game (DOOM) to understand its internal behavior without source code access. The focus is on identifying, analyzing, and manipulating the player’s health value in memory during runtime.

Using tools like Cheat Engine and DOSBox-X Debugger, the project explores how game data is stored and updated, differentiates between front-end (display) and back-end (actual logic) values, and locates the core assembly instruction responsible for health reduction. By modifying this instruction, the game behavior is altered to prevent health decrease.

🔍 Key Highlights
Memory scanning and filtering to locate health values
Identification of multiple synchronized memory addresses
Differentiation between display values and actual game logic
Debugging and tracing memory write instructions
Assembly-level modification (NOP) to disable damage logic
🛠️ Tools Used
Cheat Engine
DOSBox-X Debugger

🎯 Objective
To demonstrate how insecure memory handling in legacy applications can be exploited, emphasizing the importance of secure coding practices in modern software development.
