---
title: JobMatch App Project 
date: 2023-08-14 6:00
categories: [PORTFOLIO, MACHINE LEARNING]
tags: [streamlit, nlp, machine learning]
---

![Streamlit](https://cdn.thenewstack.io/media/2021/11/28de6660-screen-shot-2021-11-29-at-6.46.11-am.png)

This project is a tool to assess how well your resume matches a job posting. Simply input your resume and the job description, and let us calculate the match score for you. the power of Streamlit and Spacy to analyze your resume against any job posting. The algorithm computes the match score based on natural language processing. 

The process begins as Streamlit captures your resume and the job posting. Utilizing Spacy, we tokenize and preprocess the textual content, creating linguistic representations. These representations are then evaluated for semantic similarity, yielding a match score that quantifies alignment.

The match score, ranging from 0 to 1, is a testament to the convergence of your skills and the job requirements. With a mastery threshold set at 0.9, the interpretation engine deciphers the score. You could be in for a 'Strong Match,' 'Moderate Match,' 'Weak Match,' or 'Low Match.' based on the skills and experience required for the position.

[Streamlit Link](https://jobmatch.streamlit.app)

<iframe src="https://jobmatch.streamlit.app?embedded=true" width="100%" height="600" style="border: none;"></iframe>
