# 🧮 Cico FX-420 PLUS – Java Swing Calculator

A simple **desktop calculator application** built using **Java Swing** (NetBeans GUI Builder).  
The calculator supports basic arithmetic operations — addition, subtraction, multiplication, and division — with a clean interface and interactive hover effects on buttons.

---

## 🚀 Features

✅ **Basic arithmetic operations** — `+`, `-`, `×`, `÷`  
✅ **Clear button** — resets all input fields and the result  
✅ **Input validation** — shows warning messages if inputs are missing  
✅ **Interactive UI** — buttons change color when hovered  
✅ **Custom title and design** — mimics a scientific calculator name (`Cico FX-420 PLUS`)

---

## 🖼️ Interface Overview

| Component | Description |
|------------|-------------|
| **Number 1 / Number 2** | Input fields for entering numbers |
| **Result** | Displays the output of the operation |
| **Buttons** | `+`, `-`, `×`, `÷`, and `⌫` (clear all fields) |
| **Hover Effect** | Buttons turn **orange** when the mouse hovers over them |

---

## 🧩 Technologies Used

- **Java SE**
- **Swing (javax.swing)**
- **NetBeans GUI Builder**

---
## How to run #1 method (no code no IDE, Built version)
**download and run Assignment_1.jar excutable file**

## ⚙️ How to Run #2 method

1. **Clone the repository**
   ```bash
   git clone https://github.com/Mohamed-MX/Cico-FX420-PLUS.git
   ```
2. **Open in NetBeans IDE**
   - Go to **File → Open Project**
   - Select the project folder you just cloned  

3. **Run the application**
   - Click the green “Run” ▶ button, or press **Shift + F6**

---

## 🗂️ Project Structure

```
Cico-FX420-PLUS/
│
├── src/
│   └── NewJFrame.java      # Main Calculator GUI file
│
├── README.md               # Project documentation
└── nbproject/              # NetBeans project configuration files
```

---

## 🧠 Code Highlights

- **Hover Animation Example:**
  ```java
  jButton1.addMouseListener(new java.awt.event.MouseAdapter() {
      public void mouseEntered(java.awt.event.MouseEvent evt) {
          jButton1.setBackground(java.awt.Color.ORANGE);
      }
      public void mouseExited(java.awt.event.MouseEvent evt) {
          jButton1.setBackground(javax.swing.UIManager.getColor("Button.background"));
      }
  });
  ```

- **Validation Example:**
  ```java
  if (x.getText().isEmpty() || y.getText().isEmpty()) {
      javax.swing.JOptionPane.showMessageDialog(this, "Please enter both numbers!", 
          "Warning", javax.swing.JOptionPane.WARNING_MESSAGE);
      return;
  }
  ```

---

## 👨‍💻 Author

**Mohamed MX**  
🎓 Computer Science Student – Mobile & Cloud Computing Major  
📍 Egypt  
🔗 [GitHub Profile](https://github.com/Mohamed-MX)

---

## 📜 License

This project is licensed under the **MIT License** — feel free to use, modify, and share it.
