Sprite Wrangler
A lightweight, standalone web utility that combines nearest-neighbor upscaling with smart, content-based connected-component sprite detection to slice irregular sprite sheets into individual numbered frames directly in the browser.
Core Features
 Integer Upscaling: Multiplies sprite sheet resolutions cleanly (2x to 5x) using nearest-neighbor interpolation to preserve sharp pixel edges before slicing.
 Smart Auto-Detection: Scans the upscaled alpha channels using connected-component analysis to identify irregular sprite boundaries without requiring strict grid dimensions.
 Live Visual Verification: Renders color-coded bounding boxes directly over a responsive preview canvas so you can adjust detection thresholds and gap tolerances in real time.
 Sequential Numbering: Automatically exports sliced, upscaled frames in sorted reading order with clean sequential naming structures.
How to Use
1. Drop your source sprite sheet into the upload zone or click to browse files.
2. Select your target scale factor and tweak the threshold or gap values to verify the detected bounding boxes on the live preview canvas.
3. Click the batch process button to automatically upscale, slice, and download your individual numbered frames.
Local Development & Deployment
Clone the repository, name your file ⁠index.html⁠, and push it to your GitHub repository. Turn on GitHub Pages in your repository settings to host the tool directly on the web.
