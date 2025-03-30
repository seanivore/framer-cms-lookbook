# AI Resources Repository

Place to organize actual AI `./resources/` directory, a resource that gets copied into all new project by using the `./repo-starter/` directory. This AI directory also houses main copies of CORE DOCS as templates, and Claude OS app workspace documents that breakdown using tools written in JSON, including a copy for Cursor, both of which have protocol for the Memory system used to manage projects in concert, and then a master map file for all projects. 

## Repo Starter & AI Resources 

The `_ai` directory contains Claude-designed UI documents for AI workspaces. 

- Workspace configuration files
  - Project management memory system protocol 
  - Memory system keywords 
  - Tools listed in JSON format 
  - Master map for all project planning and task management 

- The `repo-starter` directory includes pre-configured:
  - `.gitignore` optimized for AI development
  - `.cursor/rules/` ready for rules, etc. 
  - `.vscode/` with copy of settings and template Cursor workspace file 
  - CORE DOCS as templates 
  - The full AI `./resources/` directory 
  - Directory full of markdown CSS files 
  - Sample Aider config file 

## Usage

### Starting a New Project

1. Create a new project directory; slug style filename will be used for the project name 
2. Copy contents from `repo-starter/` into your new directory with `cp -R /Users/seanivore/Development/_ai.resources/repo-starter/. .`
3. Run `git init`
4. Rename branch to mirror project name from project directory name 
5. Create GitHub repo with same project name using `gh repo create <repo-project-name> --public --source=. --remote=origin` 
6. Last, push the commit using `git push -u origin <repo-project-name>` to set `git push` as functional 

### MCP Resources

The `resources` directory contains essential reference materials:

- **MCP Core Concepts** - Foundational documentation on Model Context Protocol
- **MCP Spec Schemas** - Technical specifications and JSON schemas
- **MCP Test & Debug** - Tools and guides for testing MCP implementations
- **Aider How To** - Aider documentation in TXT format
- **About SFA** - About Single File Agents 
- **LLM Context** - LLM Context how to; still confusing  

### MASTER_MAP

The [MASTER_MAP.md](./AI.MASTER_MAP.md) is our central planning document that:

- Organizes all projects, tasks, and priorities in one place
- Uses emoji indicators for visual task status tracking
- Structures work into New Business, In Focus, and Old Business sections
- Provides a foundation for automated task management via single-file agents