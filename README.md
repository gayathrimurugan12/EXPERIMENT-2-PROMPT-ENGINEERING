# EXP-2-PROMPT-ENGINEERING-

## Aim: 
Comparative Analysis of different types of Prompting patterns and explain with Various Test Scenarios

Experiment:
Test and compare how different pattern models respond to various prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios. 
Analyze the quality, accuracy, and depth of the generated responses.


## Algorithm:
To implement a Hybrid Prompting System programmatically, we follow a structured algorithm that ensures every user query is enriched with the necessary constraints before reaching the LLM.

Below is the algorithmic breakdown for a Prompt Optimization Engine.

## Hybrid Prompting Algorithm
Algorithm Name: Structured Context Enrichment (SCE)

Objective: Transform a raw user string into a high-precision Hybrid Prompt.

START

Input: Receive User_Query (e.g., "How do neural networks work?").

Persona Assignment:

Identify domain (e.g., IT, Finance, Creative).

Apply SET_PERSONA (e.g., "Senior Data Scientist").

Constraint Injection:

Define Output_Format (e.g., Table, PDF-ready Markdown, Bullet points).

Define Tone (e.g., Professional, Educational).

Define Exclusions (e.g., "Avoid jargon," "No fluff").

Logic Triggering (CoT):

Append STEP_BY_STEP instruction to the instruction buffer to force Chain-of-Thought reasoning.

Prompt Assembly:

Concatenate components: Final_Prompt = Persona + Context + User_Query + Logic_Trigger + Constraints.

Execution: Send Final_Prompt to the LLM.

Post-Processing (Optional):

Verify if the Output_Format matches the constraint.

If failed, re-run with a corrective prompt.

Output: Deliver the high-precision response to the user.

END

## Output
[exp 2 (Gayathri).pdf](https://github.com/user-attachments/files/27194264/exp.2.Gayathri.pdf)


## Result
By implementing this algorithm, we eliminate the "Black Box" effect of AI generation. The
result is a predictable, scalable, and verifiable output suitable for enterprise-level
applications.
