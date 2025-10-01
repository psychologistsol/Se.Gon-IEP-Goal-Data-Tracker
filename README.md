# Serjio's IEP Goals Tracker

A simple, offline-capable web application for tracking Individualized Education Program (IEP) goals and student progress.

## Features

- **Two Goal Tracking Systems**
  - Goal #1: Task Attention (focus duration and prompts needed)
  - Goal #2: Self-Regulation Strategies (task completion with coping strategies)

- **Progress Monitoring**
  - Automatic calculation of success rates
  - Visual indicators showing if goals are met (80% threshold)
  - Rolling 5-trial progress tracking

- **Data Management**
  - Add, edit, and delete trial entries
  - Export data to Excel-compatible CSV files
  - Show/hide goal sections for focused viewing

- **Offline Functionality**
  - Works completely offline once downloaded
  - No server or internet connection required
  - All data stored locally in browser memory during session

## How to Use

### Quick Start
1. Download `iep-tracker.html` from this repository
2. Double-click the file to open it in your web browser
3. Start tracking goals by clicking "Add Trial"

### Recording a Trial
1. Click the "Add Trial" button for the goal you want to track
2. Fill in the required information:
   - Date
   - Setting/context
   - Performance metrics
   - Success indicator (Yes/No)
   - Optional notes
3. The progress indicators will update automatically

### Exporting Data
1. Click the green "Export to Excel" button for either goal
2. A CSV file will download to your computer
3. Open the file in Excel, Google Sheets, or any spreadsheet program

## Technical Details

- **Built with:** HTML5, React 18, Tailwind CSS
- **Browser Compatibility:** Modern browsers (Chrome, Firefox, Safari, Edge)
- **No Installation Required:** Single HTML file with all dependencies via CDN
- **Privacy:** All data stays in your browser - nothing is sent to external servers

## Academic Year

Academic Year 2025-2026

## Goals Tracked

### Goal #1: Task Attention
**Target:** Attend to task for 10+ minutes with ≤2 prompts in 4/5 trials (80% accuracy)

**Tracked Metrics:**
- Date
- Setting (Advisory AM, Ethnic Studies, Visual Arts, English 10, Science, English 9)
- Group Size (Small 2-5, Large 6+)
- Task Duration (minutes)
- Number of Prompts
- Success (Yes/No)
- Notes

### Goal #2: Self-Regulation Strategies
**Target:** Use self-selected strategy to complete non-preferred tasks in 4/5 opportunities (80% accuracy)

**Tracked Metrics:**
- Date
- Non-Preferred Task
- Strategy Used (Timer, Break Card, Chunking Work, Asked for Help, Other)
- Stayed on Task (Yes/Partially/No)
- Completed (Yes/Partially/No)
- Success (Yes/No)
- Notes

## Screenshots

_The tracker features a clean, user-friendly interface with color-coded sections for each goal._

## License

This project is provided as-is for educational purposes.

## Support

For issues or questions, please open an issue in this repository.

## Customization

To customize for different students or goals, edit the HTML file:
- Change student name in line with `<h1>` tag
- Modify goal descriptions in the target sections
- Adjust dropdown options in the `<select>` elements
- Update academic year as needed

## Data Privacy Note

⚠️ **Important:** This tracker does not save data between sessions. All data is stored in browser memory only. To preserve your data:
1. Export to Excel regularly
2. Keep the CSV files in a secure location
3. Consider adding browser localStorage support for persistent storage (requires code modification)
