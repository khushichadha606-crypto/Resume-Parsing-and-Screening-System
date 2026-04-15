#  AI Resume Parsing & Screening System

An AI-powered system that processes and evaluates resumes, extracts key candidate information, and ranks applicants based on job relevance.

---

##  Project Overview

This project focuses on automating the initial stages of recruitment by:

* Parsing resume data
* Structuring candidate information
* Evaluating candidate suitability
* Generating ranked outputs

The final output is stored in a structured CSV file for easy analysis and decision-making.

---

##  Features

 Resume data extraction (skills, experience, education)
 Candidate scoring system
 Ranking based on job relevance
 Structured CSV output
 Easy integration with HR workflows

---

##  How It Works

### Step 1: Resume Data Input

Resumes are processed (manually or via dataset) and converted into structured format.

---

### Step 2: Data Extraction

Key fields are identified:

* Skills
* Experience
* Education
* Certifications

---

### Step 3: Data Structuring

All extracted information is stored in tabular format for analysis.

---

### Step 4: Scoring Mechanism

Each candidate is evaluated using predefined criteria such as:

* Skill match
* Experience level
* Educational qualification

---

### Step 5: Ranking Candidates

Candidates are ranked based on their final score.

---

### Step 6: Output Generation

The system generates a CSV file:

```id="k3x91z"
resume_parsing_screening_output.csv
```

This file contains:

* Candidate details
* Scores
* Ranking
* Final recommendations

---

##  Technologies Used

* Python 
* Pandas
* NumPy
* Scikit-learn (optional for scoring)

---

##  Project Structure

```id="z91n3q"
Resume-Parsing-and-Screening-System/
│
├── resume_parsing_screening_output.csv
├── parsing_model.ipynb (optional)
└── README.md
```

---

##  Use Cases

* Resume shortlisting
* HR automation
* Recruitment analytics
* Applicant tracking systems (ATS)

---

##  Disclaimer

This project is built for **academic and demonstration purposes only**.
Real-world hiring systems require deeper validation, fairness checks, and bias mitigation.

---

##  Author

Developed as part of an academic project showcasing AI applications in HR and recruitment.

---

##  Future Improvements

* Automatic PDF resume parsing
* NLP-based skill extraction
* Integration with job portals
* Bias detection algorithms
* Web dashboard for HR teams

---

 *"Transforming recruitment with data-driven decisions."*
