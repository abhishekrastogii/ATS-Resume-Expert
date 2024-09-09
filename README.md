# ATS Resume Expert

## Overview
ATS Resume Expert is a tool designed to evaluate resumes against job descriptions. It leverages the Google Gemini API to provide professional feedback and analyze the percentage match between the uploaded resume and the given job description.

## Features
- **Resume Evaluation:** Upload a PDF resume and receive feedback on how well it aligns with the job description.
- **Match Percentage:** Get a percentage match score indicating how well the resume fits the job requirements.
- **Detailed Analysis:** Receive insights on strengths, weaknesses, and keywords missing from the resume.

## Installation

### Prerequisites
- Python 3.12 or later
- [Git](https://git-scm.com/)
- [Streamlit](https://streamlit.io/)

### Steps to Set Up

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/abhishekrastogii/ATS-Resume-Expert.git
Navigate to the Project Directory:

bash
Copy code
cd ATS-Resume-Expert
Create and Activate a Virtual Environment:

bash
Copy code
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
Install Required Packages:

bash
Copy code
pip install -r requirements.txt
Set Up Environment Variables: Create a .env file in the root directory and add your Google API key:

makefile
Copy code
GOOGLE_API_KEY=your_google_api_key_here
Run the Application:

bash
Copy code
streamlit run app.py
Usage
Job Description: Enter the job description in the provided text area.
Upload Resume: Use the file uploader to upload your resume in PDF format.
Evaluate Resume: Click on "Tell Me About the Resume" to get feedback, or "Percentage match" to get the match percentage.
License
This project is licensed under the MIT License. See the LICENSE file for details.

Contact
For questions or feedback, please contact Abhis Rastogi.
