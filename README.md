# 📂 File & PDF Uploader

A lightweight, responsive web application that allows users to seamlessly upload, validate, and preview general files and PDF documents. 

---

## 🚀 Features

| Feature | Description |
| :--- | :--- |
| **Drag & Drop** | Supports both click-to-upload and drag-and-drop file areas. |
| **PDF Restrictions** | Enforces dedicated file size limits and extension filtering for PDF documents. |
| **Live Preview** | Embedded in-browser PDF viewer and preview system for standard images. |
| **Validation Engine** | Instant frontend validation for security, format restrictions, and sizing constraints. |

---

## 🛠️ Tech Stack

| Component | Technology |
| :--- | :--- |
| **Frontend** | HTML5, CSS3, JavaScript (ES6) |
| **Icons & UI** | FontAwesome / TailwindCSS (Optional) |
| **PDF Handling** | PDF.js (or native iframe embedding) |

---

## 📋 File Upload Specifications

| Metric | General Files | PDF Documents |
| :--- | :--- | :--- |
| **Max File Size** | 5 MB | 10 MB |
| **Allowed Formats** | `.png`, `.jpg`, `.jpeg`, `.txt` | `.pdf` |
| **Multi-upload** | Supported (up to 5 files) | Supported |

---

## 🔧 Installation & Local Setup

Follow these steps to run this project locally on your machine:

1. **Clone the repository:**
   ```bash
   git clone https://github.com
   ```

2. **Navigate into the project directory:**
   ```bash
   cd YOUR-REPO-NAME
   ```

3. **Launch the application:**
   * Open `index.html` directly in your browser, or
   * If using VS Code, right-click `index.html` and select **Open with Live Server**.

---

## 💻 Code Architecture Overview

* **`index.html`** - Contains the structured drag-and-drop landing interface.
* **`style.css`** - Manages the responsive design, active drop-zone animations, and layout grids.
* **`app.js`** - Controls file state logic, size checks, format restriction filters, and rendering.

---

## 🤝 Contributing

1. Fork the project.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.
