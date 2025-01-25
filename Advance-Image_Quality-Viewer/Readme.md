# Advanced Image Quality Viewer

The **Advanced Image Quality Viewer** is a PyQt5-based desktop application for visualizing and enhancing image quality. It offers a variety of tools, including zooming, contrast adjustment, noise addition/removal, and SNR/CNR measurement, along with support for cropping and saving images.

## Features

1. **Image Display**: Load and display grayscale or color images in three views: Input, Output 1, and Output 2.
2. **Zoom and Pan**: Use Ctrl + Mouse Wheel for zooming; drag to pan.
3. **Brightness and Contrast Adjustment**: Fine-tune image brightness and contrast with sliders.
4. **Noise Manipulation**: Add Gaussian, Salt & Pepper, or Speckle noise to images.
5. **Denoising Filters**: Apply Median, Gaussian, or Non-local Means filtering.
6. **Frequency Filters**: Use lowpass or highpass filters to modify images.
7. **Histogram Visualization**: View grayscale and RGB histograms for loaded images.
8. **Contrast Enhancement**: Choose from Histogram Equalization, CLAHE, or custom stretching.
9. **ROI Selection**: Select regions of interest for cropping or SNR/CNR measurements.
10. **Keyboard Shortcuts**: Enhance productivity with hotkeys for common operations.
11. **Saving Images**: Save processed images in various formats.

## Installation
# Advanced Image Quality Viewer

The **Advanced Image Quality Viewer** is a PyQt5-based desktop application for visualizing and enhancing image quality. It offers a variety of tools, including zooming, contrast adjustment, noise addition/removal, and SNR/CNR measurement, along with support for cropping and saving images.

![Main Window](assets/screenshots/main_window.png)

## Features

1. **Image Display**: Load and display grayscale or color images in three views: Input, Output 1, and Output 2.

   ![Zoom Feature](assets/screenshots/zoom_feature.png)

2. **Zoom and Pan**: Use Ctrl + Mouse Wheel for zooming; drag to pan.

   ![ROI Selection](assets/screenshots/roi_selection.png)

3. **Brightness and Contrast Adjustment**: Fine-tune image brightness and contrast with sliders.

4. **Histogram Visualization**: View grayscale and RGB histograms for loaded images.

   ![Histogram View](assets/screenshots/histogram_view.png)

## Installation

### Requirements

- Python 3.x
- Required libraries: `PyQt5`, `numpy`, `opencv-python`, `matplotlib`

### Steps

1. Clone this repository:
   ```bash
   git clone https://github.com/your-repository/advanced-image-viewer.git
   cd advanced-image-viewer
