# QR Code Generator CLI

A simple Node.js command-line tool that generates a QR code image from a user-provided URL and saves it locally.

---

## 🚀 Features

* Accepts user input via terminal
* Generates a QR code image (PNG format)
* Saves the entered URL into a text file
* Lightweight and easy to use

---

## 🛠️ Tech Stack

* Node.js
* inquirer (for user input)
* qr-image (for QR code generation)
* fs (file system module)

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/ayushiisaiinii/qr-code-cli.git
cd qr-code-cli
```

Install dependencies:

```bash
npm install
```

---

## ▶️ Usage

Run the application:

```bash
node index.js
```

Enter a URL when prompted.

---

## 📁 Output

* `qr_img.png` → Generated QR code image
* `URL.txt` → Stores the entered URL

---

## 💡 Example

Input:

```
https://example.com
```

Output:

* QR code image saved in project folder
* URL stored in a text file

---

## 🔮 Future Improvements

* Add URL validation
* Allow custom file names
* Support multiple formats (SVG, JPEG)
* Convert into a proper CLI tool with arguments

---

## 👩‍💻 Author

Ayushi

---

## 📌 Notes

This project was built as part of a Node.js learning exercise to understand NPM packages and working with external modules.
