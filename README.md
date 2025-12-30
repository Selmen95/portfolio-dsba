# 📊 Portfolio DSBA

**Modular Python Project – Incremental Development (v0 / v1 / v2)**

## 1. Introduction

**Portfolio DSBA** is a cryptocurrency portfolio management and analysis application.
The project was developed as part of a **Python programming and software engineering course**, with the objective of designing and implementing a **non-trivial application**, emphasizing problem analysis, software design, modularity, and code quality.

The project follows an **incremental development approach**, structured into successive versions (**v0, v1, v2**). Each version is executable and demonstrates the progressive evolution of the application, with **v2 representing the final and most complete version**.

---

## 2. Problem Statement and Objectives

Managing a cryptocurrency portfolio involves:

* tracking owned assets,
* accessing real-time market data,
* analyzing portfolio value and asset allocation.

The main objectives of the project are:

* Model the problem of cryptocurrency portfolio management
* Design a **clear, modular, and scalable** software architecture
* Implement a **Python-based** application following best practices
* Apply an **incremental development process** (v0 → v1 → v2)
* Deliver a functional, robust, and well-documented application

---

## 3. Technical Constraints

The project complies with the technical constraints defined in the assignment:

* Application developed primarily in **Python**
* Code organized across **multiple files and modules**
* Compliance with best practices:

  * PEP 8 coding conventions
  * docstrings for public classes and functions
  * explanatory comments when necessary
* Progressive use of appropriate tools:

  * command-line interface (CLI)
  * data persistence
  * external API integration
  * web-based visualization in the final version

---

## 4. Project Structure

```text
portfolio-dsba/
├── v0/
├── v1/
├── v2/
├── src/
├── README.md
├── REPORT.md
├── portfolio.json
├── package.json
└── requirements.txt
```

* `v0/`, `v1/`, `v2/`: successive and executable versions of the project
* `src/`: main source code
* `portfolio.json`: portfolio data storage
* `REPORT.md`: detailed project report

---

## 5. Incremental Development

### 🔹 Version v0 – MVP

* Project skeleton and initial architecture
* Modeling of core entities (portfolio, assets)
* Basic portfolio management features
* First executable version

### 🔹 Version v1 – Functional Extensions

* Addition of new portfolio management features
* Improved modular organization
* Enhanced data handling
* Extended command-line interface

### 🔹 Version v2 – Final Version: Robustness and Enrichment

* Improved business logic and application robustness
* Comprehensive error handling and input validation
* Portfolio analysis features (total value, allocation, performance indicators)
* Integration of cryptocurrency market data via external APIs
* Data persistence and synchronization with market information
* Web interface for portfolio visualization
* Enhanced user experience
* Most complete and stable version of the project

Each version **builds upon the previous one**, without requiring a complete rewrite of the codebase.

---

## 6. Technologies Used

* **Python**: business logic and portfolio management
* **JavaScript / React**: web interface (final version)
* **External APIs**: cryptocurrency market data retrieval
* **Tools and libraries**:

  * argparse (CLI)
  * JSON (data persistence)
  * ESLint and frontend build tools

---

## 7. Installation

### Prerequisites

* **Python 3.9 or higher**
* **Node.js** (required for the web interface in v2)

### Python Dependencies

```bash
pip install -r requirements.txt
```

### Frontend Dependencies (v2)

```bash
npm install
```

---

## 8. Execution

Each version can be executed independently.

### Example (final version):

```bash
cd v2
python main.py
```

To launch the web interface:

```bash
npm run dev
```

---

## 9. Data

Portfolio data is stored in the following file:

```text
portfolio.json
```

This file is used for data persistence and portfolio analysis.

---

## 10. Report

A detailed report is available in:

```text
REPORT.md
```

It includes:

* project context and problem definition
* informal specifications
* development plan
* software architecture
* evaluation of project versions
* limitations and future improvement perspectives

In accordance with the assignment guidelines, the report does not include full code listings and refers to docstrings where appropriate.

---

## 11. Authors

Project developed by a **group of three students**,
as part of a **Python programming and software engineering** course.

---

## 12. Conclusion

This project demonstrates a complete software development lifecycle:

* problem analysis,
* modular software design,
* incremental implementation,
* documentation and critical evaluation.

It highlights the importance of code structure, readability, and scalability in a medium-sized Python application.
