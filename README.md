# Steganography (Image-Based Text Encryption using OpenCV)

This project allows you to hide a secret message inside an image using pixel manipulation with OpenCV. It also provides an option to decrypt the hidden message using a passcode.

## Features
- ✅ Upload an image in Google Colab
- ✅ Hide a secret message inside the image
- ✅ Encrypt the message using pixel modification
- ✅ Decrypt the message with the correct passcode
- ✅ View the encrypted image

## How It Works
1. Upload an image – The user selects an image to encode the message.
2. Enter a secret message – The text message is hidden within the image pixels.
3. Provide a passcode – This passcode is required for decryption.
4. Encryption Process – The message characters are converted to pixel values and embedded into the image.
5. Decryption Process – The message is retrieved from the image pixels if the correct passcode is provided.

## Installation & Usage (Google Colab)
1. Clone the Repository
```
git clone https://github.com/yourusername/image-text-encryption.git
cd image-text-encryption
```
2. Open Google Colab and Run the Notebook
- Go to Google Colab
- Upload the Python script or copy the code into a new Colab notebook.
3. Install Dependencies (if needed)
```
pip install opencv-python numpy
```
4. Run the Script
- The script will prompt you to upload an image.
- Enter your secret message and passcode.
- The encrypted image will be displayed.
- To decrypt, enter the correct passcode when prompted.

## Example 
## Encryption Process
```
Enter secret message: HelloWorld
Enter a passcode: 1234
(Image is encrypted and saved as "encryptedImage.jpg")
```
## Decryption Process
```
Enter passcode for decryption: 1234
Decrypted message: HelloWorld
```

## Technologies Used
* Python – Programming Language
* OpenCV – Image Processing
* NumPy – Array Handling
* Google Colab – Cloud Execution


## Pull requests are welcome! If you’d like to contribute, please fork the repository and create a new branch for your feature or bug fix.
```
git checkout -b feature-name
git commit -m "Added new feature"
git push origin feature-name
```
Then, submit a Pull Request.

## License
This project is licensed under the MIT License. 
