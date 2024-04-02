# Smart ATS

## Overview
Smart ATS (Applicant Tracking System) is a tool designed to assist in evaluating resumes based on provided job descriptions. It leverages AI-powered text analysis to match resumes with job requirements and offers suggestions for resume improvement. This tool aims to help job seekers enhance their resumes to increase their chances of success in a competitive job market.

## Features
- Resume evaluation based on provided job description
- Role matching percentage calculation
- Identification of missing keywords
- Profile summary generation
- Job recommendations with links to relevant job listings
- Course recommendations for skill improvement with links
- Resources for skill enhancement, including certifications

## Installation
To run the Smart ATS project, follow these steps:

1. Clone the repository to your local machine:
   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```bash
   cd smart-ats
   ```

3. Create a virtual environment (recommended):
   ```bash
   python3 -m venv venv
   ```

4. Activate the virtual environment:
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```
   - On macOS and Linux:
     ```bash
     source venv/bin/activate
     ```

5. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

2. Use the web interface to interact with the Smart ATS tool.
   - Paste the job description into the provided text area.
   - Upload your resume in PDF format.
   - Click the "Submit" button to receive resume evaluation results.

## Contributors
- Swaroop Charan, Jitendra Venkata Sai, and Rishi Kakarla
