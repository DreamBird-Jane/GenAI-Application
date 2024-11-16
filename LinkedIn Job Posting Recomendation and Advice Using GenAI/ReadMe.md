# LinkedIn Job Posting Recomendation and Advice Using GenAI

This is a hands-on project (using Python) for the lecture "**GenAI with Retrieval-Augmented Generation (RAG) Framework**." 
- You can get the slides from [GenAI with Retrieval-Augmented Generation (RAG) Framework](https://github.com/DreamBird-Jane/GenAI-Application/blob/main/LinkedIn%20Job%20Posting%20Recomendation%20and%20Advice%20Using%20GenAI/RAG%20Framework_20241111.pdf)
- Where to get the codes:
  1. Apart from [DataLab](https://www.datacamp.com/datalab/w/49e3b17b-2c12-4993-a0aa-5e8709e7092f/edit) (using GPT model for demonstration)
  2. You can also get the codes from here [Github](https://github.com/DreamBird-Jane/GenAI-Application/blob/main/LinkedIn%20Job%20Posting%20Recomendation%20and%20Advice%20Using%20GenAI/Build_VectorDB_Retrieval_and_Generation_(Gemini).ipynb) (using Gemini model for demonstration)
     > Note: You can run the Gemini model for free in [Colab](https://colab.research.google.com/) , whereas GPT model need pay-as-you-go.

## Preface
**Goal**: Find your dream job 

**Context**: Job Search Preparation based on the job market trends  

**Strategy**  
- Build an AI Career Consultant who helps job seekers to make strategic plans according to the current job trend
- This AI Career Consultant can:
  1. recommend suitable trending jobs based on your current experiences. E.g., education, abilities, projects, jobs, etc.
  2. provide further advice according to the job recommendation and your experiences

<p align="center">
  <img src="https://github.com/DreamBird-Jane/GenAI-Application/blob/main/LinkedIn%20Job%20Posting%20Recomendation%20and%20Advice%20Using%20GenAI/illustration/Project-Build%20AI%20Career%20Consultant.jpg" alt="Project-Build AI Career Consultant">
</p>


## Prerequisites
What you need to do before running the codes:

1. Application for API Keys: to build our AI assistant, we kneed to apply for keys from the following service providers
    1. Kaggle API: to download data
    1. Hugging Face API: to call embedding model
    1. Gemini API: to call generation model

- Note:
    - keys are sensitive information, do not expose them other than yourself.  
    - Once you have the keys, remember to add them as "Environment Variables"

<p align="center">
  <img src="https://github.com/DreamBird-Jane/GenAI-Application/blob/main/LinkedIn%20Job%20Posting%20Recomendation%20and%20Advice%20Using%20GenAI/illustration/Keys.png" alt="Keys" width="50%">
</p>
     
    
1. Self Description: to provide your brief autobiography for your consultant’s reference
    1. Imagine you’re preparing your resume, what information (texts) should you put? 
      - E.g., education, experience, abilities, personalities, job position you’re looking for, etc.
      - The words (texts only) need not be too long (< 500 words)
