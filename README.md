# 🔐 File Encryption & Decryption Web App

This project is a simple yet secure **File Encryption and Decryption Web Application** built using **Flask**. It enables users to upload files, encrypt them using a randomly generated key, and later decrypt them using that same key. The interface includes smooth animations and GIF backgrounds to enhance the user experience, making the tool both functional and visually appealing.

---

# 📄 Overview

The application includes the following key features:

- 📁 **File Upload** – Upload any type of file through a clean and intuitive UI.
- 🔐 **Encryption** – Encrypts the uploaded file with a secure, randomly generated 128-bit key.
- 🧾 **Key Display** – Shows the encryption key (in hex format) that must be saved for future decryption.
- 🔓 **Decryption** – Allows users to enter the key to decrypt and download the original file.
- 🎨 **Animated UI** – Features animated transitions and customizable GIF backgrounds.
- ✅ **Input Validation** – Ensures correct key formatting and displays errors if decryption fails.

---

This project is ideal for students, developers, or hobbyists interested in learning about basic cryptography and secure file handling using Python and Flask. It also serves as a solid foundation for expanding into more advanced file security applications.

# 🚀 Features & Characteristics

| Feature                  | Description                                                                 |
|--------------------------|-----------------------------------------------------------------------------|
| 📁 File Upload           | Allows users to upload any file format securely.                            |
| 🔐 File Encryption       | Encrypts files using a 128-bit AES-based encryption scheme.                 |
| 🧾 Key Generation        | Automatically generates a secure hex key for decryption.                    |
| 🔓 File Decryption       | Decrypts files using the exact key provided during encryption.              |
| 🧩 Input Validation      | Ensures the decryption key is correctly formatted (16 hex digits).          |
| 📥 File Download         | Lets users download encrypted or decrypted files after processing.          |
| 🎨 GIF Background        | Customizable animated GIF background for enhanced visual appeal.            |
| 💡 Animated Transitions | Smooth UI animations (jump-in, zoom, float) for a modern web experience.    |
| ⚙️ Flask Backend         | Lightweight and efficient backend using Python's Flask framework.           |
| 🛡️ Secure Key Handling   | Key is never stored on the server; user must save it securely.              |

# 📁Folder Structure
```
project-root/
├── decrypted/
├── encrypted/
├── templates/
│   ├── decrypt.html
│   ├── encrypt.html
│   ├── index.html
│   ├── options.html
├── uploads/
├── input.txt
└── sample.py
```
# 🚀 Installation

Follow these steps to set up and run the project locally:

## 1. Clone the repository
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

## 2. Create a virtual environment (optional but recommended)
```bash
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
```

## 3. Install required packages
```bash
pip install -r requirements.txt
```

> Make sure to create a `requirements.txt` file with the dependencies like Flask and any encryption-related libraries you're using.

## 4. Run the application
```bash
python sample.py
```

## 5. Open in browser
Visit `http://127.0.0.1:5000` in your web browser to start using the app.

# 📽️Output

🌐 Download Here: [@OUTPUT](https://github.com/DHIKSHAMP/File-Encryption/blob/main/FILE-ENCRYPTION.mp4)

# 🛠️ Tech Stack

| Category         | Technology           |
|------------------|----------------------|
| 💻 Programming   | Python               |
| 🌐 Web Framework | Flask                |
| 🔐 Encryption    | PyCryptodome (DES)   |
| 🎨 Frontend      | HTML, CSS            |
| 📁 Templates     | Jinja2 (via Flask)   |
| 📂 File Handling | OS module (Python)   |

# ✅ Use Case Scenarios

This application can be used in a variety of scenarios where secure file transmission and controlled access are critical.

## 🔐 1. Secure File Transmission
- Encrypt sensitive files before sending over email or cloud storage.
- Only recipients with the correct decryption key can access the original file content.

## 🧾 2. Confidential Document Handling
- Upload and decrypt classified or confidential files (e.g., business contracts, government documents).
- Prevent unauthorized access by using a 16-digit secret DES key.

## 🧪 3. Educational Demonstration
- Demonstrate symmetric encryption (DES) and padding mechanisms in cryptography classes or workshops.
- Understand how file encryption/decryption works using a real Python + Flask implementation.

# 👤 Author

**DHIKSHA M P**  

🌐 GitHub: [@DHIKSHAMP](https://github.com/DHIKSHAMP)

🔗 LinkedIn: [linkedin.com/in/dhikshamp](https://linkedin.com/in/dhiksha-m-p-095028257)

🌍 Portfolio: [Portfolio](https://sites.google.com/view/dhikshacyber/about)

## ⚖️ License

This project is licensed under the [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.en.html) – see the [LICENSE](./LICENSE) file for details.

## 🌟 Contributing

💡 Got suggestions or new ideas?  
🛠️ Pull Requests are welcome!  
📧 Contact me if you'd like to collaborate.
