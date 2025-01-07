
# 🚗 Lane Detection & Lane Marking System 🚧

This project combines two key functionalities:
1. **Lane Detection** - Detects lanes in road videos using computer vision techniques.
2. **Lane Marking** - Marks lanes to help visualize detected lanes on road footage.

Both components are implemented using **OpenCV**, **MoviePy**, and other relevant libraries.

## 🚀 Features
- **Lane Detection**: Detect lanes on the road using edge detection and Hough transform.
- **Lane Marking**: Automatically mark the detected lanes on the original footage.
- **Real-time Detection**: Works on video footage, processing and outputting in real-time.
- **Camera Calibration**: Calibrates the camera for accurate lane detection using calibration techniques.
- **Preprocessing**: Processes the video input for optimal lane detection and marking.

## 📦 Installation

To run this project locally, follow these steps:

### 1. Clone the repository
```bash
git clone https://github.com/shuvam-bhatt/lane-detection-lane-marking.git
cd lane-detection-lane-marking
```

### 2. Install dependencies
You'll need Python and some required libraries:
```bash
pip install -r requirements.txt
```

### 3. Prepare your video footage
- Place your video file in the `videos/` folder or modify the script to specify the path to your video file.

### 4. Run the lane detection and marking
Run the script to detect and mark lanes on your video.
```bash
python lane_detection.py --input_video path_to_video.mp4
```

## 🛠️ Usage

1. **Lane Detection**: 
   - Uses edge detection and Hough transform to identify lane boundaries in a given road video.
   - Works well for both straight and curved lanes.

2. **Lane Marking**: 
   - Visualizes the detected lanes by overlaying them on the video.
   - Makes it easy to track lane positions in real-time driving footage.

## 🧰 Technologies Used
- **OpenCV**: For image processing and lane detection.
- **MoviePy**: For video editing and output.
- **NumPy**: For array handling and mathematical operations.

## 🏆 Contributing
We welcome contributions! If you'd like to help improve this project, please fork the repository and submit a pull request. Contributions can be in the form of bug fixes, enhancements, or new features.

### How to contribute:
1. Fork the repo.
2. Create a new branch: `git checkout -b feature-name`.
3. Make your changes.
4. Commit your changes: `git commit -am 'Add feature-name'`.
5. Push to the branch: `git push origin feature-name`.
6. Open a pull request.


