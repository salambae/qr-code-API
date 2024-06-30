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
For an example, you want get the qr code of ```https://github.com/salambae``` url, change the parameters you want and paste this code to your browser
```
https://salambae.pythonanywhere.com/api/v1/qr-code-generator?url=https://github.com/salambae&size=#SIZE_OF_QRCODE&border=#BORDER_THICKNESS&background=#BG_COLOR&ver=#SIZE_OF_QR
```
# References
1. https://pypi.org/project/qrcode/
2. pythonanywhere.com
