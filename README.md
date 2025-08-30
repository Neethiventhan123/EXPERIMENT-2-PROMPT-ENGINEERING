# EXP-2-PROMPT-ENGINEERING-

## Aim: 
Comparative Analysis of different types of Prompting patterns and explain with Various Test Scenarios

Experiment:
Test and compare how different pattern models respond to various prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios. 
Analyze the quality, accuracy, and depth of the generated responses.


## Algorithm:
<br>1.Select broad and refined prompting patterns.<br>
<br>2.Choose test scenarios (story, factual, reasoning, summarization).<br>
<br>3.Frame broad and refined prompts for each scenario.<br>
<br>4.Input prompts into the LLM.<br>
<br>5.Record and compare outputs.<br>
<br>6.Evaluate based on clarity, accuracy, and depth.<br>


## Output
| **Scenario**          | **Broad Prompt**       | **Refined Prompt**                                                                                               | **Observation**                                                 |
| --------------------- | ---------------------- | ---------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------- |
| **Story Writing**     | “Write a story.”       | “Write a 200-word story about a child who finds a magical library in school.”                                    | Broad: generic, short; Refined: detailed, creative, structured. |
| **Factual Question**  | “Tell me about AI.”    | “Explain Artificial Intelligence in simple terms, include definition, applications, and one real-world example.” | Broad: vague, incomplete; Refined: clear, accurate, practical.  |
| **Reasoning Problem** | “Solve this puzzle.”   | “Solve step by step: A farmer has 3 goats (2kg/day) and 2 cows (5kg/day). Find grass needed for 7 days.”         | Broad: unclear answer; Refined: shows steps → 56 kg.            |
| **Summarization**     | “Summarize this text.” | “Summarize the passage in exactly 3 bullet points covering only main ideas.”                                     | Broad: incomplete; Refined: concise, structured, accurate.      |

## Result
The experiment demonstrates that prompt clarity directly influences the quality of LLM outputs.
