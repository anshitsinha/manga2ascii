Image2Ascii
Image2Ascii is a simple web application that allows you to upload an image and convert it into pure ASCII art. This README provides an overview of the project structure and how to use the application.

How to Use
To use Image2Ascii, follow these steps:

Clone or download the repository to your local machine.
Open the index.html file in a web browser.
File Structure
The project contains the following files:

index.html: HTML file containing the structure of the web application.
style.css: CSS file defining the styles for the web application.
src/index.js: JavaScript file containing the logic for converting images to ASCII art.
Features
Upload an image: Use the provided file input to select an image from your local file system.
Convert to ASCII art: The application converts the uploaded image into ASCII art using a predefined character set.
Display ASCII art: The converted ASCII art is displayed below the image upload area.
How it Works
When you upload an image, the application reads the image data and converts it into grayscale values.
The grayscale values are then mapped to ASCII characters based on their intensity.
The ASCII representation of the image is displayed below the original image.