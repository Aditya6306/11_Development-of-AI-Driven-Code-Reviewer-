# Development of AI-Driven Code Reviewer

## Project Statement
Reviewing code manually for correctness, coding style, and optimization is time-consuming, especially in academic or training environments where students submit large volumes of assignments. This project aims to build an AI-powered tool that automatically reviews student code submissions. The system will check for syntax errors, logical issues, coding style adherence, and suggest optimizations. By combining AI models (GPT API) with Abstract Syntax Tree (AST) parsing, the solution provides detailed feedback to help students improve their coding practices.

---

## Project Outcomes
- **Error Detection:** Identify syntax and logical errors in code.  
- **Coding Style Review:** Highlight deviations from coding standards (e.g., PEP8 for Python).  
- **Optimization Suggestions:** Recommend improvements in performance and readability.  
- **Automated Feedback:** Reduce manual evaluation effort for instructors.  
- **Student-Friendly Tool:** Allow students to paste or upload code and instantly get actionable insights.

---

## Modules

### Module 1: Code Parsing & Preprocessing
- Accept student code in supported languages (start with Python).  
- Parse code using **AST (Abstract Syntax Tree)**.  
- Preprocess code for formatting and readability.

### Module 2: Error & Bug Detection
- Identify **syntax errors** and **undefined variables**.  
- Detect **logical issues** such as unused imports, unreachable code, or infinite loops.  
- Provide **explanations** for detected errors.

### Module 3: Coding Style Analysis
- Check adherence to standard coding guidelines (**PEP8** for Python).  
- Highlight issues like improper indentation, naming conventions, or long functions.  
- Score submissions based on **style compliance**.

### Module 4: Optimization & Best Practice Suggestions
- Use **GPT API** to analyze code for efficiency and readability improvements.  
- Suggest **alternative data structures, algorithmic optimizations, and cleaner patterns**.  
- Provide **before-and-after code snippets** for learning.

### Module 5: Web Application & Feedback Delivery
- Build a **UI** for students to upload/paste code.  
- Display results as categorized feedback (errors, style, optimizations).  
- Allow instructors to track **submissions and feedback history**.

---

## Tools and Libraries
- **Python** – main programming language  
- **AST module** – parse and analyze code structure  
- **OpenAI GPT API** – generate suggestions and feedback  
- **Pandas** – for tabular display (optional)  
- **Flask / Streamlit** – to build the web interface  
- **Pylint / pycodestyle** – for coding style checks

---

## Working Workflow
1. **Input:** Student submits code (via UI or paste).  
2. **Parsing:** Code is parsed using AST to extract structure.  
3. **Error Detection:** Check for syntax and logical errors.  
4. **Style Analysis:** Evaluate code against PEP8 or chosen style guidelines.  
5. **Optimization Suggestions:** GPT API analyzes code for improvements.  
6. **Output:** Feedback is displayed with categorized sections (Errors, Style, Optimization).  
7. **Logging:** Optionally, submissions and feedback can be stored for instructor review.

---

## Expected Results
- Students receive **instant, actionable feedback**.  
- Instructors save **manual evaluation time**.  
- Code quality improves over time as students learn from suggestions.

---

## Future Scope
- Support multiple languages beyond Python.  
- Integrate **unit testing** for automated correctness verification.  
- Add **plagiarism detection** in student submissions.  
- Improve GPT suggestions with **domain-specific knowledge**.  
- Analytics dashboard for instructors to monitor **student progress**.
