# AI_Generalist

* [Playground](#playground)
* [Vibe Coding](#vibe-coding)
* [Prompt Engineering](#prompt-engineering)
* [AI Agents](#ai-agents)


## Playground
  ### Random Notes
  * What are .cursorrules files?
  * 

  ### Referenced URLs
  * https://www.youtube.com/watch?v=iLCDSY2XX7E
  * https://docs.google.com/document/d/1cAq3qjgfTISPHP4p_LQALMotCNqh6Y1SBl2GzmD9OmE/
  * https://youtu.be/ASABxNenD_U?si=COZ7aKJVcN4YxggU
## Vibe Coding

  ### Step-Wise Learning
  * Define
  * Principles
  * Info using Replit and Windsurf
  * Practical Tips

  #### Define
  * The term "Vibe Coding" was coined by **Andrej Karparthy**.
  * **His Definition** -  There's a new kind of coding I call **"vibe coding"** where you fully give in to the vibes, embrace exponentials, and forget that the code even exists. It's possible because the LLMS(e.g., Cursor Composer W Sonnet) are getting too good. Also, I just talked to Composer with **SuperWishper**, so I barely even touched the keyboard. I ask for the dumbest things, like "decrease the padding on the sidebar by half" because I'm too lazy to find it. I "Accept All" always, I don't read the diffs anymore. When I get error messages, I just copy and paste them in with no comment. Usually, that fixes it. The code grows beyond my usual comprehension; I would have to really read through it for a while. Sometimes the LLMs can't fix a bug, so I just work around it or ask for random changes until it goes away. It's not too bad for throw-away weekend projects, but still quite amusing. I'm building a project or web app, but it's not coding - I just see stuff, say stuff, run stuff, and copy and paste stuff. And it mostly works.

#### Principles
  * Fundamental course - Vibe Coding 101 with Replit https://www.deeplearning.ai/short-courses/vibe-coding-101-with-replit/
  * The course explains that there are 5 fundamental skills in vibe coding there are -
    * Thinking
    * Framework
    * Checkpoints
    * Debugging
    * Context

  ##### Thinking    
  * Four types of thinking should go into vibe coding
    * Logical Thinking - What is the game?
    * Analytical Thinking - How do I play this game? What is the main objective and goal of this game?
    * Computational Thinking - How to fit the logic of the game into a complicated set of problems? How do you enforce these rules?
    * Procedural Thinking - How do I excel in this game? We will think about strategies and boundaries of the game so that you are able to program your computer to be able to do well in the game.
    *  Of course, we need to translate this natural language that we describe and communicate that to the AI to build.
    *  We need to think clearly about how to properly communicate with AI and describe whatever we want to build to it.
    *  We need to build a PRD - Product Requirements Document.
   
##### Framework
  * Know and list the packages and frameworks AI to use. 
  * If you do not know what to use, you can ask AI to suggest based on your requirements.
  * Example prompt is like - "Could you help me come up with some React frameworks to implement, drag and drop into this application, and then implement it?"
  * three.js is a package for animation.
##### Checkpoints
  * Replit has a built-in version control
  * Git - version control software, GitHub - a website that allows one to store their code, their repositories on the cloud.

##### Debugging
  * learn the art of debugging
##### Context  
  * Provide as much information as possible to AI to build better and debug better, such as Detailed Prompt, PRD, Provide Mock-Ups, Provide Additional Data(examples, extra data, details about app, your environment, your preferences, Errors).
  * The more details we provide to the AI, the better results we get from it.

#### Info using Replit and Windsurf
  * There are several AI Code builders. For example, we have cloud-based app builders such as Replit, Bolt, Lovable, and AI code editors such as Cursor, Windsurf.
#### Tips
  * Start small and work your way up. First, perfect the MVP, then build on it.
  * Do not try to build everything in the beginning; do not complicate the process.
    * **When you are implementing a new feature**
    *  Provide relevant context
    *  Mention frameworks
    *  Provide documentation with explicit details
    *  Making incremental changes
    *  Doing the checkpoints
    *  Version control
    *  **When you are debugging Errors**
    *  Figure out how things work
    *  How to get it unstuck from LLM
    *  Provide as much information as you can
  * Write Rule Files
    * Limit code changes to the minimum
    * Rate limit all API endpoints
    * Enable captcha
    * Do not expose API keys
    * **Prompt Generation Rules:**
    * Analyze the component requirements thoroughly
    * Include specific DaisyUI component suggestions
    * Specify desired Tailwind CSS classes for styling
    * Mention any required TypeScript types or interfaces
    * Include instructions for responsive design
    * Suggest appropriate Next.js features if applicable
    * Specify any necessary state management or hooks
    * Include accessibility considerations
    * Mention any required icons or assets
    * Suggest error handling and loading states
    * Include instructions for animations or transitions if needed
    * Specify any required API integrations or data fetching
    * Mention performance optimization techniques if applicable
    * Include instructions for testing the component
    * Suggest documentation requirements for the component
    * **General Component Creation Guidelines:**
    * Prioritize reusability and modularity
    * Ensure consistent naming conventions
    * Follow React best practices and patterns
    * Implement proper prop validation
    * Consider internationalization requirements
    * Optimize for SEO when applicable
    * Ensure compatibility with different browsers and devices
    * **General Rules:**
    * Enable strict TypeScript (strict: true in tsconfig.json)
    * Avoid ‘any’, prefer ‘unknown’ with runtime checks
    * Explicitly type function inputs and outputs
    * Use advanced TypeScript features (type guards, mapped types, conditional types)
    * Organize project structure: components, pages, hooks, utils, styles, contracts, services
    * Separate concerns: presentational components, business logic, side effects
    * Use Biome for code formatting and linting
    * Configure Biome as a pre-commit hook

## Prompt Engineering
```
Prompting is an iterative approach; you are not going to come up with a perfect prompt as per your desired output in the beginning.

Always critically evaluate LLMs' output using a few guiding questions
* Is the output accurate?
* Is the output unbiased?
* Does the output include sufficient information?
* Is the output relevant to my project or task?
* Is the output consistent if I use the same prompt multiple times?

```
  ### Pro Tips
  * Give a clear, specific prompt with context
  * Always think about how your output should look and be as specific as possible to achieve that.
  * Ask it to include the sources
  * After getting the desired output with the iterative prompts, prompt the AI to 
``` Write a single prompt to get the output we finally have ``` 
It will help us prompt next time and understand how it is expecting the prompt should be to get the desired output.
  * In AI terminology, the word "Shot" is the same as the word "Example"
    * Zero-shot prompting - prompt with no example.
    * One-shot prompting -  prompt with one example.
    * Few-shot prompting - prompt with more than one example.
  * LLMs are good at pattern recognition, given examples to give it how your output should look like, it is very good at mimicking it.

  ### Examples
  * Give a good pizza place in Hamburg - decent prompt, but lacks context. 
            to make it better, give it a context like 
```
I'm in the mood for Italian cuisine, particularly a good pizza in a laid-back, cosy environment. Give me a recommendation for Hamburg city
```
If you want to compare the prices in a tabular format, you may add
```
Create a table format and divide the restaurants by restaurant name, price point, description, and popular food."
```
* Another example is summarize - 
```
The following text is an email from a software vendor, summarise its main points in a bulleted form.
```
* Classify
```
Read these customer reviews and classify whether the sentiment for the review is positive, negativ,e or neutral
```
* Extract
```
Read the blog post below and extract all the references to items and clothing I can buy, and how much each item would cost. Create a bulleted list of just these items
```
* Translation
```
Translate our product descriptions from English to Spanish. Maintain the same structure and casual tone that is used in the English version in the Spanish translation
```
* Editing
```
Read the language of the following paragraph, so that it's easy for a general audience to understand it
```
* Problem Solving
```
We are running a community program to teach children garden skills. The program runs from June 1st to August 15th, and we want the children to be able to grow plants that will be ready to harvest by the time the program ends.
First, identify a list of 10 plants that can be planted and grown in that period. Include sources that support the time to harvest for each plant.
We want the children to grow these plants. These Be as different from each other as possible. So, next choose three plants from the list that will provide the children with this variety.
```
* Few Shot Prompting Example
```
Write a sentence description of a product. It should contain two adjectives that describe the product. Read the examples and write a description of a skateboard in the same style.
Example 1: 
Bicycle: Whether you're exploring city streets or forest paths, our sleek and durable bicycle has it all.
Example 2: 
Rollerblades: Roll into summer in style with our smooth and stylish roller blades
```
* **Chain of thought prompting** - divide a large task into smaller tasks
Here’s an example of how to design a chain-of-thought prompt for a task at work. Consider an organization with thousands of employees. Each employee is assigned a unique purchasing code that can be used for buying supplies or equipment. First, a technical support specialist creates a unique purchasing code for each employee. To do so, the specialist uses a custom AI solution, approved for use with company and employee information, to help them create the purchasing code with the following chain-of-thought prompt:
```
 Our organization assigns purchasing codes by combining an employee’s department and ID number. All alphabetic characters are lowercase in the purchasing code. Review the examples and then answer the question that follows in the same manner. Explain the steps involved in determining each employee’s purchasing code.
Question: Tiana B works in the Marketing department and has an ID number of 9283. What is Tiana B's purchasing code?

Answer: The purchasing code for Tiana B is marketing9283. To determine this, first combine the department (Marketing) with the ID number (9283). This results in Marketing9283. Then, change all alphabetic characters to lowercase. This creates the purchasing code marketing9283.
```

## AI Agents
```
An AI Agent is a software program that can act autonomously to achieve specific goals, making decisions, and taking actions based on its environment and data.
```
* **As per OpenAI, six components make up an AI Agent.**
  * Models - An AI model itself (provides intelligence)
  * Tools - to interact and access different information (Enable Action)
  * Knowledge and Memory - access to a specific database and previous memory (informs decisions)
  * Audio and Speech - ability to interact (Enables natural interaction)
  * Guardrails - a system to keep the AI Agent in check (Ensures Safety)
  * Orchestration - processes that allow you to deploy the AI Agent in specific environments, monitor them, and also improve them over time. (Manages them all).
* **Examples of AI Agents**
  * Virtual Assistants - Siri, Alexa, Google Assistant
  * Chatbots - on websites
  * Self-driving cars - decide where to turn or stop all by themselves.
  * Recommendation Systems - like on YouTube or Netflix, which suggest shows or videos you might like.
* **Tools to develop AI Agent**
  * n8n is good for beginner friendly, general usecase
  * Gumloop is good for enterprise usecases.
  * TODO: if you know how to code, checkout OpenAI Agent's SDK
  * Google's ADK (Agent Development Kit) is free.
  * Claude Code SDK is specific for coding agents.   
