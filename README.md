# 🖼️ PixelScrambler - Simple Image Encryption Tool

**PixelScrambler** is a beginner-friendly Python tool for encrypting and decrypting images using basic pixel manipulation. It uses XOR-based transformations to scramble the pixels, making the image unrecognizable — until decrypted with the correct key.

---

## 🔐 Features

- 🔁 Encrypt and decrypt images using a numeric key  
- 📷 Works with common image formats (JPG, PNG)  
- 🔄 Fully reversible using the same key  
- 🎓 Great for learning image processing and basic encryption  

---

## 🧠 How It Works

Each pixel's RGB values are XOR-ed with a user-defined key.  
Applying the same key again restores the original image.

---

## 📦 Requirements

- Python 3.x  
- Pillow (Python Imaging Library)

Install Pillow:

```bash
pip install pillow
```
# 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/PRODIGY_CS_02.git
```
# 2️⃣ Navigate to the project directory
```bash
cd PRODIGY_CS_02
```
# 3️⃣ Go into the folder containing the script
```bash
cd Pixel_Scrambler
```
# 4️⃣ Rename the script file (if needed)
```bash
mv Pixel_Scrambler Pixel_Scrambler.py
```
# 5️⃣ Run the encryption or decryption
```bash
python3 Pixel_Scrambler.py encrypt input.jpg encrypted.png --key 123
python3 Pixel_Scrambler.py decrypt encrypted.png output.jpg --key 123
```
