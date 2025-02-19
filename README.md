# Secure Data Hiding in Images Using Steganography

##  Project Description  
This project implements **steganography**, a method of securely embedding sensitive data within images while keeping it imperceptible to unauthorized users. By leveraging techniques like **Least Significant Bit (LSB) substitution, Discrete Cosine Transform (DCT), and Discrete Wavelet Transform (DWT)**, the system ensures data confidentiality while preserving the visual integrity of the image. To enhance security, **AES or RSA encryption** can be applied before embedding the data.

##  Features  
✔ **Secure Data Embedding** – Hide text or files within images without noticeable distortion.  
 **Encryption Support** – Encrypt hidden data using **AES or RSA** before embedding.  
 **Robustness** – Resists **compression, resizing, and noise addition** while maintaining hidden data integrity.  
 **User-Friendly Interface** – Simple UI for embedding and extracting hidden data.  
 **Multi-Algorithm Support** – Choose between **LSB, DCT, and DWT** for different security levels.  

##  Technologies Used  
- **Programming Languages** – Python, Java  
- **Image Processing** – OpenCV, PIL (Python Imaging Library)  
- **Steganographic Techniques** – LSB, DCT, DWT  
- **Cryptography** – AES, RSA for encrypting hidden data  
- **GUI Development** – Tkinter (Python), JavaFX (Java), or Web-based (React.js, Flask/Django)  
- **Storage** – SQLite or File system  
- **Testing & Security** – StegExpose for steganalysis  

##  Installation & Usage  
### 🔹 Prerequisites  
Ensure you have the required dependencies installed:  
```bash
pip install opencv-python pillow cryptography
