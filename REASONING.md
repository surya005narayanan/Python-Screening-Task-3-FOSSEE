# Reasoning for Choosing Code Llama

## What makes a model suitable for high-level competence analysis?
A model is suitable for competence analysis if it goes beyond checking code correctness and instead evaluates the underlying reasoning a student demonstrates. It should be able to identify misconceptions (e.g., misunderstanding recursion or variable scope), explain why an error occurs, and generate prompts that encourage deeper thought. In education, interpretability and scaffolding are just as important as raw accuracy, since the goal is to guide learning rather than provide direct answers.

## How would you test whether a model generates meaningful prompts?
A meaningful prompt should not simply suggest a solution but instead stimulate reflection. To test this, I would run Code Llama on real or simulated student submissions and check:  
1. Does the prompt highlight the reasoning gap, not just the error?  
2. Does it encourage students to think about alternative cases or consequences (e.g., “What happens when the input is negative?”)?  
3. Does it adjust naturally to different complexity levels, from beginners (syntax, loops) to advanced learners (algorithm design, efficiency)?  
Comparing these outputs with expert educator feedback provides a benchmark for quality.

## What trade-offs might exist between accuracy, interpretability, and cost?
There is often a trade-off between a model’s accuracy in diagnosing code issues, its interpretability for learners, and the computational cost of running it. Larger models may be highly accurate but resource-intensive, making them harder to deploy in classroom settings. Smaller models may be affordable and faster but risk oversimplifying feedback. Interpretability must remain central in education, as opaque or overly technical responses reduce their usefulness for learners and teachers alike.

## Why Code Llama? Strengths and Limitations
I chose **Code Llama** because it is freely available, open-source, and specialized for programming tasks, especially Python. Its strengths include domain expertise, integration with Hugging Face for easy experimentation, and the ability to generate context-aware feedback. However, limitations include occasional verbosity, the risk of over-supplying solutions instead of prompts, and the need for careful prompt engineering to ensure outputs are educationally meaningful. Despite these challenges, Code Llama offers a strong foundation for building competence-oriented tools in coding education, particularly because it balances accessibility with domain specialization.
