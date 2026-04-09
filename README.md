📊 CBSE Marksheet Manager

A powerful desktop application to manage, analyze, and edit CBSE marksheet data — built for schools, teachers, and academic analysis.

This version is distributed as a standalone executable (no Python required).

🚀 Download & Run
📦 This project uses a one-folder executable build

The following files are required:

Marksheet_Software.exe
_internal/
▶️ Steps to Run
Download or clone this repository
Ensure both files are in the same folder
Double-click CBSE_Marksheet_Manager.exe

⚠️ The _internal folder is mandatory — do NOT delete or move it.

⚠️ Important Notes
❌ Running only the .exe will NOT work
❌ Renaming _internal will break the app
❌ Moving files separately will cause errors
⚠️ Windows Defender may show a warning:
Click "More info" → "Run anyway"
This is normal for unsigned executables
✨ Features
📥 Data Import
Load CBSE gazette files
Automatic extraction of:
Student details
Subject marks
Grades and results
🗄️ Database System
SQLite-based storage

Automatically creates year-wise databases:

data/results_YYYY.db
📊 Data Viewing & Filtering
Interactive table view
Sort and filter easily
Advanced filters:
Percentage range
Top-N students
Subject-wise mark filtering
🧑‍🎓 Student Detail Editor
View complete student profile
Edit:
Name, gender, school
Subject marks & grades
Auto recalculates:
Total marks
Percentage
📤 Export
Export filtered results to CSV
📚 Subject Code Manager
Built-in CBSE subject codes
Add / edit / delete codes
Class-wise organization
🎨 UI
Modern dark theme
Fast custom table (Canvas-based)
Smooth scrolling & sorting
🧠 How It Works
Open the app
Load a CBSE gazette file
Data is parsed and stored in SQLite
Use the UI to:
View
Filter
Edit
Export
⚙️ Requirements
Windows OS
No Python installation needed
📁 Project Structure
.
├── CBSE_Marksheet_Manager.exe
├── _internal/              # Required dependencies
├── data/                   # Auto-created database files
│   └── results_YYYY.db
📦 Recommended Way to Download

👉 Use the Releases section for best experience:

Download the ZIP file
Extract
Run the .exe
🛠️ Built With
Python
CustomTkinter
SQLite3
Matplotlib
💡 Use Cases
School result management
Academic performance analysis
Editing and cleaning CBSE data
Generating filtered reports
🔮 Future Improvements
PDF export
Graph dashboards
Multi-user system
Cloud sync
📄 License

Free to use for educational purposes.

⭐ Tip

If you like this project, consider starring ⭐ the repo!
