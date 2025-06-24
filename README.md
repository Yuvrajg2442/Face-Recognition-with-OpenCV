# Face Recognition with OpenCV and face_recognition

This is a simple Python project that demonstrates face recognition using the `face_recognition` and `OpenCV` libraries. In this project, we compare two images to determine if they contain the same person.

---

## Project Overview

The program:
- Loads two images.
- Detects faces in both images.
- Encodes the detected faces.
- Compares the faces to check if they match.
- Displays the comparison result and the face distance (similarity measure).

---

## Requirements

Make sure you have the following libraries installed:
- `face_recognition`
- `opencv-python`
- `numpy`

You can install them using:
```bash
pip install face_recognition opencv-python numpy

---

## How to Run
Place your reference image and the test image inside an images folder.

Update the image file names in the code if needed:

python
Copy
Edit
imgElon = face_recognition.load_image_file("images/elon musk.jpg")
imgTest = face_recognition.load_image_file("images/elon_test.jpg")
Run the Python script:

bash
Copy
Edit
python your_script_name.py
The program will:

Draw rectangles around detected faces.

Show the comparison result and similarity score.

Display both images with annotations.

Output Example
The console will print something like:

css
Copy
Edit
[True] [0.45]
True means the faces match.

The face distance indicates how similar the faces are (lower means more similar).

Notes
Make sure the image paths are correct and properly formatted (use / or \\ depending on your OS).

The face_recognition library is based on deep learning models and provides high accuracy, but lighting, angles, and image quality can still affect results.

Credits
Thanks to the creators of:

face_recognition

OpenCV team

diff
Copy
Edit

If you want, I can help you add:
- Screenshot sections  
- Example images  
- Live webcam extension  

Just let me know!









