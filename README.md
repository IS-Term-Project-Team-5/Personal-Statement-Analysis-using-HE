# Personal_Statement_Analysis_using_Homomorphic_Encryption

## Idea Proposal
- It's inevitable that a personal statement for getting a job will contain personal information. (Necessity)
- **Encrypts** and **analyzes** a candidate's personal statement and tells them where they fit into the **top 4 talents** of 18 of Koera's leading IT companies.
- 4 talents: Risk taker, Expertise, Teamwork, Initiative

## Data Description
- 10 example personal statements (Generated through ChatGPT)
- 10 x 4 = 40 personal statements (Label data)

## Flow Diagram
<img width="1075" alt="스크린샷 2024-04-20 오후 12 52 26" src="https://github.com/KangMinsu98/Personal_Statement_HE_Analysis/assets/52079339/8cf12aec-90a7-409c-8b8e-c9b9ab0dd0cf">

1. Vectorize the input personal statement’s text and 130 example personal statements.
2. Encrypt each vector homomorphically.
3. Comparing ‘Cosine Similarity’ between input personal statements and example personal statements. (130 times)
4. Print Highest similar example personal statement and it’s talent

