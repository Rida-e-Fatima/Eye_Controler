
![image](https://github.com/user-attachments/assets/a0ab1d87-79b1-42cf-9879-262b49d82491)

# Eye-Controlled Mouse Project

This project leverages computer vision and eye-tracking to control the mouse cursor and perform left-click actions using eye movements. The right eye is used to control cursor movement, while the left eye triggers a left-click when it detects a blink.

## Features

- **Right Eye Movement for Cursor Control:** The right eye controls the position of the mouse cursor on the screen, allowing for intuitive movement without the need for a physical mouse.
- **Left Eye Blink for Left-Click:** A quick blink or "twitch" of the left eye triggers a left-click, making it easy to select items or interact with elements on the screen.

## Getting Started

Follow these steps to set up the project on your machine.

### Prerequisites

Ensure you have Python and the required libraries installed:

- Python 3.x
- OpenCV
- Mediapipe
- PyAutoGUI

Install the dependencies with:

```bash
pip install opencv-python mediapipe pyautogui
```

### Installation

1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/yourusername/eye-controlled-mouse.git
    ```
   
2. Navigate to the project directory:
    ```bash
    cd eye-controlled-mouse
    ```

3. Run the project:
    ```bash
    python eye_controller.py
    ```

## Usage

1. **Launch the Script:** Start the eye-controlled mouse by running the script. Make sure your webcam is enabled.
2. **Position Your Eyes:** Position your face so the camera can detect both eyes clearly.
3. **Move the Cursor with Your Right Eye:** Look in the direction you want the cursor to move. The right eye controls the cursor’s movement across the screen.
4. **Left Click with a Left Eye Blink:** To perform a left-click, quickly blink your left eye. The program will recognize the blink as a click action.

## Troubleshooting

- **Cursor Movement Issues:** Ensure proper lighting and adjust your position so the camera can accurately track eye movement.
- **False Clicks:** If clicks are triggered unintentionally, try to blink more deliberately. Adjust sensitivity in the code if needed.

## Future Improvements

- **Double Click Detection:** Implement double-click functionality with rapid consecutive blinks.
- **Right-Click Action:** Add right-click functionality with specific eye movements or blink patterns.

## Contributing

Contributions are welcome! Please fork the repository, make your changes, and submit a pull request for review.

