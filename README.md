# DNA Data Storage: Image Encoding & Decoding

## Overview
This project explores a **computational approach** to representing digital images as DNA sequences, inspired by the futuristic concept of **DNA-based data storage**. Using **Streamlit** and the **PIL (Pillow) Python package**, this app allows users to convert images into **binary representations**, encode them into **DNA sequences (A, T, G, C)**, and decode them back.

## How It Works
1. **Image to Binary Conversion**  
   - Converts an uploaded image to **grayscale**.  
   - Applies **binary thresholding** (0 or 1 based on pixel intensity).  
   - Saves the binary representation in a text file.  

2. **Binary to DNA Encoding**  
   - Translates **binary pairs into DNA bases** using the mapping:  
     - `00 → A`  
     - `01 → T`  
     - `10 → G`  
     - `11 → C`  
   - The DNA sequence can be **synthesized and stored in a vector**, making it physically storable as DNA.  

3. **DNA to Binary Decoding**  
   - Reads the DNA sequence and converts it back to binary using the reverse mapping.  

4. **Binary to Image Reconstruction**  
   - Restores the grayscale image from the binary representation.  

## Applications
- **DNA Data Storage**: A step toward encoding **digital data into synthetic DNA**.  
- **Bioinformatics**: Demonstrates a hybrid approach combining **computing and biology**.  
- **Cryptography & Secure Storage**: DNA-based encoding could be used for **high-density, long-term data storage**.  

## Tech Stack
- **Python**  
- **Streamlit** (for the interactive web interface)  
- **PIL (Pillow)** (for image processing)  
- **NumPy** (for numerical operations)  

## 🚀 Coming Soon!  
The **complete code** will be released soon, featuring:  
✔ Enhanced UI/UX improvements  
✔ Optimized DNA encoding logic  
✔ Future integrations with **biological synthesis and sequencing**  

Stay tuned for updates!  
