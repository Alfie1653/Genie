# 🎓 TranscriptGenie

**TranscriptGenie** is a lightweight browser-based tool that allows institutions or administrators to generate academic transcripts from Excel files. Each student's transcript is formatted as a polished, printable PDF and all documents are downloaded together as a ZIP file.

**FEATURES**

- Upload an Excel file with sheets for:
  - `StudentDetails`
  - `Grades Sem 1`
  - `Grades Sem 2`
  - `CourseMapping`
- Automatically generates individual **academic transcript PDFs** for each student.
- Combines all transcripts into a single downloadable ZIP archive.
- Built-in **progress bar** (linear + circular) with real-time feedback.
- Handles missing data and errors with **inline warnings** (no pop-ups).
- Fully **responsive** and works offline (once loaded).
- Stylish PDF formatting with:
  - University logo
  - Student details
  - Semester-wise grades
  - Grading key
  - Recommendation & signature area

## EXCEL FILE FORMAT

To function correctly, your Excel workbook must contain these sheets:

1. **StudentDetails**
2. **Grades Sem 1**
3. **Grades Sem 2**
4. **CourseMapping**

Each sheet should have clearly labeled columns (e.g., `REGISTRATION NUMBER`, `COURSE`, `ADMISSION DATE`, etc.).

## 📦 HOW TO USE

1. Open the web app in your browser.
2. Click **"Choose Excel File"** and upload the `.xlsx` file.
3. Optionally, enter a custom ZIP file name.
4. Click **"Generate Transcripts"**.
5. Wait for the progress bar to complete.
6. Your ZIP file will be downloaded automatically!

## ⚙️ Built With

- [jsPDF](https://github.com/parallax/jsPDF) + [AutoTable plugin](https://github.com/simonbengtsson/jsPDF-AutoTable) — for PDF generation
- [SheetJS (xlsx)](https://sheetjs.com/) — for Excel file parsing
- [JSZip](https://stuk.github.io/jszip/) — to bundle PDFs into a ZIP file
- HTML, CSS, and JavaScript — no backend required

## 🧩 Live Demo

> Coming soon...

You can also [host it on GitHub Pages](https://pages.github.com/) or Netlify.

## 📜 DISCLAIMER
This tool is provided for informational and/or practical use only. While we strive to ensure its accuracy and reliability, use of this tool is at your own risk. Always verify critical results independently and consult a qualified professional when necessary.

## 📫 AUTHOR

Made with 💻 by**JOSAM KIMANI**  
📧 Email: joemarenye@gmail.com 
🌐 Website: [your-portfolio-or-link](https://example.com)

