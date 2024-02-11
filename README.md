📢 This code project uses OpenCV for real-time hand tracking and CVZone for gesture recognition. With the help of Pynput and mediapipe, I can simulate keyboard inputs to control the arrow key up, down, left or right depending on my hand gestures. This project took me soo long to make...Hope you will like it.




🎯 HOW TO USE for controlling the up, down, left and right using hand gestures when the palm is facing in front of the camera,

📌 All 5 fingers OPEN   ---   UP Arrow key (pressed)

📌 All 5 fingers CLOSED   ---   DOWN Arrow key (pressed)

📌 2 fingers OPEN   ---   LEFT Arrow key (pressed)

📌 1 finger OPEN   ---   RIGHT Arrow key (pressed)





📢 This Python code uses OpenCV, Mediapipe, and pynput libraries to detect hand gestures and control keyboard inputs based on the detected hand gestures. Here's a clear and concise explanation of the code:

📢 The code imports necessary libraries such as OpenCV (cv2), Mediapipe (mp), and pynput.keyboard.It initializes a keyboard controller using pynput.The code sets up Mediapipe for hand detection and defines fingerTipIds to identify the fingertips.It captures video from the camera using OpenCV.Inside the main loop, it reads frames from the video and processes them for hand detection using Mediapipe.It extracts landmarks (finger positions) from the detected hand and draws them on the frame.The code then determines which fingers are open based on the landmark positions and counts the number of open fingers.Depending on the number of fingers open, it displays corresponding text on the frame and simulates keyboard input using pynput to control the keyboard (e.g.,pressing arrow keys).It continuously displays the processed video frame with hand landmarks and waits for the 'q' key to be pressed to exit the program.This code essentially creates a hand gesture recognition system that maps specific hand gestures to keyboard inputs for controlling a computer. For example, showing different numbers of fingers can simulate pressing different arrow keys or other keyboard commands.





🎯HOW IT IS SOO GOOD


🔑 Uses Open Computer Vision (OpenCV)

🔑 Tracks hands and Finger Tips Efficiently

🔑 Can operate 🕹️ the arrow keys without touching the laptop.



🏆 Made with ❤️ by Shamal Sharfaz
