# PitchEye: Football Analysis Project ⚽

PitchEye is a project designed to analyze football (soccer) matches by detecting and tracking players, referees, and footballs in video footage. It leverages state-of-the-art AI object detection models, segmentation techniques, and motion analysis to provide insights into team performance and player dynamics.

## 🎥 Demo Video

![diagram (3)](https://github.com/DhruvSharma19/PitchEye/assets/112254552/52377374-1a36-4cab-a4d1-7ea8066e378c)
![diagram (2)](https://github.com/DhruvSharma19/PitchEye/assets/112254552/7125c41f-235b-460f-8b13-87533ec00f02)


## 🛠️ System Diagrams

## 🌟 Key Features

- Object Detection: Utilizes YOLO (You Only Look Once) for real-time object detection of players, referees, and footballs.
- Team Assignment: Assigns players to teams based on the colors of their t-shirts using K-means clustering.
- Performance Metrics: Calculates ball acquisition percentage, player speed, and distance covered for comprehensive match analysis.
- Optical Flow: Measures camera movement between frames to accurately track player movements.
- Perspective Transformation: Represents scene depth and perspective, allowing measurement of player movements in real-world units.

## 🛠 Technologies Used

- YOLO: AI object detection model
- Kmeans: Pixel segmentation and clustering for t-shirt color detection
- Optical Flow: Measure camera movement
- Perspective Transformation: Represent scene depth and perspective
- Speed and distance calculation per player

## Requirements 📋
To run this project, you need to have the following requirements installed:
- Python 3.x
- ultralytics
- supervision
- OpenCV
- NumPy
- Matplotlib
- Pandas

## 🖼️ Screenshots

## Getting Started 🚀
1. Clone this repository to your local machine.
2. Install the required dependencies listed in the `requirements.txt` file.
3. Follow the instructions in the project files to preprocess your video footage and run the analysis scripts.

## Usage 💻
1. Preprocess Video: Use preprocessing scripts to extract frames from video footage.
2. Run Object Detection: Utilize YOLO for object detection on the extracted frames.
3. Segment T-shirt Colors: Apply K-means clustering to segment and detect player t-shirt colors.
4. Analyze Performance: Calculate team metrics, player movements, and other performance indicators.
5. Visualize Results: Use Matplotlib and other visualization tools to present the analysis results.

## Contributing 🤝
Contributions are welcome! Please follow the standard GitHub workflow:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/xyz`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push your changes to the branch (`git push origin feature/xyz`).
5. Create a new Pull Request.

## Acknowledgements 🙏
- This project was inspired by the need for advanced football match analysis tools.
- We thank the creators and contributors of YOLO, OpenCV, and other open-source libraries used in this project.
  
🚀 Happy coding and analyzing! ⚽
