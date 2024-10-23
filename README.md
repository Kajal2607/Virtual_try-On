
# Virtual Try-On Application

## Overview
This project is a **Virtual Try-On App** that provides an immersive fashion experience by allowing users to try on different outfits using hand gestures. The application takes a video as input, detects the user's pose in real-time, and applies fashion items (e.g., clothes, accessories) over the user's body. The output is a video showcasing the user "wearing" the selected items, offering a highly interactive and engaging virtual try-on experience.

The app is built using Python and leverages **cvzone** and **OpenCV (cv2)** for pose detection and computer vision functionalities. It utilizes hand gestures to allow users to interact with the app and switch between fashion items seamlessly. 

Collaborators:
- **Kajal**
- **Laaasya** (GitHub: [Laasya1512](https://github.com/Laasya1512/Virtual_try-on))

## Features
- **Real-time Pose Detection**: Detects the user's body pose in a live video stream using the OpenCV and cvzone libraries.
- **Hand Gesture Recognition**: Users can control the app with hand gestures to switch between different fashion items.
- **Seamless Outfit Application**: Selected fashion items are overlaid on the user's body in real-time, simulating a try-on experience.
- **Interactive Fashion Exploration**: Users can explore different styles and outfits within the app in a fun and immersive way.
- **Video Output**: The app generates a video where the user appears to be wearing the virtual outfits.

## Tech Stack
- **Programming Language**: Python
- **Libraries**:
  - **cv2 (OpenCV)**: For image and video processing.
  - **cvzone**: Simplifies pose detection, hand gesture recognition, and other computer vision tasks.

## Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Laasya1512/Virtual_try-on.git
   cd Virtual_try-on
   ```

2. **Install Required Dependencies**
   Make sure to install the necessary Python packages. You can use the provided `requirements.txt` file for easy setup.
   ```bash
   pip install -r requirements.txt
   ```

3. **Additional Dependencies**
   - `cv2`: Install OpenCV by running:
     ```bash
     pip install opencv-python
     ```
   - `cvzone`: Install cvzone for simplified computer vision tasks:
     ```bash
     pip install cvzone
     ```

## Usage

1. **Run the Application**:
   You can run the virtual try-on app by executing the following command:
   ```bash
   python main.py
   ```

2. **Input**:
   The app takes a video input from your webcam or a pre-recorded video file. Make sure your webcam is connected if you're running it live.

3. **Control with Hand Gestures**:
   Use predefined hand gestures to interact with the app and switch between different fashion items.

4. **Output**:
   The output is a video file showing you "wearing" the virtual outfit. This video will be saved in the designated output directory.

## Hand Gesture Controls
The app recognizes different hand gestures to control its functionalities:
- **Swipe Left**: Switch to the previous outfit.
- **Swipe Right**: Switch to the next outfit.
- **Open Hand**: Confirm outfit selection.

## Project Collaboration
This project was developed in collaboration with **Kajal** and **Laaasya**. You can check out more details and contributions by visiting the project's GitHub repository: [Virtual Try-On App](https://github.com/Laasya1512/Virtual_try-on).

## Future Enhancements
- Add more fashion items such as accessories and shoes.
- Improve gesture recognition for a wider range of controls.
- Integrate AI for personalized outfit recommendations.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact
If you have any questions or suggestions, feel free to reach out:
- Kajal: [GitHub](https://github.com/Kajal)
- Laaasya: [GitHub](https://github.com/Laasya1512)

