---
title: "Resume fine-tuning using NLP and AI for improved ATS matching"
permalink: /portfolio/resumego
excerpt: ""
header:
  teaser: /assets/images/resumego_th.png
sidebar:
  - title: ""
    image: /assets/images/resumego_logo.png
    image_alt: "logo"
  - title: "Project goal"
    text: "The project aimed to develop ResumeGo, an AI-powered tool to optimize resumes for better alignment with job descriptions. ResumeGo helps job seekers increase their chances of passing Applicant Tracking Systems (ATS) by enhancing keyword relevance, structuring content, and providing real-time feedback on strengths and areas for improvement."

---

![alt]({{ site.url }}{{ site.baseurl }}/assets/images/resumego.png)

📅 October, 2024

### Objective
The project aimed to develop ResumeGo, an AI-powered tool to optimize resumes for better alignment with job descriptions. ResumeGo helps job seekers increase their chances of passing Applicant Tracking Systems (ATS) by enhancing keyword relevance, structuring content, and providing real-time feedback on strengths and areas for improvement.

### Project Description
As the lead developer, I created ResumeGo, an innovative AI-based application designed to analyze and adjust resumes for job description compatibility. The tool uses Natural Language Processing (NLP) and Cohere’s Command R+ model to identify and modify key resume areas, such as keyword matching, content structuring, and skill alignment. My role involved integrating multiple NLP libraries, developing an interactive interface, and implementing real-time resume scoring. I also addressed challenges related to skill extraction and keyword matching to ensure precise adjustments without inventing content.

### Tools and Technologies Used
- **Streamlit**: For building an interactive and user-friendly interface.
- **Python (spaCy, NLTK, RAKE)**: Used for text processing, keyword extraction, and skill matching.
- **Sentence Transformers**: Enabled embedding-based similarity scoring for resumes and job descriptions.
- **Cohere API**: Powered advanced text generation and enhancement features.
- **Plotly**: Utilized to visually represent the ATS compatibility score through a dynamic gauge chart.

These tools provided a robust framework for efficient text processing, embedding-based scoring, and insightful resume recommendations.

### Statistical and Analytical Techniques
- **Keyword Extraction (RAKE)**: Enabled targeted keyword matching between resumes and job descriptions.
- **Skill Matching**: Employed custom NLP pipelines to identify and integrate essential skills.
- **Cosine Similarity with Sentence Embeddings**: Facilitated similarity scoring for overall resume-job description alignment.
- **Weighted ATS Scoring**: Combined keyword and skill match ratios to provide a comprehensive ATS score.

**See it in action:**

[resumego.](https://resumego.streamlit.app/)
