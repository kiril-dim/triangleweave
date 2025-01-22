# Weave Visualizations

A collection of interactive algorithmic art visualizations created through AI prompting. Each visualization is a standalone HTML/JavaScript implementation with no external dependencies.

## Live Demo
Visit https://kiril-dim.github.io/triangleweave/ to try the visualizations online!

## TriangleWeave

An animated triangulation effect that creates beautiful patterns through:
- Animated point placement
- Dynamic line drawing with triangulation
- Smooth color filling animation
- Interactive controls:
  - Number of points (50-500)
  - Animation speed multiplier (0.5x-5x)
  - Point size (2-10)
  - Line thickness (1-5)
  - Color themes
  - Restart animation button

## CircleWeave

A mesmerizing circle-packing animation that generates organic patterns through:
- Dynamic circle growth and packing
- Collision detection and resolution
- Smooth color transitions
- Interactive controls:
  - Maximum circle size
  - Growth speed
  - Color palettes (Pastel, Earth, Vibrant, Cool, Warm, Monochrome)
  - Start/Stop animation
  - Download image feature

## Technical Details

The visualizations use several optimized data structures and algorithms:
- Object pooling for efficient shape management
- Priority Queue using binary heap for edge sorting
- QuadTree spatial index for fast intersection testing
- Smart color selection for adjacent shapes
- Efficient collision detection systems

## Usage

Simply open any of the HTML files in a modern web browser. No server or installation required.

## Implementation

Each visualization is contained in a single HTML file with embedded JavaScript and CSS, making them extremely portable and easy to use - just download and open in a browser.

All code was generated through AI prompting, demonstrating the capability of AI to create complex, interactive visualizations with optimized algorithms and smooth animations.
