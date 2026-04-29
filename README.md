# DeepSignSecure

DeepSignSecure is an AI-based signature verification web application built using Python and Flask. The system uses machine learning techniques to analyze and verify handwritten signatures.

## Features

* Upload and verify signature images
* AI-based authenticity detection
* Simple and user-friendly interface
* Built with Flask, HTML, CSS, and JavaScript

## AI Integration

This project applies machine learning concepts to compare signature patterns and classify them as genuine or forged.

## Project Structure

* app.py – Main Flask application
* templates/ – HTML files
* static/ – CSS, JavaScript, and UI assets

## Important Note

To ensure the repository remains lightweight and easy to upload to GitHub, the following folders and files have been intentionally excluded:

* Signature dataset
* Trained model files
* Uploaded images (static/uploads)
* Local database files

These components are large in size and are not required to understand the application logic. They were excluded using `.gitignore`.

## How to Run

1. Install dependencies:
   pip install -r requirements.txt

2. Run the application:
   python app.py

3. Open in browser:
   http://127.0.0.1:5000/

## Conclusion

This project demonstrates how AI can be integrated with web applications to solve real-world problems like signature verification while maintaining a clean and efficient codebase.
