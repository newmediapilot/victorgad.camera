
# AR Image Display Project

This project creates an augmented reality (AR) experience using A-Frame and AR.js, displaying a floating gallery of 62 images in 3D space. Each image is assigned a unique AR marker, enabling users to view them in AR on compatible devices.

## Overview

- **Libraries**: Uses **A-Frame** for 3D rendering and **AR.js** for marker-based AR, specifically barcode markers.
- **Functionality**: Each image, located in `./slides`, is rendered on an AR marker as a 3D element. The markers create a "floating" effect when viewed through AR-enabled devices.

## Files

- **index.html**: Sets up the AR scene with `<a-scene>`, links to libraries, and includes a camera for viewing.
- **main.js**: Generates 62 markers and images dynamically, each with a barcode marker for 3D display.

## Summary

This AR project combines A-Frame and AR.js to create a browser-based 3D gallery, with images "floating" on barcode markers for interactive viewing in augmented reality.