# CrAcK-tools
# 📂 File Detector & PDF Tools (Client-Side Web App)

A fully browser-based utility that can:

* Detect file types using **binary signatures (magic bytes)**
* Process PDF files locally (merge, split, protect)
* Run entirely **on-device — no uploads, no servers**

---

## 🚀 Live Demo

👉 https://aj026.github.io/CrAcK-tools


---

## ✨ Features

### 🔍 File Type Detection

* Identifies files using **magic byte analysis**
* Works even if file extensions are incorrect
* Supports:

  * Images (PNG, JPG, etc.)
  * Documents (PDF, DOCX, etc.)
  * Archives (ZIP, etc.)
  * Text & binary formats

---

### 📄 PDF Master Suite

Built using `pdf-lib` (client-side)

* Merge multiple PDFs
* Extract specific pages
* Password-protect documents

---

### 🔒 100% Privacy Focused

* No file uploads
* No backend server
* All processing happens in your browser

---

### ⚡ Instant Processing

* Uses local CPU
* No waiting for uploads/downloads

---

## 🛠️ Tech Stack

* HTML5
* CSS3
* Vanilla JavaScript
* [pdf-lib](https://github.com/Hopding/pdf-lib)

---

## 📦 How It Works

1. File is loaded into memory using `FileReader`
2. First bytes are analyzed (magic numbers)
3. Type is inferred from known signatures
4. PDF operations use in-browser byte manipulation

---

## ⚠️ Limitations

* Works best on modern browsers (Chrome, Edge)
* Large PDFs may consume more memory
* Detection depends on available signature database

---

## 📁 Project Structure

```
index.html   → Main app (UI + logic)
```

---

## 🚀 Getting Started (Local)

Just open:

```
index.html
```

in your browser — no setup required.

---

## 💡 Future Improvements

* Add more file signatures
* Drag-and-drop batch PDF operations
* UI improvements and dark mode
* Export detection reports

---

## 📄 License

MIT License — free to use and modify.

---

## 👤 Author

Built using AI-assisted development (Gemini + custom logic).
