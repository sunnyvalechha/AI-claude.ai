What is Claude Code? 
* Claude is an agentic coding assistant that can generate code, understands your codebase, edits files, runs commands, and works right inside your terminal, IDE or browser.

Installation:
* Google -> Claude code and download as per your OS.

Commands:
- claude --version    # Verify installation & version
- /login              # login claude once installed & these are / commands
- /voice              # Enable voice mode
- /config             # Claude settings, Settings Location ".claude/settings.local.json"
- shift+tab           # change mode in cli
- claude              # Start a new session
- claude "abc xyz"    # start with specific task
- claude -p "query"   # run a query & exit
- ! pwd, ! git push                # shell command with !, saves tokens 
- claude --model opus              # start with specific model
- claude -c                        # continue your last session
- claude doctor                    # diagnostic
- .claude/settings.local.json  # this folder contains local claude permissions, global is different


Claude.md  (markdown file, instruction file inside your project)
- It is not documentation and not a style guide. It's a onboarding of a new team member and instruction we want to give them, do's & dont's
- It tells, what this system is trying to achieve.
- Which patterns are allowed and which are banned.
- How changes should be made.
- How correctness is verified.
- Claude.md flips the model - define the rule once and every session carries them forward.
- Dont create claude.md file manually, just run "/init". The claude code analyzes the codebase and generates a starter claude.md
- If the rule is very important use words in claude.md file like "IMPORTANT" or "YOU MUST" for critical rules to improve functionality
- check wordings if rule are continuously ignored.
- 


Auto Memory:

- claude --resume      # resumes your running tasks
- Location: "at root location" "cd .." "cd" ".claude"    # Global settings


