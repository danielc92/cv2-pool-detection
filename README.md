# Pool Detection
Detecting pools from aerial imagery using `cv2` library in python.

# Before you get started
Concepts and methods you should know before working with repository.
- Basic understand of cv2 library for python3
- Loading and converting images colour scales
- Understanding the HSV colour space (hue, saturation, value)
- Object detection through contours
- Understanding how to create contours, filter them, draw boundaries around them

# Setup
This project uses `python3`

**How to obtain this repository:**
```sh
git clone https://github.com/danielc92/pool-detection.git
```
**Modules/dependencies:**
- `cv2`
- `jupyter`

**Install the following dependences:**
```sh
pip install cv2 jupyter
```

# Tests
These tests were ran successfully;
- Import an image and detecting contours using `HSV` colour ranges
- Eliminating contours below the area threshhold in `config` dict
- Eliminating contours within other contours (duplicates)
- Showing image detection results inline notebook, as well as exporting results to `.png`
- Record coordinates of bounding boxes

# Contributors
- Daniel Corcoran

# Sources
- [Aerial Imagery - spookfish](https://spookfish.com)
- [Contour Features OpenCV Documentation](https://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_imgproc/py_contours/py_contour_features/py_contour_features.html)
- [How to define a threshold value to detect only green colour objects in an image :Opencv [duplicate]](https://stackoverflow.com/questions/47483951/how-to-define-a-threshold-value-to-detect-only-green-colour-objects-in-an-image/47483966#47483966)
-  [HSL and HSV - Wikipedia](https://en.wikipedia.org/wiki/HSL_and_HSV)
