# Hand Gesture Volume Control

*Created by Ganesh Ajegaonkar*

**Description**

This project lets you control your system's volume using hand gestures detected by your webcam. Pinch your thumb and index finger to decrease volume, and spread your fingers to increase it. It leverages OpenCV for hand landmark detection and PyQt5 for the graphical user interface.

**Requirements**

The project necessitates these Python modules. Install them using the included `requirements.txt` file:

* opencv-python
* pyqt5
* mediapipe (for hand landmark detection)
* pycaw (for system volume control - Windows only)

**Usage**

1. **Run the Script:** Double-click the `main.py` script or execute it from the command line with `python main.py`.
2. **Grant Camera Access:** If prompted, allow the application to access your webcam.
3. **Control Volume:** Open the application window and start using hand gestures:
   - Pinch thumb and index finger to decrease volume.
   - Spread fingers apart to increase volume.

**Note:**

* This project is currently designed for Windows systems using `pycaw`. You might need to modify the volume control logic for other operating systems.

**Contribution**

We welcome contributions to enhance this project! If you have suggestions or bug fixes, feel free to create a pull request on the project's GitHub repository .

**License**

This project is licensed under the MIT License .

**Contact**

For any questions or feedback, feel free to contact Ganesh Ajegaonkar (email-ganeshajegaonkar@gmail.com).

**Additional Notes**

* You can customize the gesture recognition logic to map different hand configurations to volume changes.
* Consider incorporating error handling and user feedback messages for a more robust experience.
* Explore integrating audio visualization or a volume level display in the PyQt5 interface.