# Thefoamtrain
Foamy stuff

## Getting Started with Gemini CLI

This repository is set up to work with Google's Gemini CLI for AI-assisted development.

### Prerequisites
- Gemini CLI is installed globally: `npm install -g @google/genai`
- You need a Google AI API key (set as GEMINI_API_KEY environment variable)

### Usage

1. **Interactive Mode**: Run `gemini` in the project directory for an interactive session
2. **Quick Prompts**: Use `gemini "your prompt here"` for one-off commands
3. **File Analysis**: The CLI will automatically include relevant files in context

### Configuration

The project includes:
- `.gemini/settings.json` - Gemini CLI configuration
- `.gitignore` - Properly configured to handle Gemini temporary files

### Setting up API Key

```bash
# Add to your shell profile (.zshrc, .bashrc, etc.)
export GEMINI_API_KEY="your_api_key_here"
```

Get your API key from: https://makersuite.google.com/app/apikey
