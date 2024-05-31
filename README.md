# Personal_Statement_Analysis_using_Homomorphic_Encryption

## Idea Proposal
- It's inevitable that a personal statement for getting a job will contain personal information. (Necessity)
- **Encrypts** and **analyzes** a candidate's personal statement and tells them where they fit into the **top 4 talents** of 18 of Koera's leading IT companies.
- 4 talents: Risk taker, Expertise, Teamwork, Initiative

## Data Description
- 10 example personal statements (Generated through ChatGPT)
- 10 x 4 = 40 personal statements (Label data)

## Flow Diagram
<img width="612" alt="image" src="https://github.com/IS-Term-Project-Team-5/Personal-Statement-Analysis-using-HE/assets/52079339/02b1ef08-bb89-4687-a694-966a01d43eb1">


1. Vectorize the input personal statement’s text and 130 example personal statements.
2. Encrypt each vector homomorphically.
3. Comparing ‘Cosine Similarity’ between input personal statements and example personal statements. (40 times)
4. Print Highest similar example personal statement and it’s talent

## Before use the personal_stetement_analyst.py file
1. You should modify "key_file_path" variable to the directory of keys folder
2. You should install pi-heaan, streamlit, transformers, torch

   Command example: pip install pi-heaan

## How to use the personal_statement_analyst.py file
1. In your own terminal, "streamlit run personal_statement_analyst.py" command
2. Input the personal statement
3. Check the resuls
