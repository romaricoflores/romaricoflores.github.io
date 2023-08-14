---
title: JobMatch App Project 
date: 2023-08-14 6:00
categories: [PORTFOLIO, MACHINE LEARNING]
tags: [streamlit, nlp, machine learning]
---

This project is a tool to assess how well your resume matches a job posting. Simply input your resume and the job description, and let the app calculate the match score. The project uses Spacy which is a powerful and efficient open-source library for working with text and performing tasks like understanding the meaning of words, identifying named entities (like names of people or places), and analyzing sentence structure.

The process begins as Streamlit captures your resume and the job posting. Utilizing Spacy, it tokenizes and preprocess the textual content, creating linguistic representations. These representations are then evaluated for semantic similarity, yielding a match score that quantifies alignment.

The match score, ranging from 0 to 100%, shows the convergence of your skills and the job requirements. The results are also interpreted as a 'Strong Match,' 'Moderate Match,' 'Weak Match,' or 'Low Match.' based on the skills and experience required for the position.

<iframe src="https://jobmatch.streamlit.app?embedded=true" width="100%" height="800" style="border: none;"></iframe>
