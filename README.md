# License_plate_recognition

Automatic Number Plate Recognition

The main idea is to Extract the letters from a number plate which can be used for many other purpose.

For extracting only license plate we used a pretrained Caffe model to localize the Numberplate from a image. And for Recogonizing we done it in three ways  one using Free API of pytesseract , another one is using CNN model for classification and another way is a help from another github repository where he used a KNN algorithm to recogonize the character. Among three pytesseract didn't give that much accurate results while cnn doesn't give it and the third one gives a good a result. In this repository code for the implement of Pytesseract only given.

