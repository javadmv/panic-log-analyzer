# Panic Log Analyzer

**Panic Log Analyzer** is a desktop application built using PyQt5 that helps smartphone technicians and repair professionals analyze iPhone panic logs. It identifies known issues based on specific i2c and panic patterns and provides potential hardware-related solutions.

## 🚀 Features

- Paste or upload `.txt` or `.ips` panic log files.
- Select the iPhone processor series (A8, A9, A10, A11, A12).
- Automatically detects and analyzes i2c and general panic patterns.
- Suggests potential repair points (e.g., ICs, connectors, components).
- Allows users to add custom pattern-solution pairs in the current session.
- Dark-themed user interface for a professional look.

## 🛠️ Installation

1. Clone or download this repository:

```bash
git clone https://github.com/yourusername/panic-log-analyzer.git
cd panic-log-analyzer


2. Create and activate a virtual environment (optional but recommended):

python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate

3. Install the required packages:

pip install -r requirements.txt

4. Run the application:

python panic_log_analyzer.py

File Structure

panic-log-analyzer/
├── panic_log_analyzer.py       # Main PyQt5 application script
├── requirements.txt            # Dependencies
└── README.md                   # Documentation

📦 Requirements
Python 3.6+

PyQt5

✨ Example Use
Paste or upload an iPhone panic log.

Choose the processor series.

Click Analyze Log to see the suggested repair points.

📧 Author
Javadmv
Feel free to contribute or report issues!


---

### 📦 `requirements.txt`

```txt
PyQt5>=5.15.0
