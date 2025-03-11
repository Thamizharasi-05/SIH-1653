# Smart India Hackathon Workshop

*Date:11/03/2025* 

*Register Number: 212224100059*  
*Name:Thamizharasi G*  

## Problem Title  
*SIH 1653: Web-Based Selector-Applicant Simulation Software*

## Problem Description  
### *Background*  
Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence, conducts interviews for applications received against advertised vacancies and for promotion assessments for scientific personnel within DRDO. The interviewing process is critical to ensuring unbiased selection and the identification of the right talent.

### *Description*  
The interview process consists of questioning by an interviewer and evaluating the candidate's responses. Ensuring relevant questions aligned with the candidate’s expertise and scoring responses objectively is a challenge. 

### *Expected Solution*  
The solution should provide an interactive and immersive Board Room experience, facilitating a structured interview process that includes:  
- *Ice-breaking questions* to start the interview.  
- *Techno-managerial questions* based on the candidate’s expertise level.  
- *Quantifiable scoring mechanism* for both interviewers and candidates to evaluate question relevancy and response accuracy.  
- *Overall candidate assessment score*, determining suitability for the advertised position.

## Problem Creator's Organization  
*Ministry of Defence*

---

## Idea  
The core idea is to create a *Web-Based Selector-Applicant Simulation Software* that replicates a real-time boardroom interview experience using AI-driven automation and structured evaluation methodologies. The system will enable a *dynamic, adaptive, and unbiased interview process* by ensuring that both questions and candidate responses are assessed objectively.

### *Key Features of the Proposed Solution:*  
1. *Virtual Boardroom Simulation:* The system will replicate the in-person interview experience in a digital environment, complete with structured questioning, evaluation, and scoring mechanisms.
2. *AI-Powered Question Generation:* Based on the candidate's expertise and the job role, AI will dynamically generate relevant questions.
3. *Candidate Profile Analysis:* The system will analyze the candidate’s resume, qualifications, and past experiences to tailor interview questions accordingly.
4. *Automated Response Evaluation:* Natural Language Processing (NLP) models will assess candidate responses for relevance, technical accuracy, and clarity.
5. *Real-Time Scoring System:* Responses will be scored instantly, and the interviewer can override or validate the AI-generated score if required.
6. *Expert-Driven Review Panel:* Interviewers will have the ability to modify scores and add comments for detailed evaluation.
7. *Comprehensive Analytics Dashboard:* A reporting system will provide detailed insights into candidate performance, strengths, weaknesses, and final recommendations.
8. *Adaptive Interview Flow:* The system will modify the difficulty and depth of questions based on candidate performance during the interview.
9. *Secure and Scalable Cloud-Based Solution:* Ensuring accessibility, data privacy, and scalability for large-scale recruitment processes.
10. *Multi-User Collaboration:* Interviewers, HR personnel, and domain experts can simultaneously assess a candidate’s performance in real-time.

## Proposed Solution / Architecture Diagram  
### *Solution Overview*  
The proposed solution will be a web-based platform incorporating:
- Role-based access for interviewers and candidates.
- AI-driven question generation and response evaluation.
- Real-time scoring and feedback mechanism.
- Secure authentication and session management.
- Detailed analytics and reporting dashboard.

### *Architecture Diagram*  
- *Frontend:* User interface for both interviewers and candidates.  
- *Backend:* Question generation, scoring engine, and data management.  
- *Database:* Candidate profiles, interview history, and analytics storage.  
- *AI Module:* Natural Language Processing (NLP) for question-relevancy and response evaluation.

  ![Screenshot 2025-03-11 082810](https://github.com/user-attachments/assets/eb57cfed-1592-478b-9559-74fd986d6bd4)


## Use Cases  
1. *Candidate Simulation:* Candidates undergo a structured interview process.
2. *Dynamic Questioning:* AI generates relevant questions based on the candidate’s expertise.
3. *Response Evaluation:* NLP-based analysis to assess response quality and relevancy.
4. *Scoring System:* Automated scoring based on pre-defined evaluation criteria.
5. *Expert Review:* Interviewers can review and override scores if necessary.
6. *Final Report Generation:* A detailed report summarizing candidate performance.

## Technology Stack  
- *Frontend:* React.js / Angular
- *Backend:* Node.js / Django / Flask
- *Database:* PostgreSQL / MongoDB
- *AI & NLP:* Python (NLTK, SpaCy, GPT-based models)
- *Cloud Services:* AWS / Azure / GCP
- *Security:* OAuth2.0, JWT Authentication

## Dependencies  
- *Third-party APIs* for AI-driven question generation.
- *Cloud infrastructure* for hosting and scalability.
- *Data protection & compliance* with recruitment policies.

This structured solution will ensure a seamless, unbiased, and efficient recruitment process for RAC under DRDO.
