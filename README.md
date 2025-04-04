# Forensic Investigation Management System

A mini project built as part of the *Database Management Systems Laboratory** under the course code [BCS403], Bachelor of Engineering in **Artificial Intelligence and Machine Learning** at **Jyothy Institute of Technology**, affiliated with **Visvesvaraya Technological University (VTU)**.

## 📖 Project Overview

The **Forensic Investigation Management System** is a database-centric application developed to support the investigation and analysis of murder cases. Leveraging core principles of **Database Forensic Investigation (DBFI)**, the system helps record, retrieve, and relate key data involving:

- Victims
- Suspects
- Investigators
- Evidence
- Case details

This structured approach ensures comprehensive and chronological documentation and aids in identifying links between suspects and events.

## 🎯 Objectives

- Design a relational database schema for forensic case management.
- Implement entities and relationships to capture case attributes, evidence, and personnel details.
- Enable structured queries for analysis and reporting.
- Assist in reconstructing the sequence of events in criminal investigations.

## 🗂️ Features

- 👮 **User Authentication:** Sign-up/login system for secure access.
- 🧬 **Data Entities:**
  - **Victims:** Personal and incident details.
  - **Suspects:** Identifiers and suspicion levels.
  - **Evidence:** Includes DNA, eye color, hair color, etc.
  - **Police Officers:** Assigned investigators and logs.
- 🔍 **Querying and Analysis:** Search and retrieval of case data based on categories and criteria.
- 📊 **Admin Dashboard:**
  - View, edit, or delete any case-related entries.
  - Manage users, posts, and featured cases.
  - Monitor system updates and logs.
- 📝 **Blog Module:** Add, view, and categorize case summaries or insights.
- 🖼️ **Snapshots & Visuals:** Interface screenshots and database interaction results.

## 🧩 Technologies Used

- **Frontend/UI:** Streamlit (Python)
- **Backend:** MySQL, Python
- **Database Design:** ER Diagrams, Relational Schemas
- **Version Control:** Git & GitHub

## 🔧 Installation

1. Clone the repository (git bash):
   ```
   git clone https://github.com/Khushi-Sorathia/Forensics-investigation.git
   cd Forensics-investigation

2. Install dependencies:
```
pip install -r requirements.txt
```
3. Launch the application using Streamlit:
```
   streamlit run app.py
   ```
5. Ensure the MySQL server is running and credentials are properly set in your db_config.py.
