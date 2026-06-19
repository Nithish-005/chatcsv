# 📊 Chat CSV Data Analyzer

## AI-Powered Conversational Data Analysis & Visualization Platform

Chat CSV Data Analyzer is an intelligent Streamlit-based analytics platform that enables users to upload CSV datasets and interact with their data using natural language.

Instead of writing SQL queries, Python scripts, or manually building charts, users can simply ask questions about their data and instantly receive visualizations, insights, statistical summaries, and downloadable reports.

---

## 🚀 Key Features

### 🤖 Conversational Data Analysis

* Chat with your CSV files using natural language
* Ask questions about trends, patterns, and distributions
* Interactive chat-based user experience
* No coding required

### 📈 Automated Data Visualization

Generate charts automatically from user prompts:

* Scatter Plots
* Correlation Heatmaps
* Distribution Charts
* Box Plots
* Histograms
* Bar Charts
* Line Charts
* Pie Charts

### 📊 Interactive Analytics

* Plotly-powered visualizations
* Interactive zoom and filtering
* HTML chart exports
* Dynamic chart generation

### 📄 Professional Reporting

* PDF report generation
* Dataset summaries
* Visualization exports
* Downloadable analytics reports

### 🧠 Smart Column Detection

* Fuzzy column matching
* Natural language prompt interpretation
* Automatic chart selection
* User-friendly query processing

---

## 🏗️ System Architecture

```text
┌─────────────────────┐
│     User Uploads    │
│       CSV File      │
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│ Streamlit Frontend  │
│ Chat-Based UI       │
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│ Data Processing     │
│ Pandas & NumPy      │
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│ Analysis Engine     │
│ Query Interpretation│
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│ Visualization Layer │
│ Plotly • Seaborn    │
│ Matplotlib          │
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│ Reports & Exports   │
│ PDF • HTML Charts   │
└─────────────────────┘
```

---

## ✨ Main Applications

### Advanced Data Analyzer

Interactive chat-driven analytics platform that:

* Accepts CSV datasets
* Understands user queries
* Generates visualizations automatically
* Maintains conversation history
* Produces downloadable reports

### Smart Graph Generator

Prompt-driven chart generator where users can simply type:

```text
Show a bar chart of Sales by Region
```

or

```text
Create a scatter plot of Revenue vs Profit
```

and receive the corresponding visualization instantly.

---

## 📂 Project Structure

```text
Chat-CSV-Data-Analyzer/
│
├── app.5.py
│   ├── Advanced Data Analyzer
│   ├── Chat Interface
│   ├── Visualization Engine
│   └── PDF Reporting
│
├── app3.py
│   ├── Smart Graph Generator
│   ├── Prompt Parsing
│   └── Chart Rendering
│
├── run_app.py
│
├── .streamlit/
│   └── secrets.toml
│
├── .venv/
│
└── README.md
```

---

## 📊 Supported Visualizations

| Visualization       | Description                                      |
| ------------------- | ------------------------------------------------ |
| Correlation Heatmap | Relationship analysis between numerical features |
| Scatter Plot        | Variable comparison                              |
| Distribution Plot   | Data distribution analysis                       |
| Histogram           | Frequency analysis                               |
| Box Plot            | Outlier detection                                |
| Bar Chart           | Category comparison                              |
| Line Chart          | Trend visualization                              |
| Pie Chart           | Proportion analysis                              |

---

## 🛠️ Technology Stack

### Frontend

* Streamlit

### Data Processing

* Pandas
* NumPy

### Visualization

* Plotly
* Matplotlib
* Seaborn

### Machine Learning Utilities

* Scikit-Learn

### Reporting

* ReportLab

### Python Version

* Python 3.10+

---

## 🚀 Installation

### Clone Repository

```bash
git clone https://github.com/your-username/chat-csv-data-analyzer.git

cd chat-csv-data-analyzer
```

### Create Virtual Environment

```bash
python -m venv .venv
```

### Activate Environment

#### Windows

```powershell
.\.venv\Scripts\Activate.ps1
```

#### Linux / macOS

```bash
source .venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Application

### Advanced Analyzer

```bash
streamlit run app.5.py
```

### Smart Graph Generator

```bash
streamlit run app3.py
```

Application URL:

```text
http://localhost:8501
```

---

## 📋 Example Workflow

### Step 1

Upload CSV file

```text
sales_data.csv
```

### Step 2

Ask a question

```text
Show correlation between sales and profit
```

### Step 3

System automatically:

* Analyzes dataset
* Detects relevant columns
* Generates visualization
* Displays insights

### Step 4

Download:

* Interactive charts
* HTML exports
* PDF reports

---

## 🎯 Example Queries

### Data Exploration

```text
Show summary statistics
```

```text
Which columns have the strongest correlation?
```

### Visualization Requests

```text
Create a scatter plot of Revenue vs Profit
```

```text
Generate a heatmap for all numeric columns
```

```text
Show the distribution of sales values
```

---

## 🔒 Security & Reliability

* Local CSV processing
* No external database required
* Session-based state management
* Interactive chart export support
* Error handling for invalid datasets

---

## 💡 Business Use Cases

### Data Analysts

* Quick exploratory data analysis
* Automated chart generation
* Interactive reporting

### Students

* Data science learning
* Visualization practice
* Statistics exploration

### Business Teams

* Sales analysis
* Customer analytics
* Financial reporting

### Researchers

* Dataset exploration
* Pattern discovery
* Statistical visualization

---

## 🔮 Future Enhancements

* AI-powered insight generation
* SQL query generation
* Machine learning predictions
* Automated anomaly detection
* Multi-file analysis
* Dashboard export
* Cloud deployment support
* LLM integration (OpenAI / Groq / Gemini)

---

## 📜 License

MIT License

---

## 👨‍💻 Project Vision

Chat CSV Data Analyzer simplifies data exploration by combining conversational AI concepts with modern visualization tools, allowing anyone to transform raw CSV files into meaningful insights without writing code.

**Making Data Analysis Accessible Through Natural Language.**
