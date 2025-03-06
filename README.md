# Face Recognition Application

This is a Python-based face recognition application that uses OpenCV and Haar Cascade classifier to detect faces in real-time from a webcam feed.

## Requirements

- Python 3.13
- OpenCV (`opencv-python` package)

## Installation

1. **Clone the repository** (if applicable):
   ```bash
   git clone https://github.com/your-repo/face-recognition.git
   cd face-recognition
   ```

2. **Create a virtual environment**:
   ```bash
   python -m venv venv
   ```

3. **Activate the virtual environment**:
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```

4. **Install the required packages**:
   ```bash
   pip install opencv-python
   ```

## Usage

1. **Run the application**:
   ```bash
   python main.py
   ```

2. **Interact with the application**:
   - The application will open a window showing the webcam feed.
   - Detected faces will be highlighted with a rectangle.
   - Press the `q` key to exit the application.

## Notes

- Ensure that the `haarcascade_frontalface_default.xml` file is present in the project directory.
- The application uses the default webcam (index 0). If you have multiple cameras, you may need to adjust the index in the `cv2.VideoCapture(0)` line in `main.py`.

## License

This project is open-source and available under the MIT License.
