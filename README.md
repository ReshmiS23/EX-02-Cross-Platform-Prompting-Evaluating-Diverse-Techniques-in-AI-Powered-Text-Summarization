# EX-02 Cross-Platform Prompting: Evaluating AI Techniques in Text Summarization

## AIM
To evaluate and compare different prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across AI platforms (ChatGPT, Gemini, Claude, Copilot) for the task of summarizing technical articles.

---

## Scenario
You are part of a content curation team for an educational platform. Your task is to generate short, accurate, and student-friendly summaries of a **500-word technical article on "The Basics of Blockchain Technology"** using multiple prompting strategies and platforms.  

The goal is to find which combination of **platform + prompting style** produces the best results in terms of:
- Accuracy  
- Coherence  
- Simplicity  
- Speed  
- User Experience  

---

## Algorithm

1. **Input Preparation**  
   - Select a 500-word article on *The Basics of Blockchain Technology*.  
   - Ensure the article covers definitions, features, principles, and applications.  

2. **Define Prompting Styles**  
   - **Zero-shot** → “Summarize the following article in about 150 words for undergraduate students.”  
   - **Few-shot** → Provide 1–2 example summaries first, then request a blockchain summary.  
   - **Chain-of-Thought** → “Break the article into key points step by step, then write a final summary.”  
   - **Role-based** → “You are a professor. Explain blockchain clearly to beginners in ~150 words.”  

3. **Run Across Platforms**  
   - Use **ChatGPT, Gemini, Claude, and Copilot**.  
   - Apply all four prompting techniques.  
   - Save outputs for evaluation.  

4. **Evaluation Criteria**  
   - **Accuracy** → Are facts correct?  
   - **Coherence** → Does it flow logically?  
   - **Simplicity** → Is it easy to read for students?  
   - **Speed** → How quickly is the output generated?  
   - **User Experience** → Was the platform smooth to use?  

5. **Scoring**  
   - Use **1–5 scale** (1 = Poor, 5 = Excellent).  
   - Record scores in a result table.  
   - Calculate averages for each combination.  

6. **Comparison & Analysis**  
   - Compare results across platforms and techniques.  
   - Identify the **best combination**.  
   - Provide recommendations.  

---

## Results

### Example Observations:
- **ChatGPT Few-shot** → Best for accuracy and detail.  
- **Claude Role-based** → Best for clarity and simplicity.  
- **Gemini Chain-of-Thought** → Strong structure, step-by-step logic.  
- **Copilot Zero-shot** → Fast but sometimes oversimplified.  

---

## Final Result Table

| Platform | Technique       | Accuracy | Coherence | Simplicity | Speed | User Exp. | Avg Score |
|----------|----------------|----------|-----------|------------|-------|-----------|-----------|
| ChatGPT  | Zero-shot      | 4        | 4         | 4          | 5     | 5         | 4.4       |
| ChatGPT  | Few-shot       | 5        | 5         | 4          | 4     | 5         | 4.6       |
| ChatGPT  | Chain-of-Thought | 5      | 5         | 3          | 4     | 5         | 4.4       |
| ChatGPT  | Role-based     | 5        | 5         | 5          | 4     | 5         | 4.8       |
| Gemini   | Zero-shot      | 4        | 4         | 3          | 4     | 4         | 3.8       |
| Gemini   | Few-shot       | 4        | 4         | 4          | 4     | 4         | 4.0       |
| Gemini   | Role-based     | 5        | 5         | 5          | 5     | 4         | 4.8       |
| Claude   | Chain-of-Thought | 5      | 5         | 4          | 4     | 4         | 4.4       |
| Copilot  | Zero-shot      | 3        | 3         | 3          | 5     | 3         | 3.4       |

---

## Conclusion
- **Best Accuracy:** ChatGPT Few-shot & Claude Role-based  
- **Best Simplicity:** Claude Role-based & ChatGPT Role-based  
- **Best Coherence:** Gemini Chain-of-Thought  
- **Fastest:** Copilot Zero-shot  
- **Overall Winner:** Claude Role-based (balanced clarity, simplicity, and accuracy)  

---

## About
Thus the  evaluation for summarization tasks is succesfully implemented.
