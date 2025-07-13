# Malawi District Graph Visualization

This is a simple project to visualize how Malawi’s 28 districts are connected using a graph layout. The goal was to organize the nodes clearly and make the connections easy to follow.

## Purpose

- Make sure district names (nodes) don’t overlap.
- Reduce the number of edge crossings.
- Place connected districts closer together.
- Keep everything inside a 1x1 coordinate space.

## What’s Included

- `index.html` — The main visualization page using D3.js. All node positions are already built in.
- `analysis.pdf` — A brief write-up explaining the problem, the method used, and why it was chosen.
- `screenshots/layout.png` — A screenshot of the final output.
- `optimized_positions.json` — Node coordinates if you want to use them separately.

## How to View the Graph

Just open the `index.html` file in any browser (Chrome, Firefox, Edge, etc.).  
You’ll see the Malawi districts, with green dots for nodes and lines showing their connections.

No extra setup needed.

## Tools Used

- D3.js (loaded via CDN)
- Python (used during layout optimization — not required to run)

## Maintainer

Martin Chirwa  
📧 martinchirwa92@gmail.com
