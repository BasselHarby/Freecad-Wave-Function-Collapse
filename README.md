
# FreeCAD Wave Function Collapse for School Layouts

![Demo](https://github.com/BasselHarby/Freecad-Wave-Function-Collapse/blob/main/docs/demo.gif)

A FreeCAD macro that applies the **Wave Function Collapse (WFC)** algorithm to generate and iterate different design alternatives for a school layout.  
This project demonstrates how generative design principles can be integrated into FreeCAD for architectural and construction applications.

---

## 📂 Repository Structure

```

freecad-wfc-school-layout/
│
├─ /docs/
│   └─ demo.mp4               # Video showing the algorithm in action
│
├─ /examples/
│   └─ WFCMaintest.FCStd       # Example FreeCAD project file
│
├─ WFCV0.1.FCMacro             # FreeCAD macro (Wave Function Collapse)
│
├─ README.md                   # Project description and usage instructions
└─ LICENSE                     # License file

````

---

## ✨ Features

- Implements the **Wave Function Collapse** algorithm in FreeCAD.  
- Automatically generates multiple feasible school layout alternatives.  
- Works directly with FreeCAD `.FCStd` files.  
- Easy to extend for other design generation tasks.

---

## 🚀 Installation

1. Clone this repository:
   git clone https://github.com/yourusername/freecad-wfc-school-layout.git

2. Copy the macro file `WFCV0.1.FCMacro` into your FreeCAD **Macros** directory:

   * On Windows: `C:\Users\<YourUser>\AppData\Roaming\FreeCAD\Macro`
   * On Linux: `~/.FreeCAD/Macro`
   * On macOS: `~/Library/Preferences/FreeCAD/Macro`

3. Open FreeCAD and ensure the macro appears under **Macro → Macros…**

---

## 🛠 Usage

1. Open the example FreeCAD file:

   ```
   examples/WFCMaintest.FCStd
   ```

2. Run the macro `WFCV0.1.FCMacro` from FreeCAD.
   *(You can run it via `Macro → Macros…` and selecting it from the list.)*

3. The algorithm will iterate through layout configurations and generate alternatives.

---

## 📦 Dependencies

* **FreeCAD 0.21** or later
* **Python 3.x** (built into FreeCAD)
* No external libraries required

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).
You are free to use, modify, and distribute it with attribution.

---

## 🤝 Contributing

Contributions are welcome!
* Fork the repo and submit pull requests for improvements.

---

## 🧑‍💻 Author

Developed by Bassel Harby
Feel free to reach out for collaborations or suggestions!

