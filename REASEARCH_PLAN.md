# Research Plan

## Initial Approach
The approach to evaluating open-source models for student competence analysis is to focus on **Code Llama (Python variant)**, an LLM specialized in code understanding and generation. The evaluation will begin by selecting a range of student-written Python code examples that reflect common misconceptions (e.g., incorrect recursion, improper use of loops, and variable scope issues). Using these examples, I will test whether Code Llama can provide reflective prompts instead of direct fixes, thereby encouraging learners to reason through their own mistakes. The criteria for assessment include: 
 - Accuracy in identifying conceptual errors
 - Clarity and relevance of feedback
 - Adaptability across beginner and advanced code samples
 - Interpretability of the model’s reasoning process.  

## Validation
To validate applicability, I will compare Code Llama’s outputs with educator-designed feedback to see how closely they align. Prompts will be rated based on whether they highlight *why* a concept is problematic, rather than just pointing out errors. Additional validation will involve measuring consistency across multiple runs and testing whether the model avoids giving away full solutions. This process ensures that evaluation is both rigorous and educationally grounded, ultimately determining whether Code Llama is a suitable foundation for building tools that assess higher-level student competence in Python learning contexts.
