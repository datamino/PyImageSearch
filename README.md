# PyImageSearch - Computer Vision & Image Processing Journey

Welcome to my comprehensive computer vision and image processing learning repository! This repo contains my hands-on implementations, experiments, and projects as I master OpenCV, image processing techniques, and computer vision algorithms.

## 📚 Repository Structure

```
PyImageSearch/
├── 01-OpenCV-Fundamentals/     # Basic OpenCV operations and concepts
├── 02-Image-Processing/        # Filtering, enhancement, transformations
├── 03-Feature-Detection/       # Corners, edges, keypoints, descriptors
├── 04-Object-Detection/        # Detection, tracking, recognition
├── 05-Deep-Learning-CV/        # Neural networks for computer vision
├── 06-Advanced-Applications/   # Real-world projects and applications
├── assets/                     # Images, datasets, and resources
├── utils/                      # Helper functions and utilities
└── docs/                       # Documentation and guides
```

## 🎯 Learning Modules

### Module 01: OpenCV Fundamentals
- **Day 01**: [Loading and Displaying Images](./01-OpenCV-Fundamentals/Day-01-Loading-Images/) ✅
- **Day 02**: [Basic Image Operations](./01-OpenCV-Fundamentals/Day-02-Basic-Operations/)
- **Day 03**: [Drawing Functions and Shapes](./01-OpenCV-Fundamentals/Day-03-Drawing-Functions/)
- **Day 04**: [Mouse Events and Trackbars](./01-OpenCV-Fundamentals/Day-04-Mouse-Events/)
- **Day 05**: [Image Transformations](./01-OpenCV-Fundamentals/Day-05-Transformations/)
- **Day 06**: [Color Spaces and Conversions](./01-OpenCV-Fundamentals/Day-06-Color-Spaces/)
- **Day 07**: [Project - Interactive Image Viewer](./01-OpenCV-Fundamentals/Day-07-Project-Viewer/)

### Module 02: Image Processing
- **Day 01**: [Filtering and Blurring Techniques](./02-Image-Processing/Day-01-Filtering-Blurring/)
- **Day 02**: [Edge Detection Algorithms](./02-Image-Processing/Day-02-Edge-Detection/)
- **Day 03**: [Morphological Operations](./02-Image-Processing/Day-03-Morphological-Ops/)
- **Day 04**: [Thresholding and Segmentation](./02-Image-Processing/Day-04-Thresholding/)
- **Day 05**: [Contours and Shape Analysis](./02-Image-Processing/Day-05-Contours-Shapes/)
- **Day 06**: [Histogram Analysis and Equalization](./02-Image-Processing/Day-06-Histograms/)
- **Day 07**: [Project - Document Scanner](./02-Image-Processing/Day-07-Project-Scanner/)

### Module 03: Feature Detection & Matching
- **Day 01**: [Harris Corner Detection](./03-Feature-Detection/Day-01-Harris-Corners/)
- **Day 02**: [SIFT and SURF Descriptors](./03-Feature-Detection/Day-02-SIFT-SURF/)
- **Day 03**: [ORB Feature Detection](./03-Feature-Detection/Day-03-ORB-Features/)
- **Day 04**: [Feature Matching Algorithms](./03-Feature-Detection/Day-04-Feature-Matching/)
- **Day 05**: [Homography and Perspective](./03-Feature-Detection/Day-05-Homography/)
- **Day 06**: [Image Stitching Techniques](./03-Feature-Detection/Day-06-Image-Stitching/)
- **Day 07**: [Project - Panorama Creator](./03-Feature-Detection/Day-07-Project-Panorama/)

### Module 04: Object Detection
- **Day 01**: [Template Matching](./04-Object-Detection/Day-01-Template-Matching/)
- **Day 02**: [Haar Cascade Classifiers](./04-Object-Detection/Day-02-Haar-Cascades/)
- **Day 03**: [HOG Descriptor Method](./04-Object-Detection/Day-03-HOG-Descriptor/)
- **Day 04**: [Background Subtraction](./04-Object-Detection/Day-04-Background-Subtraction/)
- **Day 05**: [Optical Flow Tracking](./04-Object-Detection/Day-05-Optical-Flow/)
- **Day 06**: [Mean Shift and CAM Shift](./04-Object-Detection/Day-06-MeanShift-CAMShift/)
- **Day 07**: [Project - Motion Tracker](./04-Object-Detection/Day-07-Project-Tracker/)

### Module 05: Deep Learning with OpenCV
- **Day 01**: [Loading Pre-trained DNN Models](./05-Deep-Learning-CV/Day-01-Pretrained-Models/)
- **Day 02**: [Image Classification with CNNs](./05-Deep-Learning-CV/Day-02-Image-Classification/)
- **Day 03**: [Object Detection with YOLO](./05-Deep-Learning-CV/Day-03-YOLO-Detection/)
- **Day 04**: [Semantic Segmentation](./05-Deep-Learning-CV/Day-04-Semantic-Segmentation/)
- **Day 05**: [Face Recognition Systems](./05-Deep-Learning-CV/Day-05-Face-Recognition/)
- **Day 06**: [Neural Style Transfer](./05-Deep-Learning-CV/Day-06-Style-Transfer/)
- **Day 07**: [Project - Smart Security System](./05-Deep-Learning-CV/Day-07-Project-Security/)

### Module 06: Advanced Applications
- **Day 01**: [3D Computer Vision](./06-Advanced-Applications/Day-01-3D-Vision/)
- **Day 02**: [Stereo Vision and Depth](./06-Advanced-Applications/Day-02-Stereo-Vision/)
- **Day 03**: [Camera Calibration](./06-Advanced-Applications/Day-03-Camera-Calibration/)
- **Day 04**: [Augmented Reality Basics](./06-Advanced-Applications/Day-04-AR-Basics/)
- **Day 05**: [Real-time Processing Optimization](./06-Advanced-Applications/Day-05-Optimization/)
- **Day 06**: [Custom Algorithm Development](./06-Advanced-Applications/Day-06-Custom-Algorithms/)
- **Day 07**: [Final Project - Complete CV Application](./06-Advanced-Applications/Day-07-Final-Project/)

## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- pip or uv (package manager)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/YOUR_USERNAME/PyImageSearch.git
   cd PyImageSearch
   ```

2. **Set up virtual environment:**
   ```bash
   # Using uv (recommended)
   uv venv
   source .venv/bin/activate  # Linux/Mac
   # .venv\Scripts\activate   # Windows
   
   # Or using pip
   python -m venv .venv
   source .venv/bin/activate
   ```

3. **Install dependencies:**
   ```bash
   # Using uv
   uv pip install -r requirements.txt
   
   # Or using pip
   pip install -r requirements.txt
   ```

## 📦 Dependencies

- **OpenCV**: `opencv-python`
- **NumPy**: For numerical operations
- **Matplotlib**: For plotting and visualization
- **Pillow**: Additional image processing
- **Jupyter**: For interactive notebooks (optional)

## 📁 Folder Structure Explained

### Week Folders
Each week focuses on a specific computer vision topic with daily progressive learning:
- `README.md` - Week overview and objectives
- `Day-XX/` - Daily implementation with focused learning goals

### Day Folders
- `*.py` - Main implementation files
- `images/` - Input/output images specific to that day
- `README.md` - Day-specific notes, concepts, and results

### Assets
- `images/` - Common images used across multiple projects
- `datasets/` - Larger datasets for training/testing

### Utils
- Helper functions and common utilities
- Reusable code components

## 🎯 Learning Objectives

By the end of this journey, I aim to master:

- **Core OpenCV Functions**: Image I/O, transformations, filtering
- **Image Processing**: Enhancement, restoration, analysis
- **Feature Detection**: Corners, edges, keypoints
- **Object Recognition**: Detection, tracking, classification
- **Deep Learning Integration**: Pre-trained models, custom training
- **Real-world Applications**: Building complete CV systems

## 📈 Progress Tracking

- ✅ **Completed**: Task finished with working code
- 🔄 **In Progress**: Currently working on
- 📝 **Planned**: Scheduled for future
- 🎯 **Project**: Milestone project

## 🤝 Contributing

This is a personal learning repository, but feel free to:
- Open issues for questions or suggestions
- Submit pull requests for improvements
- Share your own implementations

## 📚 Resources

- [OpenCV Documentation](https://docs.opencv.org/)
- [PyImageSearch Blog](https://pyimagesearch.com/)
- [Computer Vision Fundamentals](https://opencv.org/)

## 📝 Notes

Each week builds upon previous knowledge, so following the sequence is recommended. Code includes detailed comments explaining computer vision concepts and implementation details.

## 📧 Contact

Feel free to reach out for questions, collaborations, or discussions about computer vision!

---

**Happy Learning! 🚀📸**