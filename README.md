﻿# AI-Powered Resume Screening, Matching and Interview Preparation System


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


- Add resume keyword extraction
.
- Improve UI/UX with better visualizations.
- Integrate multiple job descriptions for comparison.

## Contact

For any queries, reach out via:
- Email,github: varshithkumar1001@gmail.com

## User Panel:
1. ![Screenshot (674)1](https://github.com/user-attachments/assets/f3b22538-10d3-4e46-a048-7a56ea6b135f)
2. ![Screenshot (675)2](https://github.com/user-attachments/assets/9deef38d-b658-49c7-93c0-79f476c04f3f)
3. ![Screenshot (672)3](https://github.com/user-attachments/assets/4478a4e3-1994-4351-ad67-fcd294020caf)
4. ![Screenshot (673)4](https://github.com/user-attachments/assets/caa8e025-5cc4-4b3b-a862-88f6ff7d68c8)
5. ![Screenshot (671)5](https://github.com/user-attachments/assets/fe5a8648-90c7-42ed-a46a-31b079886054)
6. ![Screenshot (679)16](https://github.com/user-attachments/assets/7385a690-bb6d-46b3-a181-51fe26b98b4e)
7. ![Screenshot (680)17](https://github.com/user-attachments/assets/f9bdb558-a0d6-4c30-968d-dafb8479181b)
8. ![Screenshot (667)6](https://github.com/user-attachments/assets/d6bf9a0a-338d-4c68-9ce6-cfa2ce7da3d4)
9. ![Screenshot (668)7](https://github.com/user-attachments/assets/c1a0daa0-4119-4ac9-bdcc-5a4eab181ef4)
10. ![Screenshot (669)8](https://github.com/user-attachments/assets/4fe23b7e-c134-48d0-ae90-b2052feec2a8)
11. ![Screenshot (670)9](https://github.com/user-attachments/assets/6b0eea79-3f16-4d98-bb4d-0e7dacc7d9ba)

## Admin/Recruiter Panel:
12. ![Screenshot (676)10](https://github.com/user-attachments/assets/316608c3-77cf-4292-8a85-271d0ece57c7)
13. ![Screenshot (677)11](https://github.com/user-attachments/assets/91147251-1c6e-4fe6-a2e1-664d6a11a2b8)
14. ![Screenshot (682)12](https://github.com/user-attachments/assets/8887fbd3-808a-4627-827c-981cff13610a)
15. ![Screenshot (683)13](https://github.com/user-attachments/assets/4b270a4b-2297-45a9-aa92-2e008a8dcf5b)
