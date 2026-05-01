BEERUS AI — Knowledge-Based Pathfinding Agent

"I am the God of Destruction. And I will find the path."

A visually styled, browser-based AI agent that navigates a 4×4 grid environment using knowledge-based inference. Built with pure HTML, CSS, and vanilla JavaScript — no frameworks, no dependencies.

Preview
A dark cyberpunk interface with purple accents, animated spinning rings, a Beerus-inspired orb avatar, and a live system log — all running entirely in your browser.

Features

4×4 environment grid with randomly placed hazards
Knowledge-based safe cell inference from visited positions
Stench percept detection near hazard cells
Auto-run mode that navigates the safe frontier automatically
Live system log with timestamped entries
Animated UI — spinning rings, pulsing badge, flickering title
Fully self-contained — single HTML file, no build step needed


How It Works
The agent starts at cell (0,0) and explores the grid. At each position it:

Checks neighboring cells for hazards (detects a STENCH percept if any neighbor is dangerous)
Marks all safe neighboring cells as part of the known safe frontier
In auto-run mode, randomly picks a safe unvisited cell to move to next
Reaches GOAL at cell (3,3) or terminates if it steps into a hazard

This is a simplified implementation of a Wumpus World-style knowledge-based agent from classical AI.
