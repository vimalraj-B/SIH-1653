# Smart India Hackathon Workshop
# Date:18/3/2025
## Register Number:212224100051
## Name:rizwan.B
## Problem Title
SIH 1653: Web based Selector-Applicant Simulation Software
## Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

## Problem Creater's Organization
Ministry of Defence

## Idea
Develop an AI-powered Interview Assessment System that simulates a Board Room Interview Experience for DRDO RAC. The system will:

Provide Structured Interviews: Start with ice-breaking questions and gradually progress to in-depth techno-managerial questions.
Ensure Relevance: Match questions to the candidate's expertise and grade answers for relevancy and correctness.
AI-driven Scoring: Experts and AI evaluate candidate responses, generating an overall suitability score.
Interactive Panel: Experts can collaborate, refine questions, and view real-time AI-based candidate analytics.
Bias-Free Evaluation: AI ensures an unbiased assessment by comparing responses with ideal answers and scoring objectively.


## Proposed Solution / Architecture Diagram

![AI-Powered Interview Assessment System Architecture for DRDO RAC](https://github.com/user-attachments/assets/5bcdf5af-5f5b-4a34-9395-7e213e0220ce)

## Use Cases
![AI-Powered Board Room Interview System for DRDO RAC](https://github.com/user-attachments/assets/2f37c276-ef02-4403-af37-e7d379432036)


## Technology Stack
Frontend (User Interface for Experts & Candidates)
React.js / Next.js → Interactive, fast UI
Tailwind CSS / Material UI → Modern design
WebRTC / Agora SDK → Live video interview simulation
Backend (Processing & AI Models)
Node.js (Express.js) / FastAPI (Python) → Scalable API services
PostgreSQL / MongoDB → Storing candidate profiles, questions, responses
Redis → Caching frequently used data for faster performance
AI & NLP Models (For Interview Analysis & Scoring)
OpenAI GPT / Llama / Custom BERT Model →
Generate contextual questions
Analyze candidate responses
Score based on relevance and accuracy
Speech-to-Text (Whisper, Google Speech API) → Transcribe spoken answers
Hugging Face Transformers → Advanced NLP for response evaluation
Scoring Mechanism
TF-IDF / BERT Similarity Model → Evaluate candidate response relevance
Rule-Based Scoring (Python, NLTK, Spacy) → Check key concepts, completeness
Weighted Scoring Algorithm → Combine AI & expert scores for final assessment
Video & Audio Analysis (Optional Enhancements)
DeepFace / OpenCV → Candidate facial expressions & emotion analysis
NLP Sentiment Analysis → Detect candidate confidence, clarity

## Dependencies
OpenAI / Hugging Face → NLP & text analysis
WebRTC / Agora SDK → Live video
Google Speech API / Whisper → Speech-to-text
PostgreSQL / MongoDB → Database
Docker / Kubernetes → Containerized deployment
Redis → Caching
ElasticSearch → Fast question retrieval
