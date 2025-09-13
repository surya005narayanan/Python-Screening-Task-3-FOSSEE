# Python Screening Task 3: Evaluating Open Source Models for Student Competence Analysis

This repository explores the potential of using **Code Llama**, an open-source LLM specialized in code understanding and generation, for analyzing student competence in Python.

### The task focuses on:
- Assessing whether Code Llama can analyze student written Python code
- Generating meaningful prompts that probe deeper conceptual understanding
- Identifying misconceptions or reasoning gaps
- Encouraging reflective learning without giving away direct solutions

### Repository Structure
- `REASEARCH_PLAN.md` → 2-paragraph research plan outlining the evaluation strategy
- `REASONING.md` → Detailed reasoning on suitability, testing, and trade offs
- `REFERENCES.md` → References and links to Code Llama resources

### Evaluation Framework

The evaluation of Code Llama for competence analysis is structured around the three supporting files in this repository:

1. **Research Plan (`REASEARCH_PLAN.md`)**  
   Outlines the evaluation approach: running Code Llama on student-written Python code with common misconceptions (e.g., recursion, loops, variable scope). The plan sets criteria such as accuracy of analysis, clarity of prompts, and adaptability across different student levels.

2. **Reasoning (`REASONING.md`)**  
   Defines what makes a model output meaningful. A good evaluation checks whether Code Llama:  
   - Explains why errors exist, not just what they are  
   - Encourages reflection with open-ended prompts.
   - Adapts feedback to beginner vs. advanced learners  

3. **References (`REFERENCES.md`)**  
   Provides grounding in existing research and tools, ensuring that the evaluation is consistent with best practices in AI-in-education. This also serves as a baseline for comparing Code Llama with other models in future work.
   
### Setup Requirements 
No code execution is required for this submission; the plan describes a lightweight harness using unit tests, rubric‑anchored prompts, and instructor ratings for validation, which is standard for evaluating instruction‑tuned code models in an educational setting.

If you later prototype, the Code Llama instruct variants provide clear prompt formats and can run locally or via common platforms; use the instruct/chat templates as documented in the model cards and official guidance for stable results.

### Model Focus and Rationale

Model Focus: Code Llama (Python variant) is designed to understand, generate, and analyze Python code. This makes it a strong candidate for competence-oriented educational tasks.

Rationale: It is free, widely supported, and optimized for reasoning about code rather than just text. Compared to generic LLMs, its specialization in programming reduces irrelevant output and increases its usefulness in evaluating student submissions.

