# AI-Powered Resume Screening, Matching and Interview Preparation System


## Overview
Revolutionizing talent acquisition with intelligent automation. Accurately ranks candidates based on job description relevance and can compare resume with job description and gives match score and keywords and suggestions. User can compare their resume with job description and can get match score, keywords to add in resume,  suggestions and can take mock interviews on jobs he applied and can get their detailed performance, strengths ,weakness and red flags.

## Features
- **Job Description Input**: Allows recruiters to input a job description.
- **Resume Parsing & Storage**: Extracts key details from resumes and stores them in MongoDB.
- **AI-based Resume Ranking**: Uses sentence transformers and cosine similarity to rank resumes based on job relevance.
- **Resume-to-Job Matching**: Upload your resume and get an instant match score, relevant keywords, and personalized suggestions to improve your chances..
- **Mock Interviews on Applied Jobs**: Take simulated interviews tailored to the specific jobs you’ve applied for.
- **Detailed Interview Feedback**:  Receive comprehensive performance reports highlighting your strengths, weaknesses, and potential red flags—empowering continuous improvement.
- **Real-time Results**: Displays ranked resumes dynamically using React.
- **Download & Export Options**: Provides options to export shortlisted resumes.
- **User Authentication**: Secure login system for recruiters.

## Tech Stack
- **Frontend**: React.js, Vite, Tailwind CSS
- **Backend**: Flask (Python)
- **AI Models**: Sentence Transformers, NLP
- **Database**: MongoDB (NoSQL storage for resumes and job descriptions)
- **Search Algorithm**: Cosine Similarity for relevance ranking

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/varshithkumar7779/Skill_UP
   ```
2. Navigate to the project directory:
   ```sh
   cd resume-screening
   ```
3. Install dependencies:
   ```sh
   npm install  # For frontend
   pip install -r requirements.txt  # For backend
   ```
4. Start the backend server:
   ```sh
   .\venv\Scripts\activate #for creating virtual env
   python run.py # to start backend
   ```
5. Start the frontend server:
   ```sh
   npm run dev # to start frontend
   ```

## Usage
- Open `http://localhost:5173` to access the frontend.
- Upload resumes in PDF format.
- Input job descriptions.
- View ranked resumes with scores.



## Future Enhancements
- Add resume keyword extraction.
- Improve UI/UX with better visualizations.
- Integrate multiple job descriptions for comparison.



## Contact
For any queries, reach out via:
- Email,github: varshithkumar1001@gmail.com

