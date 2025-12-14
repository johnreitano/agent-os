# Quick Start

## Base Installation

```
curl -sSL https://raw.githubusercontent.com/johnreitano/agent-os/main/scripts/base-install.sh | bash
```

## Project Installation

Run the following command to install needed LLM commands and agents into into your project:
```
cd ~/dev/my-project
~/agent-os/scripts/project-install.sh \
    --profile default \
    --claude-code-commands true \
    --agent-os-commands true \
    --standards-as-claude-code-skills true
```
Files will be installed into the following directories:
- `~/dev/my-project/agent-os/`
- `~/dev/my-project/.claude/`

For more options, run `~/agent-os/scripts/project-install.sh --help`

## Project Config & Building Features

Once Agent OS is installed in your project, configure it and start building features by following the steps in [README-FOR-PROJECT.md](README-FOR-PROJECT.md)
