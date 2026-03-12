# aide

**aide** is a developer learning toolkit that helps you understand code as you write it — through AI-powered quizzes, explanations, and paste interception.

## Projects

### VS-Code-Extension
A VS Code extension that quizzes you on code and provides detailed explanations.

- **Quiz Me** — generate AI-powered questions about selected or pasted code
- **Explain This Code** — get line-by-line breakdowns of what code does
- **Poke Mode** — intercepts paste (`Cmd+V` / `Ctrl+V`) and prompts you to understand the code before it lands in your editor

**Keybindings**
| Action | Mac | Windows/Linux |
|---|---|---|
| Quiz Me | `Cmd+Alt+Q` | `Ctrl+Shift+Q` |
| Explain Code | `Cmd+Alt+E` | `Ctrl+Shift+E` |

See [VS-Code-Extension/README.md](VS-Code-Extension/README.md) for setup and usage details.

### Chrome-Extension *(submodule)*
Browser extension companion. Source: [alansigh/ClipCode-Draft1](https://github.com/alansigh/ClipCode-Draft1)

### aide-Website *(submodule)*
Marketing/landing page for aide. Source: [hungbri288/aide-website](https://github.com/hungbri288/aide-website)

## Getting Started

```bash
# Clone with submodules
git clone --recurse-submodules <repo-url>

# Or initialize submodules after cloning
git submodule update --init --recursive
```

Then follow the setup guide in each project's directory.

## License

MIT
