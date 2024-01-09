# Text Extractor/ OCR in Django

A Django web application designed for scanning text from images. Simply upload an image, and the web app will promptly provide you with the extracted texts.

## Home page

![App Screenshot](https://github.com/CodeWizardl/Django-Extract-OCR/assets/142290678/6969d299-4ad4-49e0-afee-00ee493b27b6)

## Result page

![App Screenshot](https://github.com/CodeWizardl/Django-Extract-OCR/assets/142290678/bb07a212-7644-4dda-b6d6-7581c51c9a94)

Currently, our OCR project supports the following commonly used languages:
- English
- Nepali
- Hindi

We welcome feature requests for additional languages! Feel free to suggest the languages you'd like to see included.

## Installation

```bash
  git clone https://github.com/ASACHIT/OCR-django-app.git
  cd OCR-django-app
  pip install -r requirements
  python manage.py runserver 
  # open localhost:8000  url in browser 
```
Note: You have to install [tesseract module](https://github.com/UB-Mannheim/tesseract/wiki) too

## Frameworks/lib used
- Tailwindcss
- Django
- pytesseract

## Things i learnt after creating this project

- Taking image input from user 
- Processing input image without saving it anywhere and uploading it directly to user
- scanning text from image (backend)
- and other many more


## Features
- Rapidly upload images and receive scanned text instantly.
- Images are not stored; they are processed in-memory and sent directly to our service.
- Enjoy a user-friendly and clean UI for a seamless experience.

## Conclusion
- In conclusion, our Django web application simplifies the process of extracting text from images. With just a straightforward image upload, users can effortlessly obtain the text content detected within the image. The entire process is user-friendly, eliminating the need for intricate steps. Experience the convenience of our web app, where image scanning for text retrieval is made quick and hassle-free.

