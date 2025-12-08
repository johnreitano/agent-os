# Getting Started

## Base Installation

```
curl -sSL https://raw.githubusercontent.com/johnreitano/agent-os/main/scripts/base-install.sh | bash
```

## Project Installation

Run the following command to install needed LLM commands and agents into into your project:
```
cd ~/dev/my-project
~/agent-os/scripts/project-install.sh
```
Files will be installed into the following directories:
- `~/dev/my-project/agent-os/`
- `~/dev/my-project/.claude/`

For more options, run `~/agent-os/scripts/project --help`

