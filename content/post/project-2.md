---
date: 2022-10-25
description: "A web application that extract text from the image of number plates."
featured_image: "/images/pexels-pixabay-533669.jpg"
title: "Project 1: Automatic Number Plate Detector using OCR"
---

* Created a web application that extracts license plate information as text from the image. 
* Labeled the images using pyqt's labelImg UI. And created a .csv file out of the annotations.
* Processed the labeled data ready for model training.
* Using InceptionResnet v2 model to train the dataset.
* Created a pipeline and used Tesseract for OCR (Optical Character Recognition). Tuned the OCR script and enhanced the data enough to increase the accuracy(~91%). 
* Created a client facing API using Flask

{{< figure src="/images/ocr.png" >}}

[Link to GitHub Repository](https://github.com/Thivas12/Automatic-Number-Plate-detector-using-OCR)
