# AI_Generalist

* [Playground](#playground)
* [Vibe Coding](#vibe-coding)


## Playground
  ### Random Notes
  * What are .cursorrules files?
  * 

  ### Referenced URLs
  * https://www.youtube.com/watch?v=iLCDSY2XX7E
  * https://docs.google.com/document/d/1cAq3qjgfTISPHP4p_LQALMotCNqh6Y1SBl2GzmD9OmE/
  * 
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

