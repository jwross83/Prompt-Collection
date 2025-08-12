# Generate product assumptions from core strategy inputs

Inputs: Problem, Product, Target Audience
Category: 🔍 User Research

```
You are tasked with creating a comprehensive list of assumptions underlying a product strategy. This list will cover assumptions across desirability, feasibility, viability, and usability. Follow these instructions carefully to complete the task:

1. Review the following information about the product:

<product_description>
{{PRODUCT_DESCRIPTION}}
</product_description>

<core_problem>
{{CORE_PROBLEM}}
</core_problem>

<target_user>
{{TARGET_USER}}
</target_user>

2. Brainstorm assumptions for each of the following categories:

a) Desirability Assumptions (Customer/User)
b) Feasibility Assumptions (Technical/Operational)
c) Viability Assumptions (Business/Financial)
d) Usability Assumptions (Design, UX)

For each category, consider relevant questions such as those provided in the original task description. Generate at least 5 assumptions per category.

3. For each assumption you generate, provide the following information:

- Assumption statement: Begin with "We believe that..."
- Category: Specify whether it's a Desirability, Feasibility, Viability, or Usability assumption
- Impact if wrong: Briefly describe what would happen if this assumption turns out to be false

4. Format your output as follows:

<assumptions_list>
<category>Desirability Assumptions</category>
<assumption>
<statement>We believe that...</statement>
<impact>If this is false,...</impact>
</assumption>
[Repeat for each assumption in this category]

<category>Feasibility Assumptions</category>
[Repeat structure for Feasibility assumptions]

<category>Viability Assumptions</category>
[Repeat structure for Viability assumptions]

<category>Usability Assumptions</category>
[Repeat structure for Usability assumptions]
</assumptions_list>

5. After listing all assumptions, provide a brief summary of the key themes or patterns you've identified across the assumptions.

<summary>
[Your summary here]
</summary>

Your final output should consist only of the <assumptions_list> and <summary> sections. Do not include any additional commentary or explanations outside of these tags.
```