# 📊 CryptoPortfolio

**Modular Python Project – Incremental Development (v0 / v1 / v2 / v3)**

## 1. Introduction

**CryptoPortfolio** is a cryptocurrency portfolio management and analysis application.
The project was developed as part of a **Python programming and software engineering course**, with the objective of designing and implementing a **non-trivial application**, with a strong focus on problem analysis, software design, modularity, and code quality.

The project follows an **incremental development approach**, structured into several successive versions (**v0, v1, v2, v3**). Each version is executable and illustrates the progressive evolution of the application.

---

## 2. Problem Statement and Objectives

Managing a cryptocurrency portfolio involves:

* tracking held assets,
* accessing market data,
* analyzing portfolio value and allocation.

The main objectives of the project are:

* Model the problem of cryptocurrency portfolio management
* Design a **clear, modular, and scalable** software architecture
* Implement a **Python** application following best practices
* Apply an **incremental development process** (V0 → V1 → V2 → V3)
* Deliver a functional and well-documented application

---

## 3. Technical Constraints

The project complies with the constraints defined in the assignment:

* Application developed primarily in **Python**
* Code organized across **multiple files and modules**
* Adherence to best practices:

  * PEP 8 conventions
  * docstrings for public classes and functions
  * explanatory comments
* Use of appropriate tools depending on the version:

  * command-line interface (CLI)
  * data persistence
  * external API calls
  * web interface in the final version

---

## 4. Project Structure

```text
portfolio-dsba/
├── v0/
├── v1/
├── v2/
├── v3/
├── src/
├── README.md
├── REPORT.md
├── portfolio.json
├── package.json
└── requirements.txt
```

* `v0/`, `v1/`, `v2/`, `v3/`: successive and executable versions of the project
* `src/`: main source code
* `portfolio.json`: portfolio data
* `REPORT.md`: detailed project report

---

## 5. Incremental Development

### 🔹 Version v0 – MVP

* Project skeleton setup
* Modeling of core entities (portfolio, assets)
* Minimal management functionalities
* First executable version

### 🔹 Version v1 – Functional Extensions

* Addition of new features
* Improved modular structure
* More advanced data management
* Extended command-line interface

### 🔹 Version v2 – Robustness and Enrichment

* Improved business logic
* Error handling
* Introduction of analytical features
* Preparation for external service integration

### 🔹 Version v3 – Final Version

* Integration of market data via external APIs
* Addition of a web interface for visualization
* Improved user experience
* Most complete and robust version of the project

Each version **builds upon the previous one**, without requiring a complete rewrite of the codebase.

---

## 6. Technologies Used

* **Python**: business logic and portfolio management
* **JavaScript / React**: web interface (final version)
* **External APIs**: market data retrieval
* **Tools and libraries**:

  * argparse (CLI)
  * JSON (data persistence)
  * ESLint, frontend build tools

---

## 7. Installation

### Prerequisites

* **Python 3.9 or higher**
* **Node.js** (for the web interface in v3)

### Python dependencies

```bash
pip install -r requirements.txt
```

### Frontend dependencies (v3)

```bash
npm install
```

---

## 8. Execution

Each version can be run independently.

### Example (final version):

```bash
cd v3
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

This file is used for data persistence and asset analysis.

---

## 10. Report

A detailed report is provided in:

```text
REPORT.md
```

It covers:

* context and problem definition
* informal specifications
* development plan
* software architecture
* evaluation of project versions
* limitations and improvement perspectives

In accordance with the guidelines, the report does not include full code listings and refers to docstrings where necessary.

---

## 11. Authors

Project developed by a **group of 3 students**,
as part of a **Python programming / software engineering** course.

---

## 12. Conclusion

This project illustrates a complete software development workflow:

* problem analysis,
* modular design,
* incremental implementation,
* documentation and critical reflection.

It highlights the importance of structure, readability, and scalability in a medium-sized Python project.

