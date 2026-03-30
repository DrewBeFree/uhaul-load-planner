# U-Haul Load Planner

Interactive overhead floor plan for planning a 26' U-Haul move.

## Features
- Drag-and-drop items on a to-scale floor plan (1 ft = 34 px)
- Add, edit, and delete items with custom dimensions and colors
- Snap-to-grid toggle for precise placement
- Real-time floor usage stats
- Auto-saves layout to Claude.ai storage — persists across visits

## Truck specs
- Main floor: 23'6" × 8'1" (~190 sq ft)
- Mom's Attic: 2'7" × 8'1" (over cab)
- Door opening: 7'9" W × 6'10" H
- Max load: 9,010 lbs
- Deck height: 2'11"

## Usage
Open `uhaul_interactive.html` in any browser, or host it as a static file.
Storage persistence requires the Claude.ai environment (uses `window.storage` API).

## Current inventory
Pre-loaded with confirmed items:
- Leslie speaker (1.8'×2.4')
- Highboy dresser (36"×22")
- Dresser (39.5"×18")
- Husky cabinet (36"×18")
- Bookshelf (48"×12")
- Workbench (20"×68")
- Stereo cabinet (55"×18")
- Blanket chest (24"×48")
- BR table + coffee table (24"×42" each)
- TV table (18"×30")
- Tool bench (18"×48")
- Bins × 3 (20"×30" each)
- Kitchen boxes
- Futon (lean against wall)
