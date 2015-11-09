# Parichit ( परिचित ) #
**Parichit ( परिचित )** is an attempt to create best open source OCRs for Indian and South Asian languages. The project is based on **Tesseract OCR** Engine ( http://code.google.com/p/tesseract-ocr/ ) . The front end will be a modified version of **VietOCR** ( http://vietocr.sourceforge.net/ )

The project aims to create high quality training data for creating tesseract language models for each of the Indian languages.


## Shirorekha ##

Devanagari, Bengali and Gurmukhi scripts are written in a way where each word is marked by a line above it called as **Shirorekha**. This connects all the letters in a word and so segmetation had to be done before the scanned is passed on to the recognizer.

A Shirorekha segmenter will be made available on this project soon.

## Character Reordering ##

Almost all Indic scripts need character reordering to reorganise from visual order to logical (Unicode) order. Since Tesseract OCR operates strictly from left to right the characters are scanned in visual order and recognition also happens in visual order. This needs to be reordered in post processing. Code for such reordering for each language will be made available soon.