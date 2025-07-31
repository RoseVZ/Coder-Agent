# Coder Crew
Code from a Course.....
Uses Crew

## Installation

First, if you haven't already, install uv:

```bash
pip install uv
```

(Optional) Lock the dependencies and install them by using the CLI command:
```bash
crewai install
```
### Customizing

**Add your `OPENAI_API_KEY` into the `.env` file**

- Modify `src/coder/config/agents.yaml` to define your agents
- Modify `src/coder/config/tasks.yaml` to define your tasks
- Modify `src/coder/crew.py` to add your own logic, tools and specific args
- Modify `src/coder/main.py` to add custom inputs for your agents and tasks

## Running the Project

To kickstart your crew of AI agents and begin task execution, run this from the root folder of your project:

```bash
$ crewai run
```

