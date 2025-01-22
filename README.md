# GeneratingReportCards
# **Project Overview**

The Student Report Card Generator is a Python-based project designed to automate the creation of personalized PDF report cards for students. It utilizes the pandas library for data processing and the ReportLab library for generating professional-grade PDF files. This project streamlines the process of reading student data from an Excel file, calculating total and average scores, and presenting the information in a clear, tabular format.

# **Key Features**

**-** Automated Data Processing: Reads student data from an Excel file and organizes it by student ID and name.

**-** Score Calculation: Computes total and average scores for each student across all subjects.

**-** Personalized PDF Report Cards: Generates a professional-looking PDF for each student with:

    - Student name
    
    - Total and average scores
    
    - A subject-wise score table
    
**Error Handling:** Handles missing or invalid data in the Excel file to ensure smooth execution.

**Download Links:** Provides download links for each generated PDF report card.

# **Technologies Used**

**Python Libraries:**

**pandas** for data manipulation.

**ReportLab** for creating PDF files.

**Jupyter Notebook:** Interactive development environment for the project.

**Excel:** Input file format for student data.

# **How It Works**

**1.** The script reads data from an Excel file (student_scores.xlsx) with columns:

     - Student ID
     
     - Name
     
     - Subject
     
     - Subject Score
     
**2.** It validates and cleans the data, ensuring all scores are numeric and non-null.

**3.** The data is grouped by Student ID and Name to calculate the total and average scores for each student.

**4.** A PDF report card is generated for each student, containing their scores and overall performance summary.

**5.** Users can download the generated PDFs directly.

# **Usage**

**1.** Place the student_scores.xlsx file in the project directory.

**2.** Run the script in a Jupyter Notebook or any Python IDE.

**3.** PDF files will be saved with the naming format: report_card_<StudentID>.pdf.

**4.** Download links for the PDFs will be displayed for easy access.
