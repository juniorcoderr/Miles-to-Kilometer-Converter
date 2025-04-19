### 🛣️ Miles to Kilometer Converter using Python and Tkinter

This repository contains a beginner-friendly graphical user interface (GUI) application built using **Python** and the **Tkinter** library. The app provides a simple way to convert distances from **miles to kilometers** using a clean and intuitive interface.

---

### 📌 About the Project

This project is a basic example of how to build desktop applications in Python using **Tkinter**, Python’s standard GUI toolkit. It demonstrates how to:
- Create and configure a GUI window
- Use widgets like `Label`, `Button`, and `Entry`
- Organize layout using the **grid geometry manager**
- Handle events with **callback functions**
- Perform unit conversions using basic arithmetic

When the user enters a value in miles and clicks the "Calculate" button, the application converts the input to kilometers using the formula:

```
1 mile = 1.609 kilometers
```

The result is then displayed dynamically in the same window.

---

### 💻 Technologies Used

- **Python** – Programming language
- **Tkinter** – Python's built-in GUI library for desktop app development

---

### 🧠 Key Concepts Covered

- **Tkinter Basics:** How to initialize a window using `Tk()` and start the event loop with `mainloop()`.
- **Widgets in Tkinter:**
  - `Entry` for taking user input
  - `Label` for displaying text
  - `Button` to trigger an event (conversion)
- **Layout Management:** Using `grid()` to position widgets in a structured layout.
- **Event Handling:** Assigning functions to buttons using the `command` parameter.
- **Variable Handling:** Capturing and converting string input to float using `get()` and displaying output with `config()`.

---

### 🚀 How to Run

1. Clone this repository  
2. Make sure Python is installed on your system  
3. Run the script:
   ```bash
   python converter.py
   ```

The GUI window will open. Just enter the miles you want to convert, press the "Calculate" button, and see the result in kilometers instantly.

---

### 📚 Use Case

This is a great project for:
- Beginners exploring GUI development in Python
- Students practicing basic Python concepts
- Anyone who wants a simple desktop utility tool
