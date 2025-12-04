#  UIU Automation Underwater Robotics CREW  
## ROV Software Bootcamp — “UIU Mariner Program”

---

###  Overview

Welcome to the **UIU Automation Underwater Robotics CREW – ROV Software Bootcamp**, also known as the **UIU Mariner Program**.  
This 12-week training program builds your software, data, and robotics foundation — leading you from **Python basics** to **ROS 2-powered marine control systems**.  

By the end, you’ll be ready to design and program **autonomous underwater ROV systems** integrating **Python**, **PyQt**, **OpenCV**, and **ROS 2**.

---

## ⚙️ Core Technologies

-  Python 3  
-  ROS 2 (Robot Operating System 2)  
-  PyQt 5 / 6  
-  OpenCV    

---

##  Stage 1 — Core Programming & Software Skills (Weeks 1–12)

> Learn programming, data visualization, GUI development, and computer vision before diving into ROS.

---

### **Week 1–2: Python Basics**
**Objective:** Build a foundation in Python programming, logic, and version control.

**Tasks:**  
- [ ] Install Python and IDE (VS Code / PyCharm)  
- [ ] Set up Git & GitHub repository  
- [ ] Learn: Variables, data types, operators, conditionals, loops, input/output  
- [ ] Implement small practice programs  
- [ ] Upload code to GitHub  

---

### **Week 3–4: Data Skills**
**Objective:** Learn to handle, analyze, and visualize data.

**Tasks:**  
- [ ] Install NumPy, Pandas, Matplotlib, Seaborn  
- [ ] Load and clean CSV/Excel data  
- [ ] Perform filtering, grouping, and statistical summaries  
- [ ] Visualize data: bar charts, line plots, scatter plots, heatmaps, pairplots  
- [ ] Practice simple database CRUD operations (SQLite/MySQL)  
- [ ] Upload a **marine-themed mini data project** to GitHub  

---

### **Week 5–6: Object-Oriented Programming & GUI**
**Objective:** Learn OOP concepts and build GUIs with PyQt.

**Tasks:**  
- [ ] Learn: classes, objects, inheritance, encapsulation, polymorphism  
- [ ] Implement OOP-based examples (Student Manager, Bank Account System)  
- [ ] Learn PyQt basics — windows, buttons, event connections  
- [ ] Build a **Marine-Themed PyQt Mini Project**  
- [ ] Upload to GitHub  

---

### **Week 7–8: OpenCV Basics**
**Objective:** Learn the fundamentals of image and video processing.

**Tasks:**  
- [ ] Install OpenCV  
- [ ] Read, display, and save images/videos  
- [ ] Convert color spaces (BGR → Gray / HSV)  
- [ ] Apply resize, rotate, crop, and blur transformations  
- [ ] Draw shapes, text, and apply thresholding and masking  
- [ ] Upload a **marine-themed OpenCV project** to GitHub  

---

### **Week 9–10: Intermediate OpenCV**
**Objective:** Work with advanced image-processing techniques.

**Tasks:**  
- [ ] Implement edge detection (Canny)  
- [ ] Detect contours and recognize shapes  
- [ ] Apply histogram equalization and image enhancement  
- [ ] Use morphological operations (erosion, dilation)  
- [ ] Try background subtraction for object detection  
- [ ] Upload results and annotated outputs to GitHub  

---

### **Week 11–12: Object Detection & Marine Project**
**Objective:** Integrate object detection and GUI control.

**Tasks:**  
- [ ] Learn object detection frameworks: YOLO, SSD, Faster R-CNN  
- [ ] Set up YOLOv8 (or later) pre-trained model  
- [ ] Load marine datasets (fish, boats, coral, divers)  
- [ ] Visualize bounding boxes and labels  
- [ ] Build a **PyQt-based Marine Detection Dashboard** with:  
  - Real-time camera feed  
  - Object detection and measurement  
  - GUI-based control and display  
- [ ] Document and upload the final project to GitHub  

---

##  Stage 2 — ROV Software Integration with ROS 2

> Once your Python, GUI, and OpenCV foundations are strong, move on to real-time robotic control using ROS 2.

---

### **Challenge 1 — PyQt ROV Control GUI**
- Create a GUI to control ROV thrusters.  
- Include live camera feed display.  
- Tested in ROV simulation (ROS 2 environment).

---

### **Challenge 2 — Object Identification with OpenCV**
- Detect a red button in ROV’s camera feed.  
- Display annotated output on your GUI.  
- Tested in simulation.

---

### **Challenge 3 — Autonomous Navigation**
- Use ROS 2 to act on button-position data.  
- Implement an autonomous navigation algorithm toward the target.  
- Tested in the pool using the real ROV.  
- A reliable solution may be integrated into the official ROV control system.

---

##  Stage 3 — Environment Setup & Testing

**Follow these steps before starting the bootcamp:**

1. Create a GitHub account and install Git.  
2. Install VS Code and Python 3.12 or later.  
3. Clone the bootcamp repository.  
4. Create a virtual environment:
   ```bash
   python3 -m venv venv
5. Activate it:
   ```bash
   Windows CMD: venv\Scripts\activate.bat
   PowerShell: venv\Scripts\Activate.ps1
   Linux/MacOS: source venv/bin/activate
6. Install dependencies:
   ```bash
   pip install -r requirements.txt

