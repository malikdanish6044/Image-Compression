# Image-Compression
the Quadtree algorithm identifies regions of uniform color and merges them into single nodes. This results in significant compression, especially in images with large areas of low variance (e.g., skies, flat backgrounds).
the Quadtree algorithm identifies regions of uniform color and merges them into single nodes. This results in significant compression, especially in images with large areas of low variance (e.g., skies, flat backgrounds).
Key Features:
Recursive Compression: Implementation of a 4-way recursive split based on color variance.

Live Preview: Real-time feedback as you adjust Threshold and Max Depth sliders.

Visual Grid Mode: Overlay that shows exactly how the image was partitioned.

Multiple Formats: Support for PNG, JPG, and WebP exports.

Client-Side Processing: All computations happen in your browser—no data is sent to a server.
The algorithm follows a Divide & Conquer approach, represented by the recurrence:$$T(n) = 4T(n/4) + O(n)$$Best Case Time Complexity: $\Omega(n)$ (Uniform Image)Worst Case Time Complexity: $O(n \log n)$ (High Detail Image)Space Complexity: $O(n)$ (Total pixel data)
