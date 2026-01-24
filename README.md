# DataAnalysisTool

Project Structure

DataAnalysisTool/
├── main.py
├── data_analyzer.py
├── report_generator.py
│
├── ui/
│   ├── tkinter_ui.py
│   └── pyqt_ui.py
│
├── reports/
│   ├── report.html
│   └── style.css
│
├── sample_data/
│   └── sample.csv
│
├── requirements.txt
└── README.md

How to Run the Project

1️⃣ Clone the Repository

git clone https://github.com/23sindhuja/DataAnalysisTool.git

cd DataAnalysisTool

2️⃣ Install Required Libraries
pip install pandas numpy matplotlib PyQt5

Tkinter comes pre-installed with Python on Windows.

3️⃣ Run Tkinter Version
python main.py

4️⃣ Run Tkinter Version with chart representation

For this follow DataAnalysisTool_Charts.zip 

Update data_analyzer.py

Update ui/tkinter_ui.py

Then update upload_file() function in tkinter_ui.py 

5️⃣ Run PyQt5 Version
python ui/pyqt_ui.py


