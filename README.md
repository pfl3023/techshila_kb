<b>Interview Question Generator and Evaluation Model:</b><br>
This repository contains a Machine Learning model designed to assist in interview preparation by generating interview questions relevant to specific roles. The model leverages web scraping techniques to gather data from relevant websites and utilizes the LMQG Python library for question generation. It also incorporates a database of answers and employs cosine similarity metrics to evaluate the correctness of responses provided by interviewees.<br>

Features:<br>
Web Scraping: Automatically fetches data from pertinent websites to gather information necessary for generating interview questions through <b>beautiful soup 4</b>.<br>

Question Generation: Uses the <b> LMQG Python library</b> to create interview questions based on the scraped data, ensuring relevance and specificity to the role.<br>

Answer Database: Stores a collection of model answers associated with generated questions, enabling evaluation of interviewee responses.<br>

Evaluation Mechanism: Utilizes<b> cosine similarity metrics</b> to assess the similarity between the interviewee's response and the model answer. Responses are tokenized and vectorized using <b>count vectorization</b> techniques for comparison.<br>

Speech Recognition: Incorporates Python's <b>speech recognition</b> library to capture and transcribe interviewee responses for evaluation.<br>

Self-Improvement Process: If the similarity score between the interviewee's response and the model answer is below a certain threshold (0.5 in this case), the model suggests the LMQG-generated answer, thereby facilitating a learning and improvement process.<br>

User-Friendly Interface: Designed for easy use, particularly beneficial for students and individuals preparing for specific role-based interviews who may not have access to a peer group for practice.<br>

Applications<br>
Interview Preparation: Ideal for students and professionals preparing for interviews in specific roles (e.g., consulting case interviews).<br>

Skill Enhancement: Provides a structured approach to practicing interview scenarios, improving interview techniques, and enhancing familiarity with common interview questions.<br>

The model will scrape relevant websites, generate interview questions using LMQG, and store associated model answers.<br>

During the interview simulation, speak your response into the application using the provided speech recognition feature.<br>

The model will compare your response with the stored model answer using cosine similarity. If the similarity score is below 0.5, the model will suggest the LMQG-generated answer for improvement.<br>

Review feedback and suggestions to refine your interview techniques and responses.<br>

Contributions and Feedback<br>
Contributions to enhance the model or its dataset are welcome via pull requests. <br>

By leveraging web scraping, natural language processing, and speech recognition technologies, this model aims to provide a valuable tool for interview preparation, ensuring that users can practice effectively and improve their performance in role-specific interviews.



