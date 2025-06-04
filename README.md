# 🖼️ RGB Image Processing Application

## 📌 Overview

This C++ project implements various basic **image processing** operations such as:
- Grayscale Conversion
- Image Merging
- Brightness Adjustments (Darken / Lighten)
- Edge Detection
- Purple Filter (Custom Effect)

All operations are performed through a user-friendly console menu.

## 🧑‍💻 Authors

- **Ahmed Sheref Sayed**  
  ID: 20230542  
  Email: [ahmedsheref2288@yahoo.com](mailto:ahmedsheref2288@yahoo.com)

## 📂 Project Structure

bash
├── Image_Class.h         # Header file for the Image class
├── main.cpp              # Main driver file (your current code)
├── assets/               # Folder to store input/output images
├── README.md             # Project documentation
🔧 Features
Input validation and safe file access handling

Colored terminal UI using ANSI escape codes (Red, Green, Blue)

Interactive image editor with looping menu

Image I/O and transformation using a custom Image class

📷 Supported Image Formats
The application supports saving edited images in the following formats:

.jpg

.bmp

.png

.tga
----------
🔄 Menu Options
1: Convert image to grayscale

2: Merge two images

3: Darken or lighten the image

4: Detect edges in the image

5: Apply a purple filter effect

6: Exit the program

You will also be prompted to:

Save the edited image

Continue editing the same or different images

📌 Dependencies
Ensure that Image_Class.h and its implementation supports the following methods:

Image(string filename) — load image

saveImage(string filename) — save image

Public attributes: width, height, and pixel data access
