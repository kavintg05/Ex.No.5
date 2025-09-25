

# EXP 5: COMPARATIVE ANALYSIS OF DIFFERENT TYPES OF PROMPTING PATTERNS AND EXPLAIN WITH VARIOUS TEST SCENARIOS

# Aim: To test and compare how different pattern models respond to various prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios.  Analyze the quality, accuracy, and depth of the generated responses 

### AI Tools Required: 

# Explanation: 
Define the Two Prompt Types:

Write a basic Prompt: Clear, detailed, and structured prompts that give specific instructions or context to guide the model.
Based on that pattern type refined the prompt and submit that with AI tool.
Get the ouput and write the report.

Prepare Multiple Test Scenarios:
Select various scenarios such as:
Generating a creative story.
Answering a factual question.
Summarizing an article or concept.
Providing advice or recommendations.
Or Any other test scenario
For each scenario, create both a naïve and a basic prompt. Ensure each pair of prompts targets the same task but with different levels of structure.
Run Experiments with ChatGPT:
Input the naïve prompt for each scenario and record the generated response.
Then input the corresponding basic prompt and capture that response.
Repeat this process for all selected scenarios to gather a full set of results.
Evaluate Responses : 
	Compare how ChatGPT performs when given naïve versus basic prompts and analyze the output based on Quality,Accuracy and Depth. Also analyse does ChatGPT consistently provide better results with basic prompts? Are there scenarios where naïve prompts work equally well?
Deliverables:
A table comparing ChatGPT's responses to naïve and basic prompts across all scenarios.
Analysis of how prompt clarity impacts the quality, accuracy, and depth of ChatGPT’s outputs.
Summary of findings with insights on how to structure prompts for optimal results when using ChatGPT.


# OUTPUT

## EXP 5: COMPARATIVE ANALYSIS OF DIFFERENT TYPES OF PROMPTING PATTERNS

---

## Aim
The objective of this experiment is to test and compare how ChatGPT responds to two different types of prompting strategies — **naïve prompts** (broad/unstructured) and **basic prompts** (clear, refined, and structured).  
The study evaluates the **quality, accuracy, and depth** of generated responses across multiple real-world scenarios. The ultimate goal is to understand how prompt engineering affects the usefulness of AI-generated outputs.

---

## AI Tool Required
- **ChatGPT (GPT-5 or equivalent AI model)**  
  Used as the test model for generating responses and evaluating prompt clarity.

---

## Explanation of Prompt Types

### 1. Naïve Prompt
- Broad, vague, or unstructured instructions.  
- Provides little to no guidance to the AI.  
- Relies heavily on the model’s internal assumptions and defaults.  
- **Example:**  
  *“Write me a story.”*

### 2. Basic Prompt (Refined Prompt)
- Clear, detailed, and structured instructions.  
- Guides the model with context, constraints, and desired outcomes.  
- Helps the model stay relevant and focused.  
- **Example:**  
  *“Write a 300-word creative story about a boy who discovers a hidden library in his school basement. Focus on suspense and mystery.”*

---

## Methodology

1. **Prompt Type Identification:**  
   Defined two categories of prompts: naïve and basic.

2. **Scenario Selection:**  
   Designed **four experimental scenarios** covering both creative and factual domains:  
   - Creative Story Generation  
   - Factual Question Answering  
   - Summarization Task  
   - Advice/Recommendation  

3. **Experiment Execution:**  
   - Asked ChatGPT the **naïve prompt** for each scenario.  
   - Recorded the generated response.  
   - Asked ChatGPT the **basic (refined) prompt** for the same task.  
   - Recorded the refined response.  

4. **Evaluation Metrics:**  
   Each response was evaluated based on three criteria:  
   - **Quality**: Coherence, structure, and readability.  
   - **Accuracy**: Correctness of facts and relevance of information.  
   - **Depth**: Detail, richness, and comprehensiveness of the response.  

5. **Comparison:**  
   Created comparative tables summarizing results for each scenario.

---

## Test Scenarios & Results

### Scenario 1: Creative Story Generation
| Prompt Type | Prompt | Response (Summary) | Evaluation |
|-------------|--------|---------------------|------------|
| Naïve | *“Write me a story.”* | A short, generic story about a boy who went on an adventure. Minimal detail, no clear theme or climax. | Quality: Low, Accuracy: Neutral, Depth: Low |
| Basic | *“Write a 300-word story about a boy discovering a secret library in his school basement. Use suspense and mystery.”* | A well-structured, suspenseful story with vivid descriptions, mysterious atmosphere, characters, and a strong ending. Word count respected. | Quality: High, Accuracy: Good, Depth: High |

---

### Scenario 2: Answering a Factual Question
| Prompt Type | Prompt | Response (Summary) | Evaluation |
|-------------|--------|---------------------|------------|
| Naïve | *“Tell me about the Sun.”* | A vague 3–4 line explanation: “The Sun is a star that provides light and heat.” Very generic. | Quality: Medium, Accuracy: Correct but minimal, Depth: Low |
| Basic | *“Explain the Sun in detail, including its structure, composition, life cycle, and importance for Earth.”* | A comprehensive explanation: structure (core, photosphere, corona), nuclear fusion process, hydrogen–helium composition, life cycle stages, and role in sustaining life on Earth. | Quality: High, Accuracy: Strong, Depth: High |

---

### Scenario 3: Summarization Task
| Prompt Type | Prompt | Response (Summary) | Evaluation |
|-------------|--------|---------------------|------------|
| Naïve | *“Summarize climate change.”* | A 2–3 sentence general summary: “Climate change means rising global temperatures, ice melting, and unpredictable weather.” | Quality: Medium, Accuracy: Partial, Depth: Low |
| Basic | *“Summarize climate change in ~150 words, covering causes, effects, and possible solutions.”* | A balanced summary explaining greenhouse gases, global warming, rising sea levels, biodiversity impacts, and proposed solutions like renewable energy, reforestation, and sustainable living. | Quality: High, Accuracy: High, Depth: Medium–High |

---

### Scenario 4: Advice/Recommendation
| Prompt Type | Prompt | Response (Summary) | Evaluation |
|-------------|--------|---------------------|------------|
| Naïve | *“Give me study tips.”* | A generic 3-point list: “Stay focused, take breaks, avoid distractions.” | Quality: Medium, Accuracy: Basic, Depth: Low |
| Basic | *“Give 5 effective study strategies for engineering students preparing for exams, including time management, note-taking, and revision methods.”* | Detailed strategies: Pomodoro technique for time management, active recall, spaced repetition, mind mapping for notes, and practice problem-solving. Tailored to engineering students. | Quality: High, Accuracy: High, Depth: High |

---

## Extended Analysis

1. **Impact of Prompt Clarity:**
   - Naïve prompts led to short, surface-level responses that lacked depth.  
   - Basic prompts, with structured requirements, consistently resulted in more comprehensive and relevant answers.  

2. **Quality Differences:**
   - Naïve responses were often **generic, repetitive, and lacking creativity**.  
   - Basic prompts improved storytelling, factual richness, and targeted advice.  

3. **Accuracy:**
   - While naïve prompts sometimes produced factually correct outputs, they were incomplete.  
   - Basic prompts forced the model to include **specific factual details**, improving correctness.  

4. **Depth & Usefulness:**
   - Naïve prompts provided minimal usable content for professional or academic use.  
   - Basic prompts produced responses closer to **ready-to-use material** (reports, study notes, summaries).  

5. **Notable Observation:**
   - For simple casual tasks (e.g., “Tell me a joke” or “Write a riddle”), naïve prompts worked fine.  
   - For academic, professional, or structured tasks, **basic prompts were essential** for high-quality results.  

---

## Summary of Findings

1. **Naïve Prompts**
   - Result in short, shallow, and sometimes generic responses.  
   - Useful for casual interactions but not suitable for academic/professional tasks.  

2. **Basic Prompts**
   - Produce structured, coherent, and context-rich answers.  
   - Higher accuracy and depth compared to naïve prompts.  
   - Better suited for **detailed explanations, creative writing, and tailored advice**.  

3. **General Conclusion**
   - Prompt clarity directly influences the quality of AI outputs.  
   - Well-structured prompts = better answers.  
   - Users should **include context, constraints, and expected outcomes** in prompts to maximize the utility of ChatGPT.  

---

## Final Best Practices for Prompting
- **Be Specific:** Always specify the task, format, and details.  
- **Give Context:** Explain background or target audience.  
- **Set Constraints:** Word count, tone, style, or structure.  
- **Use Action Words:** Start prompts with *“Explain,” “Summarize,” “List,” “Write a story,” “Compare,”* etc.  
- **Iterate:** Refine prompts if the first output is unsatisfactory.  

---

✅ **Conclusion:**  
Basic (refined) prompts consistently provide better results in terms of **quality, accuracy, and depth** compared to naïve prompts. This experiment highlights the importance of prompt engineering when using AI tools like ChatGPT for academic, professional, or creative purposes.
 

# RESULT: The prompt for the above said problem executed successfully
