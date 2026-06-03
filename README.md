# Men of Culture

A cinematic cultural archive website showcasing important events, revolutions, and milestones from 2015–2026.

## Features

* Interactive timeline
* Major historical events section
* AI-powered archive assistant
* Dynamic event management
* Animated UI and custom cursor
* Responsive design

## Technologies Used

* HTML5
* CSS3
* JavaScript (Vanilla)
* Anthropic Claude API

## Project Structure

```text
.
├── index.html
└── README.md
```

## How to Run

### Option 1: Open Directly

1. Download or clone the project.
2. Open `index.html` in your browser.

### Option 2: Run with VS Code Live Server

1. Install the **Live Server** extension in VS Code.
2. Open the project folder.
3. Right-click `index.html`.
4. Click **Open with Live Server**.

### Option 3: Run with Python

```bash
# Python 3
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## AI Features

The project uses the Anthropic Claude API for:

* Archive questions
* Event descriptions
* Dynamic content generation

To use AI functionality, configure your Anthropic API key in the JavaScript fetch requests.

## Notes

* Internet connection is required for Google Fonts.
* AI features require a valid Anthropic API key.
* Do not expose API keys in production client-side code.

## License

MIT License
