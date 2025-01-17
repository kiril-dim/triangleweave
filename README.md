# TriangleWeave

TriangleWeave is a standalone HTML/JavaScript visualization that creates an animated triangulation effect. The entire implementation was generated through AI prompting, resulting in a self-contained static webpage with no external dependencies.

## Features

- Animated point placement
- Dynamic line drawing with triangulation
- Smooth color filling animation
- Interactive controls:
  - Number of points (50-500)
  - Animation speed multiplier (0.5x-5x)
  - Point size (2-10)
  - Line thickness (1-5)
  - Restart animation button

## Technical Details

The visualization uses several optimized data structures and algorithms:
- Object pooling for efficient point management
- Priority Queue using binary heap for edge sorting
- QuadTree spatial index for fast intersection testing
- Optimized triangle finding algorithm
- Smart color selection for adjacent triangles

## Usage

Simply open the `triangleweave.html` file in any modern web browser. No server or installation required.

The animation will:
1. Place random points
2. Draw connecting lines to create triangles
3. Fill triangles with harmonious pastel colors
4. Allow real-time adjustment of visualization parameters

## Implementation

The entire implementation is contained in a single HTML file with embedded JavaScript and CSS. This makes it extremely portable and easy to use - just download and open in a browser.

All code was generated through AI prompting, demonstrating the capability of AI to create complex, interactive visualizations with optimized algorithms and smooth animations.
