# Counterfeit-Currency-Detection

## Project Description

Counterfeit currency is a burning question throughout the world. The counterfeiters are becoming harder to track down because of their rapid adoption of and adaptation with highly advanced technology. Detecting fake notes manually becomes tedious and untidy process hence there is need of automation techniques with which currency detection process can be efficiently done. The process of identification is done by extracting the features such as security thread and watermark of the numeral of the given Indian currency and comparing it with the extracted features of the original currency with the help of image processing techniques like Canny edge detection, Gaussian Blur. There are many ways used to detect forgeries however still very dependent on the presence of a machine and equipment that are sometimes less effective and need more time but with our proposed model we can detect the originality of our currency paper quickly with the help of a scanner or an image capturing device.

## Results

### Security Thread

In Security Thread: If the number of contours detected is less than equal to 1 then the currency is real. Else it is fake.

![Image of Real Note — Continuous strip detected](https://user-images.githubusercontent.com/88145926/214235768-830d8d40-5d2c-494a-ad03-65e616041d1d.png)

<p align="center"> Image of Real Note — Continuous strip detected </p>

![Image of Fake Note — Segments of strip detected](https://user-images.githubusercontent.com/88145926/214235809-04a50a77-4645-41a6-ae0c-56e4e9313179.png)

<p align="center"> Image of Fake Note — Segments of strip detected </p>

### Watermark of Numeral

In Watermark of Numeral: If the output detected using OCR is the same as that of the currency then it is real. Otherwise, it is fake.

![Image of Real Note — Numeral detected](https://user-images.githubusercontent.com/88145926/214235845-04490b56-288f-4e59-b015-aff5f449563d.png)

<p align="center"> Image of Real Note — Numeral detected </p>

![Image of Fake Note — Numeral not detected](https://user-images.githubusercontent.com/88145926/214235870-e9fedd4f-3341-43be-b9d2-f432ed9931f3.png)

<p align="center"> Image of Fake Note — Numeral not detected </p>

## Conclusion

Currency use is a necessity for survival and hence it is always necessary to keep in track of its originality. Paper currencies are used much more in India and hence a system to detect the fake currency is needed. As the new currencies are used in the market, the proposed system seems to be useful to detect the currency to be genuine or not. It also shows where the differences are in the currencies instead of simply displaying the result. This system can be further implemented for foreign currencies like Dollars, Euros, Taka, etc. as a future scope. Finally, we compared Real and Fake images we find weather the currency is original or duplicate.
