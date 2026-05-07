# MEP Progress Tracker

Portable browser-based MEP progress monitoring tool.

This tool is designed for simple floor-wise and system-wise MEP progress tracking without requiring Primavera, P6, schedules, databases, Python, .NET, or installation.

## Features

- Floor-wise MEP progress tracking
- System and sub-system selection
- Planned % and Actual % input
- Automatic variance calculation
- Automatic status detection:
  - Completed
  - Delayed
  - In Progress
  - Not Started
- Sample floor data generation
- Save/load project data as JSON
- Export CSV
- Export Excel-compatible `.xls`
- Works in Microsoft Edge, Google Chrome, or any modern browser

## How to Run

1. Download or clone this repository.
2. Open `MEP_Progress_Tracker_Portable.html` in a browser.
3. Start entering MEP progress data.

No installation is required.

## Files

| File | Description |
|---|---|
| `MEP_Progress_Tracker_Portable.html` | Main portable application |
| `QUICK_START.txt` | Short usage guide |
| `USER_MANUAL.txt` | Full English user manual |
| `README_RUN_FIRST.txt` | Basic launch instructions |

## Export Options

The tool can export:

- CSV file for Excel, Power BI, or further analysis
- Excel-compatible `.xls` report with:
  - Main progress table
  - Summary section
  - Delay register

> Note: The `.xls` export is an Excel-compatible HTML file. Microsoft Excel may show a warning that the file format and extension do not match. Click **Yes/Open** to continue.

## Typical Use Case

This tool can be used by:

- Site engineers
- MEP coordinators
- Planning engineers
- Project control engineers
- MEP contractors
- Project managers

## Limitations

This is a standalone progress monitoring tool. It does not include:

- Primavera P6 integration
- Schedule logic
- Baseline comparison
- Critical path analysis
- Database storage
- Multi-user cloud access

## License

Internal / demonstration use. Update this section if you want to publish it under a formal open-source license.
