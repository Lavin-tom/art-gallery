# AR Art Gallery

## Overview

This project demonstrates how to create an Augmented Reality (AR) experience using Three.js and the WebXR API. Users can place images in their environment through their device's camera, providing a seamless integration of virtual images into the real world. The application includes logging features to provide feedback on the AR session.

## Features

- **Image Placement**: Users can place multiple images in the AR space.
- **Logging**: The application logs messages to provide feedback on actions, like loading images and detecting surfaces.
- **Surface Detection**: The app uses hit-testing to identify flat surfaces for image placement.
- **User Interaction**: Tap to place images and click to remove them.

## Technologies Used

- [Three.js](https://threejs.org/): A JavaScript library for 3D graphics.
- [WebXR API](https://developer.mozilla.org/en-US/docs/Web/API/WebXR_Device_API): A browser API to support VR and AR experiences.

## Getting Started

### Prerequisites

- A modern web browser that supports WebXR (e.g., Chrome, Firefox).
- A device with a camera (smartphone or AR-capable tablet).

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Lavin-tom/art-gallery.git
   cd art-gallery
   ```

2. Open `index.html` in your browser.

### Project Structure

```
ar-image-placement/
│
├── assets/          # Contains image assets for AR placement
│   ├── ar1.jpg
│   ├── ar2.jpg
│   └── ar3.jpg
│
├── css/
│   └── index.css    # Custom styles for the application
│
├── index.html       # Main HTML file
│
└── README.md        # Project documentation
```

## How to Use

1. Stand in an area with at least 4 feet of empty space.
2. Point your camera at a flat surface when prompted.
3. Tap the screen to place the AR images.
4. Click on an image to remove it from the scene.

## Logging

The application displays messages in the log container for actions such as:

- Initializing AR session
- Loading images
- Placing images in the AR space
- Surface detection status

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any enhancements or bug fixes.