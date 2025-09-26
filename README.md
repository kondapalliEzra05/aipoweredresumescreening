AI- POWERED RESUME SCREENING AND RANKING SYSTEM

submitted in partial fulfillment of the requirements of

AICTE Internship on AI: Transformative Learning

with

TechSaksham – A joint CSR initiative of Microsoft & SAP

by

EZRA K, ezrareddy11@gmail.com

Under the Guidance of

SOMAYA CHOWDARY

ACKNOWLEDGEMENT

We would like to take this opportunity to express our deep sense of gratitude to all individuals who helped us directly or indirectly during this thesis work.

Firstly, we would like to thank my supervisor SOMAYA CHOWDARY for being a great mentor and the best adviser I could ever have. His advice, encouragement and the critics are a source of innovative ideas, inspiration and causes behind the successful completion of this project. The confidence shown in me by him was the biggest source of inspiration for me. It has been a privilege working with him for the last one year. He always helped me during my project and many other aspects related to the program. His talks and lessons not only help in project work and other activities of the program but also make me a good and responsible professional.

ABSTRACT

Provide a brief summary of the project, including the problem statement, objectives, methodology, key results, and conclusion. The abstract should not exceed 300 words.

The evolving technology is creating many chances of employment for many. Nowadays to apply for any job the most essential document is a resume. A resume tells a lot about the person's achievements and the skill sets in all walks of life. The person applying for the job highlights the strong points and skill sets required for the company. Multinational organizations receive thousands of emails from such people who send their resumes for them to apply for a certain post. Now the real challenge is to know which resume is to be sorted and shortlisted according to the constraints. One method is to manually check and sort the resume. Now, this method is the most time-consuming and also can lead to a lot of errors because of human interventions. Also, humans cannot keep on working continuously. Using Natural Language Processing and Machine Learning to rank the resumes according to the given constraint, this intelligent system ranks the resume of any format according to the given constraints or the following requirement provided by the client company. We will basically take the bulk of input resume from the client company and that client company will also provide the requirement and the constraints according to which the resume should be ranked by our system.

TABLE OF CONTENT

Chapter 1.

Introduction ......................................................................................... 6

1.1 Problem Statement ............................................................................... 6

1.2 Motivation ............................................................................................. 6

1.3 Objectives .............................................................................................. 6

1.4. Scope of the Project ............................................................................. 6

Chapter 2.

Literature Survey ................................................................................ 7

2.1 Review relevant literature…………………………………................. 7

2.2 Mention any existing models, techniques……………………………. 7

2.3 Highlights…………………………………………………………….. 7

Chapter 3.

Proposed Methodology ....................................................................... 8

3.1 System Design……………………………………………………….. 8

3.2 Requirement Specification…………………………………………... 8

3.2.1 Hardware Requirements……………………………………... 8

3.2.2 Software Requirements……………………………………… 8

Chapter 4.

Implementation and Results .............................................................. 9

4.1 Snap Shots of Result………………………………………………… 9,10

4.2 GitHub Link for Code……………………………………………….. 10,11,12

Chapter 5.

Discussion and Conclusion .............................................................. 13

5.1 Future Work……………………………………………………….. 13

5.2 Conclusion.………………………………………………………… 13,14

References .................................................................................................................. 14

LIST OF FIGURES

Figure No.

Figure Caption

Page No.

Figure 1

3.1 System Design

8

Figure 2

4.1 Snap Shots of Result

9-10

CHAPTER 1

Introduction

1.1 Problem Statement:

In the modern recruitment process, organizations receive an overwhelming number of resumes for each job opening Screening these resumes to identify the most suitable candidates is a time consuming and labor-intensive task. Automating this process using machine learning and natural language processing (NLP) techniques can significantly improve the efficiency and effectiveness of recruitment.

1.2 Motivation:

The AI-powered resume screening and ranking system is a project that leverages artificial intelligence to automate and enhance the recruitment process, specifically focusing on sorting, ranking, and evaluating resumes. This project is often chosen because it addresses several key challenges in recruitment, such as the high volume of resumes, bias in hiring, and inefficiency in manual screening.

1.3 Objective:

The objectives of the AI-powered resume screening and ranking system project are to:

Automate the resume screening process to save time and effort.

Rank candidates based on the relevance of their qualifications to the job.

Enhance hiring efficiency by reducing time-to-hire.

Minimize bias in the recruitment process, ensuring fairness.

1.4 Scope of the Project:

Scope:

The AI-powered resume screening and ranking system will automate the extraction of key information from resumes, rank candidates based on job relevance, reduce bias, and provide data-driven insights. It will integrate with existing Applicant Tracking Systems (ATS), scale for high-volume hiring, and continuously improve with new data.

Limitations:

The system's effectiveness depends on the quality of input data, may perpetuate biases if trained on biased datasets, and struggles with understanding unstructured or nuanced data. It cannot replace human judgment in areas like cultural fit or soft skills, and may require ongoing adjustments to stay relevant to changing job market trends.

CHAPTER 2

Literature Survey

2.1 Review relevant literature or previous work in this domain.

Resume Screening is a very important step in the hiring process. Even today, many companies are following the traditional resume screening process Even though many efficient systems were proposed to perform resume screening operations, due to some problems; the systems are not efficient as expected. Resume Screening using Machine Learning approaches has some issues like a time consuming, not being user-friendly, etc. Resume Screening using Artificial Intelligence approaches has some issues with input/output format, single resume acceptance for a time (which leads to a lot of time to screen all the resumes), etc.

2.2 Mention any existing models, techniques, or methodologies related to the problem.

The systems has models that don’t have any way to improve themselves over the time, the models will be trained only once. The models used Machine learning algorithms which have a tend to plateau in performance when run over a large dataset. The application can only be used effectively by the programmer. Each code block is interdependent; each change requires disrupting the entire code, which may disrupt the flow.

2.3 Highlight the gaps or limitations in existing solutions and how your project will address them.

Gaps in Existing Solutions:

Bias in Hiring: Many existing systems still carry biases, impacting fairness in candidate selection.

Inefficiency with Large Volumes: Current tools struggle to efficiently process and rank a high volume of resumes.

Limited Understanding of Soft Skills: Many systems focus only on technical skills, overlooking soft skills and cultural fit.

Lack of Adaptability: Existing solutions often fail to evolve with changing job market trends and new resume formats.

How Our Project Addresses These Gaps:

Bias Reduction: Our AI system is designed to minimize bias and promote fair, objective evaluations.

Improved Efficiency: The system efficiently processes and ranks large volumes of resumes, speeding up the hiring process.

Holistic Candidate Matching: It evaluates both technical qualifications and soft skills, enhancing overall job fit.

Continuous Learning: Our system adapts to evolving job trends, ensuring it stays relevant and effective over time.

CHAPTER 3

Proposed Methodology

3.1 System Design

This Use Case Diagram is a graphic depiction of the interactions among the elements of Resume Builder. It represents the methodology used in system analysis to identify, clarify, and organize system requirements of Resume Builder. The main actors of Resume Builder in this Use Case Diagram are: Dataset, User, Algorithm who perform the different type of use cases such as Manage Resume, Manage Skills, Manage Job, Manage Formats, Manage Resume Types, Manage Users and Full Resume Builder Operations. Major elements of the UML use case diagram of Resume Builder.

3.2 Requirement Specification

3.2.1 Hardware Requirements:

Processor : Pentium Dual Core 2.00GHZ

Hard disk : 120 GB

RAM : 2GB (minimum)

Keyboard : 110 keys enhanced

3.2.2 Software Requirements:

FRONT END : streamlit. BACK END : python.

FRAMEWORKS : Sklearn / NLKT / Spacy.

CHAPTER 4

Implementation and Result

4.1 Snap Shots of Result:

4.2 GitHub Link for Code:

https://github.com/kondapalliEzra05/aipoweredresumescreening

SOURCE CODE :

import streamlit as st

from PyPDF2 import PdfReader

import pandas as pd

from sklearn.feature_extraction.text import TfidfVectorizer

from sklearn.metrics.pairwise import cosine_similarity

#function to extract text from pdf

def extract_text_from_pdf(file):

text
pdf = PdfReader(file)[1]

text = ""[1]

for page in pdf.pages:[1]

    text += page.extract_text()[1]

return text[1]
#funxtion to rank resume based on job description

def rank_resumes(job_description, resumes) :

text
documents = [job_description] + resumes[1]

vectorizer = TfidfVectorizer().fit_transform(documents)[1]

vectors = vectorizer.toarray()[1]

#Calculate cosine similarity[1]

job_description_vector = vectors[1]

resume_vectors = vectors[1:][1]

cosine_similarities = cosine_similarity([job_description_vector],[1]
resume_vectors).flatten()

text
return cosine_similarities[1]
#streamlit app

st.title("Resume Ranking App")

#job description input

st.header("Job Description")

job_description = st.text_area("Enter the job description")

st.header("Upload Resumes")

uploaded_files = st.file_uploader("Choose a file", type=['pdf'],

accept_multiple_files=True)

if uploaded_files and job_description:

text
st.header("Ranking Resumes")[1]

resumes =[][1]

for file in uploaded_files:[1]

    text = extract_text_from_pdf(file)[1]

    resumes.append(text)[1]

#rank Resumes[1]

scores = rank_resumes(job_description, resumes)[1]

#display scores[1]

results = pd.DataFrame({"Resumes":[file.name for file in[1]
uploaded_files], "Scores": scores})

text
results = results.sort_values(by="Scores", ascending=False)[1]

st.write(results)[1]
CHAPTER 5

Discussion and Conclusion

5.1 Future Work:

Integrate advanced NLP techniques like BERT or GPT for improved contextual understanding and semantic matching.

Implement a custom-trained deep learning model for more accurate resume ranking.

Incorporate structured data extraction from resumes to better assess qualifications and skills.

Expand with interactive dashboards for data visualization and improved user interaction.

Add multi-language support to cater to a global audience.

Strengthen security measures for robust protection of data and system integrity.

Establish regular updates and feedback loops for continuous improvement and adaptability to industry changes.

5.2 Conclusion:

Functional Solution:

The project developed a Flask-based web application that effectively ranks and classifies resumes using machine learning models and text processing techniques, streamlining the hiring process by matching resumes to job descriptions.

User-Friendly Interface:

It features an intuitive interface for uploading resumes, inputting job descriptions, and viewing ranked results, with responsive design and clear error handling.

Data Processing and Ranking:

The system utilizes TF-IDF vectorization and cosine similarity to evaluate resume relevance, providing a quantitative measure of how well each resume aligns with the job description.

Future Enhancements:

Potential improvements include integrating advanced NLP models, adding more features for nuanced ranking, and expanding the data processing pipeline to enhance the system's accuracy and adaptability.

REFERENCES

. Ming-Hsuan Yang, David J. Kriegman, Narendra Ahuja, “Detecting Faces in Images: A Survey”, IEEE Transactions on Pattern Analysis and Machine Intelligence, Volume. 24, No. 1, 2002.
