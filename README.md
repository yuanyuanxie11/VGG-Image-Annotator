# VGG-Image-Annotator

## Description
A comprehensive tool for annotating images (manual) and extracting textual and tabular content (automate) using Optical Character Recognition (OCR). This project utilizes the VGG Image Annotator and provides a workflow to arrange text elements vertically, ideal for creating annotated image datasets and extracting structured data from images.

## Features
- **Image Annotation**: Utilize the VGG Image Annotator to mark and annotate regions of interest within images. 
- **Text Extraction**: Extract text from annotated regions using OCR technology.
- **Table Processing**: Extract tabular data from images and ensure accuracy with manual corrections.
- **Vertical Arrangement**: Arrange extracted text elements vertically for a cohesive presentation.
- **PDF Conversion**: Convert images and extracted data into a PDF format.


## Implementation Details

In this project, I mainly focus on the implementation of Moody's historical manual approach to deal with vertical text arrangement, which contrasts with the typical horizontal layout favored by computer reading systems. This approach ensures that the text is presented in a more human-readable format, following traditional document structures.

## References

VGG Image Annotator (VIA) from Oxford University: VIA is a tool for annotating images and videos. It provides a user-friendly interface for creating bounding boxes, polygons, and other shapes for object annotation. You can learn more and access the tool here: https://www.robots.ox.ac.uk/~vgg/software/via/

OCR Technology: There are several OCR tools available, such as Tesseract, Google Cloud Vision, and AWS Textract. These tools can help extract text from images efficiently.

## Installation
To use this tool, you'll need to install the following dependencies:

```bash
pip install img2pdf Pillow pikepdf
