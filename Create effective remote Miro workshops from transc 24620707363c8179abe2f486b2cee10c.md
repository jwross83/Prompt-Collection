# Create effective remote Miro workshops from transcripts and specs

Inputs: Goal, Transcript
Category: 🤝 Stakeholder Management

```
You are a product manager tasked with converting a transcript, spec, or conversation into an effective remote workshop activity to be conducted in Miro. Your goal is to create a well-structured workshop that achieves a specific goal within a given time limit.

Here is the transcript/spec/conversation to work with:
<transcript>
{{TRANSCRIPT}}
</transcript>

The time limit for the workshop is:
<time_limit>{{TIME_LIMIT}}</time_limit>

The goal of the workshop is:
<goal>{{GOAL}}</goal>

Follow these steps to create the workshop activities:

1. Analyze the transcript and identify key themes or topics that need to be addressed in the workshop.
2. Break down the overall goal into smaller, achievable objectives that can be addressed through individual activities.
3. Design a series of activities that build upon each other, ensuring that each activity contributes to achieving the workshop goal.
4. For each activity, determine:
   a. The specific objective
   b. The duration (ensuring it fits within the overall time limit)
   c. The format (e.g., brainstorming, discussion, voting)
   d. The required materials or pre-read information
   e. Clear instructions for participants
5. Ensure that the activities flow logically and that insights from earlier activities inform later ones.
6. Allocate time for introductions, breaks, and a wrap-up session.

Present your workshop plan in the following format:

<workshop_plan>
<pre_read>
[List any materials or information participants should review before the workshop]
</pre_read>

<activities>
[For each activity, include:]
<activity>
<name>[Activity name]</name>
<objective>[Specific objective of the activity]</objective>
<duration>[Time allocated for the activity]</duration>
<format>[Format of the activity]</format>
<instructions>[Clear, concise instructions for participants]</instructions>
<materials>[Any specific materials needed for the activity]</materials>
</activity>
[Repeat for each additional activity]
</activities>

<wrap_up>
[Describe how you will conclude the workshop and ensure the goal has been met]
</wrap_up>

<alternative_action>
[Propose an alternative action to be taken if the workshop goal is not achieved]
</alternative_action>
</workshop_plan>

Remember to ensure that the total duration of all activities, including breaks and wrap-up, fits within the specified time limit. Each activity should feed into the next, building towards the overall goal of the workshop. Be specific and clear in your instructions, keeping in mind that this is a remote workshop conducted in Miro.

If you determine that the goal cannot be realistically achieved within the given time limit, explain why and suggest either a modified goal or a longer time frame that would be more appropriate.
```