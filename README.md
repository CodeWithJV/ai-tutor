*I created this repo as part of the [codewithjv.com](http://codewithjv.com) project. Sign up if you want a weekly email on learning to code using AI assistants or [subscribe on youtube](https://www.youtube.com/@LearnCodeWithJV) for more good stuff.*

# AI Tutor: A custom prompt for creating your personal teacher

This repository provides you with a custom prompt designed to help you learn and practice new skills using ChatGPT. The prompt has been primarily tested with GPT-3.5, and it has been created to:

- Offer clear and specific information about a topic
- Provide lesson plans, with detailed steps and learning objectives
- Teach individual steps, with a mix of theory and practice
- Test your knowledge through a series of questions
- Walk you through practical exercises

## How to Use the Prompt

1. To get started, find the custom prompt in the [init.md](./init.md) ([raw markdown here](https://raw.githubusercontent.com/CodeWithJV/ai-tutor/main/init.md)) file within this repository.

2. Modify the prompt to suit your preferences, ChatGPT can be forgetful so you might want to reinforce some things at the end (such as the use code blocks for lesson plan markdown - it was really resistant to doing that by default).

3. You can now interact with the AI tutor following the guidelines provided in the prompt:

   - To create a lesson plan, ask the tutor "Create a lesson plan for [topic]."
   - To teach an individual step, ask the tutor "Teach me step [number]."
   - To test your knowledge, ask the tutor "Test my knowledge on step [number]."
   - To walk you through practical exercises, ask the tutor "Walk me through practical exercises for [topic]."

4. You can also prefix an instruction before pasting the prompt such as "teach me the fundamentals of coding using python using the following guidelines" which will give you better chat titles

5. You can save lesson plans and reinstantiate a learning session by pasting in the init prompt, then the lesson plan and something like "continue teaching at step 3"

6. ChatGPT can get forgetful over long chat sessions so you can try things like
    - "please print out a summary of our lesson plan"
    - "what is your understanding of the guidelines around ..." creating lesson plans (or teaching, or testing etc.)
    - "please remember your guidelines are ..." (and paste in the entire prompt, or a subsection)

## ChatGPT versions and other LLMs

The prompt tends to work better in GPT 4 but I tend to use it in 3.5 as it is good enough and doesn't use your quota. I only jump into 4 if 3.5 is being painful.

I haven't taken it for a spin on other LLMs, would love to hear how it performs if you do so.

