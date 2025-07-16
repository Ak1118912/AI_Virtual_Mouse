# AI Virtual Mouse

A Python-based AI Virtual Mouse application that enables control of the computer cursor using hand gestures detected by a webcam. Built using **OpenCV** and **MediaPipe**, this project utilizes computer vision and deep learning techniques to enable touch-free, intuitive interaction with your desktop.

---

## Features

- Real-time hand tracking using your webcam
- Cursor movement mapped to hand motions
- Simulate left/right mouse clicks with finger gestures
- Works across Windows, Mac, and Linux desktops
- Minimal and user-friendly interface

---


## Getting Started

### Prerequisites

- Python 3.7 or newer
- [OpenCV](https://pypi.org/project/opencv-python/)
- [MediaPipe](https://pypi.org/project/mediapipe/)
- [pyautogui](https://pypi.org/project/pyautogui/) or [autopy](https://pypi.org/project/autopy/) for cursor control

### Installation

1. Clone the repository:
git clone https://github.com/your-username/ai-virtual-mouse.git
cd ai-virtual-mouse

2. Install the required packages:
pip install opencv-python mediapipe pyautogui

3. (Optional) If you use a different library for cursor control, install as needed.

### Running the App

Start the program with:
python main.py

---

## Usage

- The application will open a webcam window and detect your hand.
- Move your index finger to control the mouse cursor.
- Perform predefined gestures (e.g., index and thumb touch) to simulate click actions.
- Press 'q' or the designated key to exit.

---

## Project Structure

| File/Folder      | Purpose                              |
|------------------|--------------------------------------|
| `main.py`        | Entry point, video stream, hand logic|
| `hand_tracking.py`| Handles hand detection & gesture logic|
| `utils/`         | Helper scripts, configuration        |
| `README.md`      | Project overview and instructions    |

---

## Customization

- Update gesture recognition logic to add new controls.
- Change hand landmarks mapping for different pointer speeds or gestures.
- Enhance UI with PyQt or other libraries if a graphical interface is required.

---

## License

Released under the MIT License.

---

## Acknowledgments

- [MediaPipe Documentation](https://developers.google.com/mediapipe/)
- [OpenCV Python Documentation](https://docs.opencv.org/)
- [pyautogui Documentation](https://pyautogui.readthedocs.io/en/latest/)

---

Enjoy hands-free computing with your AI-powered virtual mouse!
