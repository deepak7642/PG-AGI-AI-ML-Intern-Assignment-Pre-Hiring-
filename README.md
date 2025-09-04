# ***PG-AGI AI/ML Intern Assignment Pre Hiring***

### **Assignment Overview -**

*You are tasked with developing an intelligent Hiring Assistant chatbot for "TalentScout," a fictional recruitment agency specializing in technology placements. The chatbot should assist in the initial screening of candidates by gathering essential information and posing relevant
technical questions based on the candidate's declared tech stack. This project will allow you to demonstrate your understanding of LLM’s*

----

### **Built-Up Overview -**

TalentScout is an AI-powered Hiring Assistant chatbot designed to streamline the recruitment process. It interacts with candidates in a conversational style, collects their personal and technical details, and generates tailored interview questions based on their declared tech stack.

*Key Capabilities:*

* Collects candidate details (name, email, experience, role preference, etc.) in a conversational flow.
* Supports multilingual interaction (English + Hindi).
* Uses LLM-powered prompt templates to generate tailored, technical interview questions based on the candidate’s declared tech stack.
* Performs sentiment analysis on candidate responses during the chat, mapping them into interview-style impressions (Confident, Neutral, Uncertain).
* Provides a final summary with per-question sentiments and an Overall Impression (Strong, Balanced, Needs Clarity).

### **Usage Guide**

* Start the chatbot using the instructions above.
* When the app loads, you’ll see a chat interface with a welcome message.
* The bot first asks you to choose a language (English or Hindi).
* Then it will ask for details step by step:
   * Full Name
   * Email
   * Phone
   * Years of Experience
   * Desired Position
   * Location
   * Tech Stack

* After collecting inputs, the bot will:
  * Generate one interview question per technology in your tech stack (English or Hindi).
  * Show a sentiment summary of your answers.
  * Provide an overall impression (Strong, Balanced, Needs Clarity).

 ------

### **Demo of TalentScout Hiring Assistant -**


 

### **Future Work**

* Enhanced Multilingual Support
   * Extend beyond Hindi & English to cover more Indian regional languages (e.g., Tamil, Bengali, Marathi) to make the hiring process inclusive.

* Advanced Sentiment & Personality Analysis
  * Replace the basic Hugging Face sentiment model with multi-class emotion & personality trait analysis (e.g., Big Five traits).
  * Provide recruiters with deeper insights into communication style (assertive, hesitant, detail-oriented).
    
* Downloadable Candidate Reports
  * Generate PDF or Word summaries of candidate details, interview questions, and sentiment analysis.
  * Useful for recruiters to keep structured candidate records.

* Data Privacy & Secure Storage
   * Instead of sending candidate data to third-party systems, securely store user inputs in a local database (e.g., SQLite, PostgreSQL) or even CSV files.
   * Ensures data remains private, under recruiter’s control, and compliant with data protection laws.

* Adaptive Questioning
  * Use real-time analysis of confidence & sentiment to adjust question difficulty dynamically.
  * Example: If the candidate is confident, escalate to advanced-level questions.

* Scoring & Recommendation System
  * Assign candidates a readiness score (e.g., 7.5/10) based on experience, sentiment, and answers.
  * Provide recruiters with shortlisting recommendations.

**Note -** *This Project runs entirely on CPU, No API key required and Zero deployment overhead – Built using Gradio, Also ensuring the solution is highly scalable, adaptable, and future-ready for enterprise demands*
