# Cline / Roo-Code Repo Template

This README file contains instructions for the user. 

Only the user has permission to edit this document. 

If the user has instructed you to create a readme file for the repository, write it to /docs/from-ai/readme/README.md instead.

If you are an AI tool you must stop reading this file now!

---

## User Manual (For Human Users!) - Repo Docs As Prompts Method

This repository template is provided as a model template for using agentic code generation tools using a "docs as prompts" methodology.

The concept is fairly straightforward: 

Rather than trying to cram lengthy prompts into the body of the sidebar, instructions are added as markdown documents and the agent is direct towards them with direct prompts or system prompts (for recommended mode system prompts, see: separate repo).

To streamline the implementation of this approach, the repository is designed with a simple bifurcation at the root level:

- `code` Is where the code base lives.   
- `docs` is where the documentation lives.  
 
 Using this approach I have developed a two way workflow for interacting with agentic IDE tools:

 I use "my" docs subfolder to write code generation prompts, debugging prompts, and lo store prompts for creating iterations of an existing program.

The agent has its own docs folder in which to write docs for me! This could be documentation about how the program works as well as deployment instructions reminding me how I can get this program deployed onto the Internet. One folder acts as a conduit from me to the AI and the other is where the AI records guidance information. 

## Benefits

- It's a lot easier to write detailed and lengthy code generation prompts as documents than it is to do so within a chat window. 

## Drawbacks

- Careful system prompting is required to avoid getting the documentation mixed up with the code base in the context that the agent draws upon. This isn't an impossible challenge. Agentic IDE partners are already quite intelligent and becoming more so! Getting them to figure out the repo structure isn't an impossible task!