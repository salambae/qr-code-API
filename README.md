# QR Code API
### Base URL
```https://salambae.pythonanywhere.com/api/v1/qr-code-generator```
### Parameters
These are the inputs you send to the API to get the desired data
- ```url``` parameter for text or url.
- ```size``` parameter controls how many pixels each “box” of the QR code is.
- ```border``` parameter controls how many boxes thick the border should be.
- ```background``` parameter controls the background color.
- ```ver``` parameter is an integer from 1 to 40 that controls the size of the QR Code.
# Example Usage
### Example Requests
For example, if you want get the QR code of the ```https://github.com/salambae``` url, change the parameters you want and paste this url into your browser
```
https://salambae.pythonanywhere.com/api/v1/qr-code-generator?url=https://github.com/salambae&size=#SIZE_OF_QRCODE&border=#BORDER_THICKNESS&background=#BG_COLOR&ver=#SIZE_OF_QR
```
### Apply to the website
Source code (Javascript, HTML, CSS)
```
https://github.com/salambae/text-to-qrcode
```
Website appearance
```
https://salambae.github.io/text-to-qrcode/
```
Download format is .PNG
# References
1. https://pypi.org/project/qrcode/
2. https://pythonanywhere.com
