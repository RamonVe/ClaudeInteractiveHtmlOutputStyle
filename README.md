# Claude Code HTML Interactive Output Style

This repository contains a custom output style configuration for Claude Code that enables intelligent HTML generation with interactive features.

## Purpose

This output style allows Claude Code to automatically switch between terminal text output and rich HTML generation based on user requests, providing an enhanced experience for web-related tasks.

## How It Works

The configuration defines two output modes:

- **Default Mode**: Normal terminal/text responses for standard coding tasks
- **HTML Mode**: Generates complete, interactive HTML pages when triggered by specific keywords

## Trigger Keywords

HTML mode activates when users mention:
- `html`, `HTML`, `web page`, `webpage`
- `interactive`, `web app`, `webapp` 
- `documentation page`, `docs page`
- `generate HTML`, `create HTML`
- `todo list` (for interactive format)
- `project documentation` (for web format)

## Features

### Complete HTML Structure
- Full DOCTYPE and semantic HTML5 markup
- Responsive CSS with mobile-first design
- Modern JavaScript for interactivity
- Professional styling with dark/light mode support

### Interactive Components
- Dynamic content manipulation
- Local storage persistence
- Search and filtering capabilities
- Collapsible sections and modals
- Smooth animations and transitions

### Project Integration
- Logical file placement (`docs/index.html`)
- Git integration guidance
- Development server suggestions
- Asset organization best practices

## Installation

### Method 1: File-based Installation
1. Place the `html-interactive.md` file in your Claude Code configuration directory
2. The output style will automatically be available in Claude Code
3. No additional setup required

### Method 2: Direct Copy-Paste
1. Open Claude Code in your terminal
2. Use the output style creator command
3. Copy and paste the entire contents of `html-interactive.md` directly into the terminal when prompted
4. The output style will be created and immediately available

## Usage

Simply mention HTML-related keywords in your requests to Claude Code:

```
"Create an interactive HTML todo list"
"Generate a documentation webpage for this API"
"Build a web app dashboard"
```

Claude Code will automatically generate complete, functional HTML with CSS and JavaScript included.

## File Structure

```
ClaudeInteractiveHtmlOutputStyle/
├── README.md                 # This documentation
└── html-interactive.md       # Output style configuration
```

## Requirements

- Claude Code CLI tool
- No additional dependencies (generates self-contained HTML)

## License

This configuration is provided as-is for use with Claude Code.