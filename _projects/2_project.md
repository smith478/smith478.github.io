---
layout: page
title: summarize medical data
description: transcribing and summarizing medical audio
img: assets/img/medical_summarization.png
importance: 2
category: work
---

This project aims to address the critical issue of burnout among medical professionals by streamlining the process of generating discharge notes. This process is not only time-consuming but also prone to inaccuracies, particularly if there is a significant delay between the patient consultation and the creation of these notes. The idea here leverages advancements in Automatic Speech Recognition (ASR) and Large Language Models (LLMs) to automate the transcription and summarization of discharge notes from raw audio recordings of patient-clinician conversations.

Here is an overview of the project.

## 1. Project Scope
* Real-time Transcription and Summarization:
    - Develop a feature for real-time transcription and summarization, allowing clinicians to review and edit discharge notes immediately after or during a consultation, significantly reducing inaccuracies and recall bias.
* Integration with Electronic Health Records (EHRs):
    - Ensure seamless integration with existing EHR systems, allowing for automated updates to patient records with minimal manual input, thus enhancing efficiency and reducing clerical errors. This can be extracted from the transcribed text.
* Multilingual Support:
    - Implement multilingual ASR capabilities to work across a number of languages.

## 2. Technical Development
* ASR Module Development:
    - Develop a robust ASR system capable of handling medical terminology with high accuracy, including the ability to adapt to different accents and speech patterns. In limited experimentation it seems that both OpenAI Whisper and NVIDIA Parakeet does a good job with these challenges. 
* Summarization and Formatting Engine:
    - Design an LLM-based summarization engine tailored for medical discourse, capable of identifying and highlighting critical information such as diagnosis, treatment plans, and follow-up instructions.
    - Include formatting rules in order to generate standardized discharge notes, making them easy to read and understand.
* Validation and Feedback Loop:
    - Implement a mechanism for clinicians to provide feedback on the accuracy and completeness of the automated notes, facilitating continuous learning and improvement of the system.

## 3. User Interface and Experience
* Design an intuitive user interface that allows clinicians to easily review, edit, and finalize discharge notes. For fast testing and development, the initial app has been built using streamlit. 
* Include voice command features for hands-free operation, enhancing usability during or immediately after patient interactions.

## 4. Expansion to Other Applications
* Explore the potential for using these tools in other areas of healthcare documentation, such as consultation summaries, referral letters, and patient education materials.
* Investigate the feasibility of extending the tool's capabilities to support interactive question-answering features, enabling clinicians to query patient records or receive decision support based on the summarized content.



