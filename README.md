
# 🔒 Secret

A simple repository containing pre-built executable files generated using **PyInstaller**.
No source code required — just clone and run.

---

## ⚙️ Build Process

The executable was created using:

```bash
pipx install pyinstaller
pyinstaller --onefile src.py
```

The compiled file is placed inside the `dist/` folder.

---

## 🚀 How to Run

Clone the repository:

```bash
git clone https://github.com/Sahil002620Q/secret.git
```

Navigate to the executable folder:

```bash
cd secret/dist
```

Run the executable:

```bash
./src
```

---

## 📁 Project Structure

```
secret/
│── dist/
│   └── src   # Executable file
│── src.py    # Original source (optional)
```

---

## ⚠️ Notes

* Ensure execution permission:

  ```bash
  chmod +x src
  ```
* Works on Linux/macOS
* For Windows, use `.exe` if available
* No Python installation required to run the executable

---

## 🧠 About

This project demonstrates how to convert Python scripts into standalone executables using PyInstaller for simple and fast distribution.
