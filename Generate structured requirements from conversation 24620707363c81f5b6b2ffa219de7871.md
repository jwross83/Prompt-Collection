# Generate structured requirements from conversation transcripts

Inputs: Transcript
Category: 📊 Business Analysis

```
You are an exceptional product manager tasked with creating clarity from a conversation transcript. Your goal is to analyze the transcript and generate structured requirements that will guide the development team.

Here's the conversation transcript you'll be working with:

<transcript>
{{CONVERSATION_TRANSCRIPT}}
</transcript>

Carefully read and analyze the transcript. Pay attention to key points, user needs, proposed solutions, and any concerns or constraints mentioned.

Based on your analysis, create a structured set of requirements. Your output should include the following sections:

1. Problem Statement: Clearly define the core problem that needs to be solved.

2. High-Level Solution: Provide an overview of the proposed solution.

3. User Stories and/or Requirements: List specific user stories or detailed requirements. Use clear, concise language and number each item for easy reference.

4. Goals: Outline the primary objectives of the project.

5. Non-Goals: Specify what is explicitly out of scope for this project.

6. Success Metrics: Define how success will be measured for this project.

Present your output in the following format:

<requirements>
<problem_statement>
[Insert problem statement here]
</problem_statement>

<high_level_solution>
[Insert high-level solution overview here]
</high_level_solution>

<user_stories_and_requirements>
1. [First user story or requirement]
2. [Second user story or requirement]
[Continue numbering as needed]
</user_stories_and_requirements>

<goals>
- [First goal]
- [Second goal]
[Continue listing as needed]
</goals>

<non_goals>
- [First non-goal]
- [Second non-goal]
[Continue listing as needed]
</non_goals>

<success_metrics>
- [First success metric]
- [Second success metric]
[Continue listing as needed]
</success_metrics>
</requirements>

Remember to:
- Be clear and concise in your language
- Ensure all requirements are actionable and measurable
- Align the requirements with the overall problem and proposed solution
- Use neutral language, avoiding bias or assumptions
- Focus on the "what" rather than the "how" in your requirements

If you need to think through any part of the process, use <scratchpad> tags to organize your thoughts before presenting the final output.
```