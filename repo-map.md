# Repo Map For AI Tool

This document provides a set of rules that you must adhere to when working in this repository. 

## Code Workspace Folder

All code for this project must be created within the `code` folder. 

## Docs Workspace Folder

The `docs` folder is the base level for the documentation workspace. 

`/docs/for-ai/instructions`: This is the folder in which the user writes instructions to you:

- The `dev-prompts` folder Contains development prompts providing detailed instructions for you to create this project. The `debugging` folder contains Debugging prompts providing detailed debugging guidance. `edit-prompts` Provides editing instructions. `feature-additions` provides instructions for feature additions.

The `docs/from-ai` folder is a documentation workspace folder in which you can write documentation for the user. 

You can use this folder to generate documentation describing:

- The structure of the code base.   
- The function of specific programs you have generated or edited. 

 

There is also a file there called `ai-changelog.md`. You can use this file to keep a change log as you make changes to the code. 

## User-Only

There is a folder called `user-only`. You must never read or edit content in this folder. 

## File Selection

Use the following logic to guide your decision as to which file to read when you encounter multiple files within any folder:

- The user will employ a basic numbering system in order to distinguish between earlier and later versions. If you encounter files called 1.md, 2.md You would read 2.md.