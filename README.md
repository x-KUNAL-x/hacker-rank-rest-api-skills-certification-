# 🏆 HackerRank REST API Skills Certification

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![REST API](https://img.shields.io/badge/REST%20API-Programming-green)
![HackerRank](https://img.shields.io/badge/HackerRank-Skills%20Certification-2EC866?logo=hackerrank)

A collection of **Python 3 solutions** for HackerRank API and algorithm-based programming challenges, with a focus on working with **REST APIs, JSON data, HTTP requests, and problem-solving logic**.

## 📌 Project Overview

This repository demonstrates practical experience in:

* Consuming REST APIs
* Sending HTTP requests
* Processing JSON responses
* Extracting and filtering API data
* Working with API query parameters
* Implementing algorithmic solutions in Python
* Handling paginated API responses
* Solving real-world data-processing problems

---

# ⚽ REST API: Football Competition Winner's Goals

## 📝 Problem Description

In this challenge, a REST API provides information about football competitions and matches.

The API allows users to query:

* Competitions by **name and year**
* Matches by **competition and year**
* Match information including participating teams and goals

The objective is:

> Given a competition name and year, determine the team that won the competition and calculate the total number of goals scored by that team during the competition.

## 🎯 Example

### Competition

```text
UEFA Champions League
```

### Year

```text
2011
```

The competition data can be queried to determine the winning team.

The match data can then be retrieved to identify all matches played by the winning team and calculate the total goals scored.

For example, the winning team can be identified from the competition information, after which the match records are processed to calculate the team's total goals.

## 🔄 Solution Approach

The solution follows these main steps:

```text
Competition Name + Year
          │
          ▼
   Query Competition API
          │
          ▼
   Identify Winning Team
          │
          ▼
    Query Match API
          │
          ▼
 Retrieve Team's Matches
          │
          ▼
 Calculate Total Goals
          │
          ▼
        Result
```

## 🧠 Key Concepts

### 1. REST API Requests

Python is used to send requests to the provided API endpoints and retrieve competition and match information.

### 2. JSON Processing

API responses are returned as JSON data. The solution extracts the required fields from these responses.

### 3. Pagination

When an API endpoint returns multiple pages of results, the solution handles pagination to ensure all relevant matches are processed.

### 4. Data Filtering

Only matches involving the required team are selected for calculating the total number of goals.

### 5. Goal Calculation

Goals scored by the target team are extracted from each relevant match and added together to produce the final result.

---

## 🛠️ Technologies Used

| Technology        | Purpose                             |
| ----------------- | ----------------------------------- |
| **Python 3**      | Core programming language           |
| **REST API**      | Retrieve competition and match data |
| **HTTP Requests** | Communicate with API endpoints      |
| **JSON**          | Process API responses               |
| **HackerRank**    | Programming challenge platform      |

---

> The repository structure may vary depending on the number of HackerRank solutions included.

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/x-KUNAL-x/hacker-rank-rest-api-skills-certification-.git
```

### 2. Navigate to the project

```bash
cd hacker-rank-rest-api-skills-certification-
```

### 3. Run a solution

```bash
python solution.py
```

Make sure Python 3 is installed on your system.

---

## 💡 Skills Demonstrated

This project demonstrates the following skills:

* 🐍 Python Programming
* 🌐 REST API Integration
* 📡 HTTP Requests
* 📦 JSON Data Handling
* 🔄 Pagination Handling
* 🧮 Algorithmic Problem Solving
* 🔍 Data Filtering
* 🧠 Logical Problem Solving
* 📊 Data Processing

---

## 🎓 Learning Outcome

Through this project, I gained practical experience working with REST APIs and learned how to retrieve, process, filter, and analyze structured data using Python.

The challenge also strengthened my understanding of API-driven programming and algorithmic problem solving.

---

## 👨‍💻 Author

**Kunal Kumar**

Python Developer | Cybersecurity Enthusiast

---

## ⚠️ Disclaimer

This repository contains solutions developed for educational and practice purposes based on HackerRank challenges. All API endpoints and challenge data belong to their respective owners.
