[![Developed by Mad Devs](https://maddevs.io/badge-dark.svg)](https://maddevs.io?utm_source=github&utm_medium=shared_cursor_rules)

# Cursor Rules Templates

These templates are based on [awesome-cursorrules](https://github.com/PatrickJS/awesome-cursorrules)

## Rules structure 
The `rules` directory contains ready-to-use cursor rules.

📁 **generic** - general rules for any tech stack
  - 📁 **must-have** - mandatory rules for all company projects
  - 📁 **optional** - optional rules, use as needed

📁 **specific** - examples for specific tech stacks

📁 **project-rules** - examples of rules for individual projects

📁 **user-rules** - examples of personal rules (apply to all your projects)

## Using prompt templates

The `prompt-templates` directory contains ready-to-use prompts

- 📁 **rules** - prompts to help create, adapt, and work with rules
- 📁 **documentation** - prompts to help generate documentation
- 📁 **other**

### How to use prompts:

1. **Copy and paste**
2. **Customize placeholders** like `[your tech stack]` with your specific information
3. **Refine as needed**

These prompts serve as starting points to help you get the most out of LLM

---

## Rules quick start

1. Copy rules from `generic/must-have` and selectively from `generic/optional` and `specific`
2. Paste them into `.cursor/rules` of your project
3. Customize the rules for your project:
   - Rules from `generic/must-have` can be adapted, but it's important to preserve their essence. For us, it's crucial that all company projects are based on unified principles.
   - Rules from `generic/optional` and `specific` can be completely changed
4. Don't hesitate to **ask AI to adapt the rules for your project**
5. Study `project-rules` and create custom rules for your project
6. Check out `user-rules` and create personal rules (they are added to `Cursor settings → Rules → User rules`)

---

## Example prompts for implementing Cursor rules

### For familiarizing with rules
```
Read all rules in the `.cursor/rules` directory and confirm that you understand them.
Briefly summarize the essence of each rule and how you will apply them in your work.
Confirm that you will never ignore these rules.
```
[View Template](prompt-templates/rules/force-ai-to-read-rules.txt)

### For adapting rules to a project
```
Study the rules in `.cursor/rules/{rule}` and adapt them for the project [your project description].
Consider that we use [your tech stack], and the team consists of [team description].
It's important to preserve the essence of must-have rules, but they can be improved.
```
[View Template](prompt-templates/rules/adjust-rules.txt)

### For creating custom project rules
```
Create rules for the project considering the following features:
1. Tech stack: [your stack]
2. Architecture: [architecture description]
3. Main problems we want to solve: [problems]
4. Our core values in code: [values]
5. Approach to task execution: [typical action algorithm]
```
[View Template](prompt-templates/rules/create-rules.txt)

### For creating personal rules
```
Help create personal rules for the AI agent considering my work style:
1. I prefer [your programming preferences]
2. Often work with [technologies/libraries]
3. It's important for me that code is [your code priorities]
4. Usually face difficulties with [problem areas]
5. What should NEVER be done [prohibitions]
```
[View Template](prompt-templates/rules/create-rules-personal.txt)

### For writing comprehensive README files
```
Write a clear, concise README for this project that follows industry best practices and includes:

1. Project title and brief description (1-2 sentences)
2. Problem the project solves
3. Key features (bullet points)
4. Technologies/frameworks used
5. Installation instructions with prerequisites and step-by-step setup
6. Basic usage examples with code snippets
7. Project structure overview (only key directories/files)
8. Configuration options
9. Contribution guidelines (if applicable)
10. License information
11. Credits/acknowledgments
```
[View Template](prompt-templates/documentation/write-readme.txt)

---

## Setting priorities

To change the rule application mode:
1. Open the rule file
2. Click on the dropdown `Rule type`
3. Select the appropriate option

### Tips for effective rules:

✅ Use a small number of rules  
✅ Keep files short (up to 100 lines)  
✅ Avoid contradictions between rules  
✅ Set `Rule type: Always` only for critically important rules  
✅ At the beginning of the chat, ask AI to read the rules and summarize their essence

---

If AI ignores the rules, it means there are too many of them or they are not effectively written.

> **Found a way to improve the rules?** Make a PR, we'll be happy ❤️
