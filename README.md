# Stegnography_Project

## Overview
This project implements **secure data hiding in images using steganography**. It enables users to embed confidential information within an image while ensuring minimal distortion and high security. The project uses techniques like **Least Significant Bit (LSB) embedding** along with optional encryption for enhanced security.

## Features
- **Data Hiding:** Conceal text messages or files within images.
- **Encryption Support:** AES encryption to enhance data security.
- **Image Processing:** Uses OpenCV and PIL for efficient manipulation.
- **Steganalysis Resistance:** Ensures low detectability.
- **GUI Interface (Optional):** User-friendly interface for ease of use.

## Technologies Used
- **Programming Language:** Python
- **Libraries:** OpenCV, PIL (Pillow), NumPy, PyCryptodome
- **Steganographic Techniques:** Least Significant Bit (LSB), DCT, and DWT (optional)

## Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/Deepamkochar/Stegnography_Project.git
   cd Stegnography_Project
   ```
2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the script:**
   ```bash
   python steganography.py
   ```

## Usage
- **Embedding Data:**
  - Select an image file.
  - Input the text or file to hide.
  - Encrypt (optional) and embed it within the image.
  - Save the stego-image.
- **Extracting Data:**
  - Load the stego-image.
  - Extract and decrypt (if applicable) the hidden data.

## Future Enhancements
- **AI-based Steganalysis Resistance**
- **Support for Audio and Video Steganography**
- **Cross-Platform Mobile Application**

## Contributing
Contributions are welcome! Feel free to fork the repository and submit pull requests.

## License
This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

## Contact
For queries or collaborations, reach out via [GitHub Issues](https://github.com/Deepamkochar/Stegnography_Project/issues).
