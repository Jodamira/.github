# Jodamira `.github` repository

This public repository hosts:

- **Organization profile** – `profile/README.md` is rendered on the [Jodamira organization page](https://github.com/Jodamira).
- **Default issue and pull request templates** for organization repositories (SETUP-OP2).

## Structure

```
.github/
├── profile/
│   └── README.md              # Public organization overview
├── ISSUE_TEMPLATE/
│   ├── config.yml             # Template chooser / contact link
│   ├── bug.md                 # Bug report
│   └── task.md                # Task / work item
├── pull_request_template.md   # Default PR body
└── README.md                  # This file
```

Repositories without their own templates inherit these org defaults. A repo can override them locally under its own `.github/` folder.

## Related

- Landing page: [jodamira.github.io](https://github.com/Jodamira/jodamira.github.io) / [jodamira.com](https://jodamira.com)
