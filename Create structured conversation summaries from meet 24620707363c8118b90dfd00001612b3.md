# Create structured conversation summaries from meeting transcripts

Inputs: Transcript
Category: 📅 Project Management

```
You will be summarizing a conversation and identifying specific actions. The conversation will be provided to you in the following format:

<conversation>
{{CONVERSATION}}
</conversation>

Your task is to create a comprehensive summary of the conversation using nested bullet points. Follow these steps:

1. Read through the entire conversation carefully.

2. Create a high-level summary using main bullet points for major topics or themes discussed.

3. Under each main bullet point, use sub-bullets to provide more detailed information or specific points related to the main topic.

4. Continue nesting bullets as needed to capture the hierarchy and relationship between ideas.

5. While summarizing, identify specific actions that need to be taken. For each action:
   a. Clearly state what the action is
   b. Specify who needs to take the action
   c. Use bold text to make the action stand out (use ** before and after the text to make it bold)

6. For each action identified, break it down into simple, manageable steps for someone with ADHD. Use a numbered list for these steps, keeping each step concise and clear.

Here's an example of how your output should be structured:

<summary>
• Main topic 1
  ◦ Subtopic 1.1
    ▪ Detail 1.1.1
    ▪ Detail 1.1.2
  ◦ Subtopic 1.2
    ▪ Detail 1.2.1
      - Sub-detail 1.2.1.1

• Main topic 2
  ◦ Subtopic 2.1
    ▪ **Action: [Description of the action]**
    ▪ **Who: [Person responsible]**
    ▪ Steps for ADHD individuals:
      1. First step
      2. Second step
      3. Third step

  ◦ Subtopic 2.2
    ▪ Detail 2.2.1
</summary>

Remember to use clear and concise language throughout your summary. Ensure that the nested structure accurately reflects the relationships between ideas in the conversation. When breaking down actions for ADHD individuals, focus on creating simple, actionable steps that are easy to follow.

Please provide your summary within <summary> tags.
```