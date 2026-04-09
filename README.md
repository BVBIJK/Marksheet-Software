# 📊 CBSE Marksheet Software

A powerful desktop application to **manage, analyze, and edit CBSE marksheet data** — designed for schools, teachers, and academic use.

This version is distributed as a **standalone executable**, so no programming or Python setup is required.

---

## 🚀 Getting Started

### 📦 This project uses a **one-folder executable build**

Make sure the following are present:

Marksheet_Software.exe
_internal/

---

### ▶️ How to Run

1. Download or clone this repository  
2. Ensure both files are in the **same folder**  
3. Double-click `Marksheet_Software.exe`  

> ⚠️ The `_internal` folder is required for the app to run.

---

## ⚠️ Important

- ❌ Running only the `.exe` will NOT work  
- ❌ Deleting or renaming `_internal` will break the app  
- ❌ Moving files separately will cause errors  

### Windows Warning
If Windows shows a warning:
- Click **More info → Run anyway**

This is normal for unsigned apps.

---

## ✨ Features

### 📥 Data Import
- Load CBSE gazette files  
- Automatically extracts:
  - Student details  
  - Subject marks  
  - Grades  

---

### 🗄️ Database System
- Uses SQLite for storage  
- Automatically creates year-wise databases:

data/results_YYYY.db

---

### 📊 Data Viewing & Filtering
- Interactive table interface  
- Sort and filter easily  
- Advanced filters:
  - Percentage range  
  - Top performers  
  - Subject-wise mark filtering  

---

### 🧑‍🎓 Student Editor
- View complete student details  
- Edit:
  - Name, gender, school  
  - Marks and grades  
- Auto recalculates totals and percentage  

---

### 📤 Export
- Export filtered data to CSV  

---

### 📚 Subject Code Manager
- Built-in CBSE subject codes  
- Add / edit / delete codes  
- Organized by class  

---

### 🎨 User Interface
- Modern dark theme  
- Fast custom table system  
- Smooth scrolling and sorting  

---

## 🧠 How It Works

1. Launch the application  
2. Load a CBSE gazette file  
3. Data is parsed and saved automatically  
4. Use the interface to:
   - View  
   - Filter  
   - Edit  
   - Export  

---

## ⚙️ Requirements

- Windows OS  
- No additional installations required  

---

## 📁 Project Structure

.
├── Marksheet_Software.exe
├── _internal/              # Required dependencies
├── data/                   # Auto-created database files
│   └── results_YYYY.db

---

## 📦 Recommended Download Method

Use the **Releases section**:
1. Download the ZIP file  
2. Extract it  
3. Run the `.exe`  

---

## 🛠️ Built With

- Python  
- CustomTkinter  
- SQLite  
- Matplotlib  

---

## 💡 Use Cases

- School result management  
- Academic performance analysis  
- Editing CBSE result data  
- Generating filtered reports  

---

## 🔮 Future Improvements

- PDF export  
- Graph-based analytics  
- Multi-user system  
- Cloud sync  

---

## 📄 License

Free to use for educational purposes.

---

## ⭐ Support

If you like this project, consider giving it a ⭐ on GitHub!
