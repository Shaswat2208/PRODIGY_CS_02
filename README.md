
```markdown
# Pixel Manipulation for Image Encryption

This Python script provides a simple image encryption tool that utilizes pixel manipulation techniques. It allows users to encrypt and decrypt images using a fixed XOR operation and also provides functionality to swap pixels in an image and restore them back.

## Features

- **Encryption and Decryption**: Encrypt images by applying a fixed XOR value to each pixel, and decrypt them using the same operation.
- **Pixel Swapping**: Swap pairs of pixels horizontally in an image.
- **Restore Swapped Pixels**: Reverse the pixel swapping process to restore the image to its original state.

## Requirements

- Python 3.x
- Libraries: PIL (Python Imaging Library), numpy

## Usage

1. **Encrypt Image**: Encrypts an input image using a fixed XOR value.

   ```bash
   python image_encryption.py
   Enter your choice (1/2/3/4): 1
   Enter the path of the image to encrypt: input_image.png
   Enter the path to save the encrypted image: encrypted_image.png
   ```

2. **Decrypt Image**: Decrypts an encrypted image using the same fixed XOR value.

   ```bash
   python image_encryption.py
   Enter your choice (1/2/3/4): 2
   Enter the path of the encrypted image: encrypted_image.png
   Enter the path to save the decrypted image: decrypted_image.png
   ```

3. **Swap Pixels**: Swaps pairs of pixels horizontally in an image.

   ```bash
   python image_encryption.py
   Enter your choice (1/2/3/4): 3
   Enter the path of the image to swap pixels: input_image.png
   Enter the path to save the image with swapped pixels: swapped_image.png
   ```

4. **Restore Swapped Pixels**: Reverses the pixel swapping process to restore the image.

   ```bash
   python image_encryption.py
   Enter your choice (1/2/3/4): 4
   Enter the path of the image with swapped pixels: swapped_image.png
   Enter the path to save the restored image: restored_image.png
   ```

## Notes

- Ensure you have the necessary permissions and adhere to ethical considerations when working with encryption and keyloggers.
- Always validate the paths and extensions when providing input and output file paths.

## Acknowledgements

This project was created as part of the internship program at Prodigy InfoTech.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
```

Feel free to customize the file further based on specific details or additional instructions relevant to your project or organization.# PRODIGY_CS_02
