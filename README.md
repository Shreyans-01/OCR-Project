# OCR-Project

Omkar Sawant   1911118 COMPS B-4, 
Shreyans Mehta 1911124 COMPS B-4

Mentors: Pradnya Bhangale, Vaibhav Vasani

K.J. Somaiya College of Engineering

Prerequisites:
1. OpenCV Package (Installation Guide: https://pypi.org/project/opencv-python/)
2. Tesseract
  -Install pytesseract using pip install pytesseract
  -Install Tesseract Binaries from https://github.com/UB-Mannheim/tesseract/wiki. Download 32, 64 bit depending on your system.
  -Run the .exe file and finish the setup.
  -Setup a new enviroment variable called tesseract and locate to the recently setup folder called "Tesseract-OCR" and add \tesseract.exe in the end.

Instructions:
1. Change Path on Line 22 to the desired folder containing the images to be processed.
2. Repeat the above process on Line 190.
3. Run the file, it will open another Window.
4. Click on Open Image and choose an image.
5. Click on Manual Crop Button
6. Click the 4 corners of the image in the sequence - Top Left, Top Right, Bottom Left, Bottom Right
7. This will generate another window with cropped and aligned image.
8. On GUI window click on Detect Text Button,
9. Wait for a while and Et Voila, the detected text will be displayed on the Centre Text Box
