# DICOM Viewer with Multi-Planar Reconstruction (MPR)

## 🖥️ Overview
The **DICOM Viewer** is a graphical user interface (GUI) tool designed to load and view medical imaging data from DICOM series or NIfTI files. It provides multi-planar reconstruction (axial, coronal, sagittal) and features for adjusting brightness, contrast, and more.

---

## ✨ Features
- **Multi-Planar Reconstruction (MPR):**
  - Axial, Coronal, and Sagittal views with real-time updates.
- **Adjustable Parameters:**
  - Brightness and contrast sliders for each view.
- **Interactive Controls:**
  - Slice selection sliders.
  - Cine mode for automatic slice animation.
- **Cursor Inspector:**
  - Cross-referencing between views.
- **Save Slices:**
  - Save selected slices as images (`.png` or `.jpg`).
- **Mouse Interaction:**
  - Zooming and clicking to adjust views.

---

## 🛠️ Requirements
To run this project, you need the following:
- **Python 3.7+**
- Libraries:
  - `SimpleITK`
  - `Matplotlib`
  - `Tkinter`
  - `Numpy`

Install dependencies using:
```bash
pip install SimpleITK matplotlib numpy
