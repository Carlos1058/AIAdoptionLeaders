# DYCSI AI Pioneers Project

A strategic initiative to identify and select internal change agents to drive the adoption of Artificial Intelligence technologies throughout the company.

---

## Executive Summary

The "AI Pioneers" project is a strategic initiative by **DYCSI** to accelerate and streamline the adoption of Artificial Intelligence (AI) technologies across the organization. Led by the **AI Consultant Interns** team and supervised by our **CEO**, this project will leverage an innovative, data-driven approach to identify a select group of employees. These "Pioneers" will be influential, charismatic, and proactive individuals who will act as change agents, training and motivating their peers in the use of new AI tools. The selection process will be conducted through a company-wide survey and the application of a Machine Learning model (Logistic Regression) to ensure an objective and effective process.

## The Problem

The implementation of new technologies, especially AI, often faces a cultural and human barrier rather than a technical one. Resistance to change, lack of knowledge, or fear of complexity can slow down adoption and limit the return on investment. A purely top-down approach is not always sufficient to drive meaningful change.

To overcome this challenge, we need an internal, peer-led movement that builds trust, demonstrates the value of AI in a practical way, and fosters a culture of curiosity and innovation from within.

## Project Objectives

-   **Primary Objective:**
    -   To identify and select a group of 5-10 employees ("AI Pioneers") who fit the ideal profile to lead AI adoption at DYCSI.

-   **Secondary Objectives:**
    -   Develop a scalable and reusable selection model for future change management initiatives.
    -   Gauge the current level of openness and enthusiasm towards AI within the company.
    -   Foster a positive and expectant atmosphere around the implementation of new technologies.
    -   Validate the use of Machine Learning for internal HR and change management processes.

## Methodology and Phases

The project will be executed in four key phases:

1.  **Phase 1: Survey Design and Planning**
    -   **Tool:** We will use **Google Forms** to facilitate easy creation, distribution, and automatic data collection into a Google Sheet.
    -   **Content:** A concise survey of 5-7 questions will be designed to indirectly measure the desired qualities. Questions will include:
        -   **Likert Scale (1-5):** To measure self-perception of initiative, openness to change, and comfort with technology.
        -   **Multiple Choice:** To understand learning and collaboration preferences.
        -   **Open-Ended Nomination:** A key question such as: *"Which colleague would you ask for help with a new tech tool, and why?"* This will be crucial for influence analysis.

2.  **Phase 2: Data Collection**
    -   The survey link will be distributed to all DYCSI employees via internal communication channels.
    -   A clear deadline (e.g., 5 business days) will be set to ensure a high participation rate. The confidentiality of individual responses will be guaranteed to encourage honest feedback.

3.  **Phase 3: Data Processing and ML Model Development**
    -   The collected data from Google Sheets will be exported to a `.csv` file.
    -   Data will be cleaned and preprocessed to convert it into numerical features for the model.
    -   A **Logistic Regression** model will be trained. The target variable (what we want to predict) will be whether an employee is an "ideal candidate" or not. This label will be derived from a combination of factors: high self-assessment scores, being nominated by peers, and expressing explicit interest and availability.
    -   The model will learn the patterns that define an ideal candidate based on the survey data.

4.  **Phase 4: Analysis, Selection, and Reporting**
    -   The trained model will assign a "suitability score" to each employee.
    -   The AI Consultant Interns team will analyze these results, combining the quantitative score with a qualitative analysis of open-ended responses (the reasons for nominations).
    -   A final report will be generated with the list of recommended candidates, the methodology used, and key insights. This report will be presented to the CEO for final approval.

## The "AI Pioneer" Profile (Selection Criteria)

We are looking for collaborators who demonstrate:

-   **Empathy and Charisma:** The ability to connect with others and build trust. They are people others listen to.
-   **Positive Influence:** Their opinion is respected, and they are often recommended by their peers.
-   **Initiative and Proactivity:** They don't wait to be told what to do; they actively seek new ways to improve.
-   **Openness and Curiosity:** They show a genuine interest in learning and experimenting with new technologies, without fear of making mistakes.
-   **Communication Skills:** They can explain potentially complex topics in a simple and accessible way.
-   **Availability and Commitment:** They have the time and willingness to dedicate to this leadership role.

## Project Deliverables

1.  The finalized survey in Google Forms.
2.  The cleaned and anonymized dataset (`.csv` format).
3.  The source code (Jupyter Notebook/Python script) for the Machine Learning model.
4.  A **Final Selection Report** that includes:
    -   A summary of the process and methodology.
    -   An analysis of the survey results.
    -   The final list of recommended "AI Pioneers" with a brief justification for each.
