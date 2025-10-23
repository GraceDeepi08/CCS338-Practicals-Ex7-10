# CCS338-Practicals-Ex7-10: CV Calibration Labs

**Implementation of Anna University CCS338 Computer Vision practical sessions (Exercises 7-10) in Jupyter Notebook.** *Focus: Camera calibration using circular grid patterns with OpenCV.* Covers distortion correction, homography, and parameter estimation—core to Unit 3 of the syllabus.

## Syllabus Context (CCS338)
- **Labs Covered**:
  - **Ex 7**: Circular grid detection – Identify and extract corners from grid images using OpenCV's `findCirclesGrid`.
  - **Ex 8**: Homography computation – Estimate transformation matrices between grid points and image coordinates.
  - **Ex 9**: Intrinsic matrix estimation – Compute camera parameters with `calibrateCamera` for focal length and principal point.
  - **Ex 10**: Undistortion & reprojection error – Apply distortion correction and evaluate accuracy with reprojection metrics.
- Official syllabus: [Anna University CCS338](https://www.annauniv.edu/syllabus/ug/2021/1.pdf) (pg. 45-50 for CV unit).

## Files
- **CV exercise 7 - 10.ipynb**: Complete notebook containing all exercises 7-10 with code, explanations, and outputs. Refer to this for step-by-step execution and visualizations.
- **cv_ex7_to10.py**: Python script version of the labs—run directly in terminal or IDE for non-interactive use. Refer to this for clean, exportable code without Jupyter dependencies.

## How to Run (CCS338 Lab Setup)
1. **Environment**: Python 3.8+, Jupyter.
   - Install: `pip install opencv-python numpy matplotlib jupyter`.
2. **Local**: `git clone https://github.com/GraceDeepi08/CCS338-Practicals-Ex7-10.git` > `jupyter notebook CV exercise 7 - 10.ipynb` > Run All.
3. **Colab**: Upload notebook > `!pip install opencv-python` > Execute cells.

**Pro Tip**: Use your own camera photos for grids—tune flags for accuracy.

## What You'll Learn
- How OpenCV's `calibrateCamera` works for real lenses.
- Using error metrics to iterate and validate calibration—aim for <1% radial distortion.
- Real-world applications: AR/VR, self-driving cars.

## Credits & License
- **Code**: Original by [GraceDeepi08](https://github.com/GraceDeepi08).
- **Syllabus**: Anna University (public educational use).
- **License**: MIT—share, fork, or adapt for your labs!

---

*Updated: Oct 23, 2025* | #CCS338 #ComputerVision #OpenCV #AnnaUniversity
