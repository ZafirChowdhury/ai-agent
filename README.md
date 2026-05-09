# AI Agent

Very basic AI agent buit using the gemini api.

Do not run this program on your local machine! It does not have all the security and safety features that a production AI agent would have. It is for learning purposes only.

## What it can do

The agent accepts a natural language prompt from the command line and autonomously decides which tools to call to fulfill it. It runs in an agentic loop (up to 20 iterations) until it has a final answer.

It has access to four tools:
- **List files and directories** — browse the working directory structure
- **Read file contents** — inspect any file in the working directory
- **Write or overwrite files** — create or edit files based on instructions
- **Execute Python files** — run Python scripts and capture their output

Things I learned from this 
- Working with files, directorys
- Running other program using pythons subprocess
- args, stout, sterr
- Working with extarnal api (IE google gemenie api)
- Test-Driven Development
