# Camo Generator

A fully browser-based digital camouflage generator.
Users can create unlimited custom color palettes, adjust pattern rules, preview the camo live, and export a PNG at any resolutions.

## Features
- **Unlimited hex color pickers**
- **Rule-based pattern generation**
- **Live Background Preview**
- **Seperate Preview And Export Sizes**
- **PNG export button**
-**Runs in browser**

## How It Works

The generator creates a grid of blocks.  
For each block:

1. It shuffles the list of color IDs.  
2. It checks if placing that color would exceed the maximum allowed run length horizontally or vertically.  
3. If allowed, it places the color.  
4. If no color fits the rule, it falls back to a random color.  

This produces natural‑looking digital camo patterns without long streaks.