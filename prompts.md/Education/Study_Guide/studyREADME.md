# Study Guide Generator
> *Used for creating study guides on specific concepts at school.*
## Overview
This prompt produces a comprehensive guide for students who are struggling with understanding schoolwork or studying for important exams that are coming up. It helps solve the problem of not finding adequate study resources on the internet or at a library.

This would best work for any grade or high school student studying for a class or exam, as the placeholders allow for flexibility for all students. Because of the 
detailed placeholders and how the prompt provides step-by-step guidance for the AI, it could output an effective and comprehensive study guide.

**Best For:**
- Any student with limited access to study resources.
- Last-minute studying for a test.
- Reference when taking notes for class.

**Output:** 
The output of the AI consists of a 3-page maximum guide structured with an introduction and context to the subject, a detailed explanation of the concept, going over
important points of the concept, examples of the concept to give the student a much clearer idea, and ending with a summary of the page.\

The guide will be in a formal style that will also be adapted to the comprehension level of the specified student to make the guide readable and easy to understand.

## Quick Start
### 1. Copy the prompt
Open [`studyprompt.md`](./prompts.md/studyprompt.md) and copy the entire template.
### 2. Fill in placeholders
Replace these with your specific information:
- `[Grade Level]` - You need to put what grade level student you are: 3rd grade, 9th grade, etc.
- `[Subject]` - The main subject that the student needs help with: history, math, etc.
- `[Specific Concept]` - The specific concept that the student needs clarification on within the subject.
### 3. Run in your LLM
Paste into Gemini, Claude, ChatGPT, or your preferred model.
### 4. Review and adapt
Guide the AI using the placeholders so it understands the context and what needs to be output

---
## Example Use Cases
See the `examples/` folder for three complete demonstrations:
1. **[Trigonometric Derivative Study Guide](./examples/Example1.md)** - Gives a study guide for an 11th grade students on trigonometric derivatives in calculus.
2. **[Photosynthesis Study Guide](./examples/Example2.md)** - Gives study guide for 3rd-graders on photosysnthesis and how it works.
3. **[Galvanic Cell Study Guide](./examples/Example3.md)** - Gives study guide for 10th grade students on galvanic cells in AP Chemistry.
Each example shows the filled prompt and resulting output.
---
## Limitations & Considerations
**What This Prompt Does Well:**
- Lays out all important points in a concise manner.
- Helps adapt to the student's comprehension, adding flexibility.
**What Requires Human Judgment:**
- Actual depth of content needed.
- May not always be 3 pages long due to AI errors.
**Always:**
- Make sure the information is understandable and readable for you.
- Be detailed when writing in the placeholders to create the best possible output.
---
## Technical Details
**Framework:** CARE Framework  
**Optimal Model:** Google Gemini  
**Average Response Length:** 3 Pages Long  
**Required Placeholders:** [Subject], [Specific Topic], [Grade Level]  
---
## Version History
**v1.0** (3/1/2026) - Contains placeholders above and the step-by-step AI instructions. 
