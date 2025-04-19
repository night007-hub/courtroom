# courtroom
#  Agent of Justice - Intelligent Courtroom Simulation

Welcome to **Agent of Justice**, a simulation of a real courtroom built using ai

This project was created as part of my induction task, blending AI reasoning, memory, and role-playing to mimic the different characters in a courtroom – from judges and prosecutors to witnesses and defendants.

---

##  Features

-  **Multiple LLM-powered agents** with memory (Judge, Prosecutor, Defense Lawyer, Witness, Defendant, Jury)
-  **Role-based responses** using Groq (LLaMA 3.3 70B) and HuggingFace (Flan-T5)
-  **Structured simulation** with:
  - Opening statements
  - Witness testimony
  - Cross-examinations
  - Closing arguments
  - Final verdict & jury evaluation
-  **Data-driven**: Automatically loads a real case from a CSV file
-  **Memory-enabled context**: Each agent remembers past conversation snippets for realistic flow

---

##  Tech Stack

-  Python 3
-  [Groq API](https://groq.com/)
-  Hugging Face Transformers + Inference Client
-  Pandas
-  LLaMA 3.3 70B + Flan-T5 base

---

##  File Structure
├── Agent_of_Justice.ipynb      # Main notebook
├── data.csv                    # Dataset containing real courtroom cases
├── README.md                   # This file


## How to Run
Open in Google Colab
Mount Google Drive
Install required libraries
Provide your HuggingFace token
Add your Groq API key
Run the simulation

## sample output
============== case type ====================
Judge: opens court and summarizes
Prosecutor: accusation
Defense: opening defense
Witness: testimony
Cross-Examination: smart response
Verdict: judge final verdict
Jury: [Conclusion]


## author
Adithya
B.Tech CSE, IIT Indore
Passionate about AI, reasoning, and simulation.

