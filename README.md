# 🧪 PyTCG-Eval: Automated Python Test Case Generation and Evaluation System

## 👨‍💻 Developed By
### **Yashwanth Reddy Anugu**

🎓 Master’s Student in Computer Science at Rivier University  
💡 Interested in Software Engineering, Test Automation, Distributed Systems, and Intelligent Development Tools

---

# 📌 Project Overview

**PyTCG-Eval** is an advanced automated Python test case generation and evaluation system designed to simplify software testing and improve code quality through intelligent automation.

In many real-world software development environments, developers spend a large amount of time manually writing unit test cases. Even after spending significant effort, important edge cases and execution paths are often missed, which can lead to bugs and unreliable software behavior.

To solve this problem, I designed and developed PyTCG-Eval — a platform that automatically generates unit tests for Python programs, executes those tests, evaluates testing effectiveness, and provides detailed analytics through an interactive dashboard.

The system supports both local Python source files and GitHub repositories as input sources and integrates multiple open-source testing tools to generate and evaluate test cases automatically.

---

# ❗ Problem Statement

Traditional software testing processes face several major challenges:

- Writing test cases manually requires significant time and effort
- Developers may overlook important edge cases
- Measuring test quality accurately is difficult
- Coverage analysis tools are often disconnected from test generation tools
- Comparing effectiveness between multiple testing tools is not easy
- Small and medium projects lack centralized testing automation platforms

These challenges reduce testing efficiency and may result in unstable or poorly tested applications.

PyTCG-Eval solves these issues by providing a centralized automated testing and evaluation platform.

---

# 🎯 Project Objectives

The primary objective of this system is to reduce manual effort involved in software testing while improving overall software reliability and code quality.

The system helps developers:

✅ Automatically generate unit tests  
✅ Execute tests without manual setup  
✅ Measure testing effectiveness using coverage metrics  
✅ Compare multiple testing tools  
✅ Detect missing test coverage areas  
✅ Analyze testing quality visually through dashboards

---

# ✨ Core Features

# 📂 Source Code Input Management

The system allows users to provide Python programs through multiple sources.

### Supported Input Methods
- Upload local Python source files
- Submit GitHub repository links
- Select specific Python modules for testing

This flexibility makes the system suitable for both academic and real-world development projects.

---

# ⚙️ Automated Test Case Generation

PyTCG-Eval integrates multiple open-source testing tools to generate unit test cases automatically.

### Capabilities
- Generate test cases dynamically
- Create tests for functions and modules
- Detect edge cases
- Support structured unit testing workflows
- Reduce manual test-writing effort

The system focuses on improving development productivity through automation.

---

# ▶️ Automated Test Execution

After generating test cases, the platform automatically executes them.

### Features
- Automatic test execution pipeline
- Real-time execution tracking
- Failure detection and reporting
- Error logging and debugging support
- Execution monitoring dashboard

---

# 📊 Coverage Analysis & Evaluation

One of the main highlights of this project is the advanced evaluation engine.

The system analyzes testing effectiveness using multiple coverage metrics.

### Supported Metrics

## ✅ Line Coverage
Measures how many lines of source code are executed during testing.

## ✅ Branch Coverage
Measures how many logical branches and decision paths are tested.

## ✅ Mutation Coverage
Checks whether generated tests can detect intentional code modifications.

These metrics help developers understand the overall quality and reliability of their test suites.

---

# 📈 Visualization Dashboard

The application provides interactive dashboards for analyzing results.

### Dashboard Features
- Test execution statistics
- Coverage visualization
- Tool comparison charts
- Error reports
- Coverage trend analysis
- Module-level testing insights

The dashboard is designed to make analysis simple and understandable.

---

# 🔄 Multi-Tool Comparison

The system supports comparison between multiple test generation tools.

### Comparison Capabilities
- Compare line coverage
- Compare branch coverage
- Compare mutation scores
- Analyze tool effectiveness
- Identify best-performing testing strategies

This helps developers choose the most suitable testing tool for their projects.

---

# 📝 Logging & Reporting

The platform maintains structured logs and reports.

### Features
- Execution logs
- Error tracking
- Testing history
- Exportable reports
- Structured evaluation summaries

This improves transparency and debugging support.

---

# 🏗️ System Architecture

The project follows a modular and layered architecture design.

### 🔹 User Interface Layer
Handles user interaction through the Streamlit dashboard.

### 🔹 Input Processing Layer
Processes uploaded Python files and repository data.

### 🔹 Test Generation Layer
Generates unit tests using selected testing tools.

### 🔹 Test Execution Layer
Runs generated tests and captures outputs.

### 🔹 Coverage Analysis Layer
Calculates line, branch, and mutation coverage.

### 🔹 Reporting & Visualization Layer
Displays analytics, comparisons, and reports.

The modular architecture makes the system scalable and easy to extend.

---

# 🛠️ Technologies Used

## 💻 Programming Language
- Python

## 🌐 Frontend / UI
- Streamlit

## 📊 Data Handling & Analysis
- Pandas
- NumPy

## 📈 Visualization
- Plotly

## 🧪 Testing & Automation
- Open-source Python test generation tools

---

# 📂 Project Structure

```bash
PyTCG-Eval/
│
├── pytcg_eval.py
├── requirements.txt
├── reports/
├── logs/
└── sample_projects/
```

---

# ⚙️ Installation Guide

## Step 1 — Install Required Packages

```bash
pip install streamlit pandas numpy plotly
```

---

## Step 2 — Run the Application

```bash
streamlit run pytcg_eval.py
```

---

## Step 3 — Open in Browser

```bash
http://localhost:8501
```

---

# 🔄 System Workflow

## Step 1
User uploads Python files or provides a GitHub repository link.

## Step 2
User selects modules and testing tools.

## Step 3
System generates unit test cases automatically.

## Step 4
Generated tests are executed.

## Step 5
Coverage metrics are calculated.

## Step 6
Results are displayed in the analytics dashboard.

## Step 7
User compares testing tool performance and exports reports.

---

# 📊 Coverage Metrics Explained

## 🟢 Line Coverage
Shows how many lines of source code were executed.

## 🟡 Branch Coverage
Measures how many logical conditions and execution paths were tested.

## 🔴 Mutation Coverage
Evaluates how well tests detect code changes and injected faults.

These metrics help developers identify weak testing areas.

---

# 📈 Key Benefits

## ⚡ Reduces Manual Testing Effort
Automatically generates and executes unit tests.

## 🧪 Improves Testing Quality
Detects missing coverage and weak test cases.

## 📊 Provides Clear Insights
Interactive dashboards simplify coverage analysis.

## 🔍 Enhances Software Reliability
Helps developers build better-tested applications.

## 🚀 Supports Faster Development
Speeds up debugging and quality assurance workflows.

---

# 🌟 Key Highlights

✅ Automated Python test generation  
✅ GitHub repository support  
✅ Multi-tool comparison system  
✅ Advanced coverage analytics  
✅ Interactive dashboard visualization  
✅ Error logging and reporting  
✅ Easy-to-use Streamlit interface  
✅ Suitable for academic and real-world projects

---

# ⚠️ Current Limitations

- Designed mainly for Python projects
- Best suited for small and medium-scale applications
- Uses open-source testing tools only
- No cloud deployment integration currently
- Limited support for distributed execution

---

# 🔮 Future Improvements

## ☁️ Cloud Integration
Support AWS and Azure deployment.

## 🤖 AI-Based Test Generation
Integrate machine learning-based test generation models.

## 🔗 CI/CD Integration
Connect with GitHub Actions and Jenkins pipelines.

## 📡 Real-Time Collaboration
Support team-based testing workflows.

## 📊 Advanced Analytics
Add predictive testing quality analysis.

---

# 🧪 Testing & Validation

The system includes validation for:

- Source file handling
- Test generation workflows
- Coverage calculation
- Execution monitoring
- Error logging
- Dashboard visualization

---

# 🎯 Final Conclusion

The **PyTCG-Eval** system provides a complete and intelligent solution for automated Python test generation and evaluation.

By combining automated testing, execution pipelines, coverage analysis, visualization dashboards, and multi-tool comparison into a single platform, the system significantly reduces manual testing effort while improving software quality and reliability.

This project demonstrates practical implementation of software engineering principles, automation workflows, testing frameworks, analytics systems, and real-world development practices.

--- 
