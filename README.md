# Vehicle Speed Detection using YOLO 🚗💨
📌 Project Overview

This project is an AI-based Vehicle Speed Detection System developed using YOLOv8, OpenCV, and Python.
The system detects moving vehicles from a road video, tracks them, and calculates their speed based on the time taken to cross two predefined lines.

The project uses computer vision techniques for real-time vehicle monitoring and speed estimation.

🚀 Features
Vehicle detection using YOLOv8
Real-time object tracking
Speed calculation in Km/h
Vehicle counting (Up and Down directions)
Bounding box visualization
Frame saving functionality
Output video generation
🛠️ Technologies Used
Python
OpenCV
YOLOv8
Pandas
NumPy
📂 Project Structure
Vehicle-Speed-Detection/
│
├── main.py
├── tracker.py
├── road.mp4
├── yolov8s.pt
├── output.avi
├── detected_frames/
├── README.md
└── requirements.txt
⚙️ How It Works
The input road video is processed frame by frame.
YOLOv8 detects vehicles from each frame.
The tracker assigns IDs to detected vehicles.
Two reference lines are used for speed calculation.
The time taken for a vehicle to move between the lines is measured.
Speed is calculated using:

Speed=
Time
Distance
	​


Vehicle speed is displayed on the screen in Km/h.



▶️ Installation
Clone the Repository
git clone https://github.com/Ghouse707/projectspeed
Install Dependencies
pip install -r requirements.txt
▶️ Run the Project
python main.py
📊 Output
Detected vehicles with bounding boxes
Vehicle ID tracking
Speed display in Km/h
Saved output video
Saved detected frames
📸 Sample Output

(Add screenshots here)

🔮 Future Improvements
Speed violation alert system
Number plate recognition
Real-time CCTV integration
Web dashboard for monitoring
👨‍💻 Author

Ghouse Pasha
