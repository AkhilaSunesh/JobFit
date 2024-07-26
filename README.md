# JobFit
# Resume ATS Scanner 📄➡️🔍

## Problem Statement
In today's competitive job market, applicants often struggle to ensure their resumes stand out and pass through Applicant Tracking Systems (ATS). Many resumes are rejected due to formatting issues, lack of relevant keywords, or simply not meeting the job description's requirements. There is a need for a tool that can help job seekers optimize their resumes, provide feedback, and compare multiple resumes against a job description to determine the best fit.

## Our Approach
We have developed a Resume ATS Scanner that allows users to upload their resumes in PDF format, get an estimated reading time, and receive a summary, ATS rating, and feedback based on the provided job description. The tool also allows users to ask specific questions about their resumes and compare multiple resumes to identify the best fit for a job.

## Features
- **Resume Upload:** Upload resumes in PDF format.
- **Reading Time Estimation:** Provides an estimated reading time for the resume.
- **Resume Summary:** Generates a summary of the resume highlighting key skills, experiences, and achievements.
- **ATS Rating:** Rates the resume based on relevance to the job description.
- **Feedback:** Provides constructive feedback on how to improve the resume.
- **Question & Answer:** Users can ask specific questions about their resume.
- **Resume Comparison:** Compare multiple resumes to determine the best fit for a job description.
- **Job Description Integration:** Option to add a job description, company name, and job post for more accurate analysis.

## Updates
- **v1.0:** Initial release with resume upload, summary, ATS rating, feedback, and Q&A features.
- **v1.1:** Added functionality to compare multiple resumes and select specific resumes for comparison.
- **v1.2:** Improved UI and added support for job description integration.

## Timeframe
- **Week 1:** Define problem statement and requirements.
- **Week 2:** Develop resume upload and text extraction functionality.
- **Week 3:** Implement resume summary, ATS rating, and feedback features.
- **Week 4:** Add question & answer functionality.
- **Week 5:** Develop resume comparison feature.
- **Week 6:** Integrate job description and improve UI.
- **Week 7:** Testing and debugging.
- **Week 8:** Final review and deployment.

## Installation

### Prerequisites
- Python 3.7 or higher
- pip (Python package installer)
- A Google Cloud account with access to Generative AI APIs
- A `.env` file with your Google API key:
- ``` GOOGLE_API_KEY=your_google_api_key ```

### Steps
1. Clone the repository:
  ```bash
  git clone https://github.com/yourusername/resume-ats-scanner.git
  cd resume-ats-scanner
  ```

2. Create a virtual environment:
  ```bash
  python -m venv venv
  source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
  ```

3. Install the required packages:
  ```bash
  pip install -r requirements.txt
  ```

4. Run the Streamlit application:
  ```bash
  streamlit run app.py
  ```

5. Open your web browser and navigate to `http://localhost:8501`.

## Technology Used
- **Python**
- **Streamlit**: For the web interface
- **PyMuPDF (fitz)**: For PDF text extraction
- **Google Generative AI (Gemini)**: For generating content, summaries, ratings, and feedback
- **dotenv**: For managing environment variables

## Demonstrations

### Photo Demonstrations
![Screenshot of Resume Upload](s1.png)


### Video Demonstrations
[Placeholder for video demonstration](placeholder_for_video_url)

## Contributors
- **Akhila Sunesh** - [akhilasunesh@gmail.com](mailto:akhilasunesh@gmail.com)
- **Other Contributors**

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


