# 0-ugans-agent-hub

A personal collection of GitHub Copilot custom instructions, skills, and agent configurations.

## Structure

```
├── .github/
│   ├── copilot-instructions.md    # Global Copilot instructions (auto-loaded in this repo)
│   └── copilot/                   # Copilot skills & prompt files
├── instructions/                  # Reusable instruction sets by domain
│   └── coding-standards.md
├── skills/                        # Portable skill definitions
│   └── code-review.md
```

## How to Use

### In This Repo
- `.github/copilot-instructions.md` is automatically picked up by Copilot when working in this repo.
- Files in `.github/copilot/` are available as prompt files and skills.

### In Other Repos
Copy any instruction or skill file into another repo's `.github/` directory, or reference them as inspiration for your own.

## Adding New Instructions

1. Create a `.md` file in `instructions/` or `skills/`
2. Follow the template format (see existing files for examples)
3. Optionally copy into `.github/copilot-instructions.md` or `.github/copilot/` for active use

## Resources

- [Customizing Copilot in your IDE](https://docs.github.com/en/copilot/customizing-copilot)
- [Copilot Instructions Reference](https://docs.github.com/en/copilot/customizing-copilot/adding-repository-custom-instructions-for-github-copilot)
- [Copilot Prompt Files](https://docs.github.com/en/copilot/customizing-copilot/adding-prompt-files)
