# TODO

## AI Agent for Automated Issue Resolution & PR Creation

- AI agent will integrate with a GitHub repository 
- Receive context from the BlotUp Chrome extension


## Will analyze
- network requests
- console logs
- error logs
- performance data
- user actions
- page URLs
- Identify and fix code
- Raise GitHub PR

## Requirements
1. GitHub API Access / Permissions and Authentication
2. BlotUp Chrome Extension Integration
3. Server / Cloud Environment
4. ChatGPT APIs

## Functional Requirements
1. CONTEXT GATHERING => Blotup creates issues and gathers context, including network logs, console logs, error logs, and user actions)
2. ISSUE IDENTIFICATION => Identify potential error lines of code
3. CODE FIXING => Generating a code fix using chatGPT
4. PULL REQUEST CREATION => Create branches for fixes, and use GitHub APIs to raise PR with a description
5. REVIEW AND NOTIFICATION => Notifying development teams to review the code and merge it.


> Note: Need to discuss => Deployment strategy, monitoring and logging
