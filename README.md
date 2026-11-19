🎨 Real-Time Multi-Color Detection Using OpenCV

A real-time multi-color detection system built using Python, OpenCV, NumPy, and Matplotlib. This project detects and tracks 10 different colors through a webcam, displays bounding boxes around detected objects, and generates graphical reports automatically.

🚀 Features
🎯 10 Color Detection: Detects Red, Green, Blue, Yellow, Orange, Pink, Purple, Brown, White, and Black.
📷 Real-Time Webcam Detection: Detects multiple colors using a live webcam feed.
🔲 Bounding Boxes: Draws bounding boxes around detected colored objects.
🏷️ Color Labels: Displays the detected color name on the screen.
📊 Bar Graph: Displays the number of detections for each color.
🥧 Pie Chart: Visualizes the distribution of detected colors.
📈 Timeline Graph: Shows color detection activity over time.
📋 Dashboard: Generates a visual summary of detection results.
💾 CSV Export: Saves detection results into a CSV file.
🛠️ Technologies Used
Technology	Description
Python 3	Main programming language
OpenCV	Real-time image processing and color detection
NumPy	Numerical computations and array operations
Matplotlib	Graphs and data visualization
📁 Project Structure
text
real-time-multi-color-detection-opencv/
│
├── color_detection.py
├── README.md
├── requirements.txt
└── output/
    ├── graphs/
    └── detection_results.csv


Note: The output folder and filenames are illustrative. Actual files depend on your Python code.

⚙️ Installation and Setup
1. Clone the Repository
bash
git clone https://github.com/Aryanchandra0776/real-time-multi-color-detection-opencv.git

2. Navigate to the Project Folder
bash
cd real-time-multi-color-detection-opencv

3. Install Required Libraries
bash
pip install -r requirements.txt


Alternatively, install the libraries directly:

bash
pip install opencv-python numpy matplotlib

4. Run the Project
bash
python color_detection.py

🎮 How to Use
Open the project in VS Code.
Run the color_detection.py file.
Allow webcam access if requested.
Show different colored objects in front of your webcam.
The system detects colors and displays bounding boxes with color labels.
Press Q in the webcam window to stop detection.
The application generates graphs and saves detection results to a CSV file.
🎨 Supported Colors

The system detects the following 10 colors:

🔴 Red
🟢 Green
🔵 Blue
🟡 Yellow
🟠 Orange
🩷 Pink
🟣 Purple
🟤 Brown
⚪ White
⚫ Black
📊 Project Output

The application generates the following visualizations:

Color Detection Bar Graph
Color Distribution Pie Chart
Detection Timeline
Color Detection Dashboard
CSV Detection Report
💡 Applications
Computer Vision
Real-Time Object Detection
Color-Based Object Tracking
Image Processing
Educational Computer Vision Projects
🔮 Future Improvements
Add more color categories.
Improve detection accuracy under different lighting conditions.
Add object tracking.
Build a graphical user interface.
Export detection reports in additional formats.
👨‍💻 Author

Aryan Chandra

GitHub: @Aryanchandra0776
⭐ Show Your Support

If you find this project useful, please consider giving it a ⭐ on GitHub.

Developed with ❤️ using Python, OpenCV, NumPy, and Matplotlib.
