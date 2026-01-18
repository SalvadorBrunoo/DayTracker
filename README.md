## 📅 2026 Dynamic Life Progress Tracker

A minimalist, vector-based **Life Progress Tracker** that automatically updates based on your system clock.

It's a copy from "https://www.weeklydots.com/" -> If this tool helps you get your life together, consider buying them a coffee to keep the inspiration flowing!!!

The main idea here is to create a high-quality, printable version of your year. While the digital version is cool, the real magic happens when you print it out and physically mark your progress.

No automation. No **smart** reminders. **Just you, a pen, and the cold, hard truth of a grid**. 
It’s designed to be a physical **shame-o-meter** to help you track exactly how many days you’ve skipped a task by lying to yourself and saying:
#### "I'll just do it tomorrow." 
Spoiler alert: Tomorrow is usually a very busy day.

## PREVIEW:

[Preview PDF file](https://github.com/SalvadorBrunoo/DayTracker/blob/main/Preview%20-%20Year%20Progress%20Tracker.pdf)

---

### ✨ Features

1.	**Real-time Progress:** Automatically fills squares based on the current day of the year.
2.	**Vector Fidelity:** Built entirely with SVG, ensuring perfect clarity at any zoom level or print size.
3.	**A4 Optimized:** Includes a dedicated **Print** button (bottom-right) that formats and centers the calendar perfectly on an A4 page for PDF export.
4.	**Weekday Alignment:** Mathematically accurate grid that accounts for the January 1st weekday offset (starts on a Thursday for 2026).
5.	**Visual Organization: 7+7 Layout:** Columns are split into two groups of seven for better scannability.
6.	**Month Shading:** Even-numbered (pair) months are shaded in a light gray to help distinguish time periods.
7.	**Agency FB Styling:** The year is styled with a modern, high-impact font, shifted 5px right for unique balance.

---

### 🚀 How to Use

This is a **zero-dependency** project. Everything is contained within a single HTML file.

1.  Clone the repository or download the `figure.html` file.
2.  Open the file in any modern web browser (Chrome, Firefox, Safari, Edge).
3.  To save as a PDF:
	Click the **Download PDF** button in the bottom-right corner.
	In the print dialog, select **Save as PDF** and ensure the paper size is set to **A4**.

---

### 🛠️ Customization

You can easily modify the following variables inside the `<script>` tag:

| Variable | Description |
| :--- | :--- |
| `squareSize` | Changes the dimensions of the dots. |
| `midGap` | Adjusts the spacing between the 7th and 8th column. |
| `isPairMonth` | Logic for the alternating month shading. |
| `yearDisplay` | Controlled by `now.getFullYear()` but can be hardcoded. |

---

### 📂 File Structure

```text
├── index.html   # Main application code (HTML/CSS/JS/SVG)
└── README.md    # You are here!
