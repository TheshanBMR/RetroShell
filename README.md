# RetroShell 🖥️

A vintage-style terminal web app inspired by 90s BBS/console interfaces with modern enhancements and AI integration potential.

![RetroShell](https://img.shields.io/badge/Version-2.0-green) ![License](https://img.shields.io/badge/License-MIT-blue) ![Status](https://img.shields.io/badge/Status-Online-brightgreen)

## ✨ Features

### 🎨 Retro Aesthetic
- Full-screen black background with green terminal text
- Flickering screen effect with CSS animations
- Blinking cursor and scanline overlays
- Matrix-style neon glow effects
- Mobile-responsive design

### 🛠️ Enhanced Commands

| Command | Description |
|---------|-------------|
| `help` | Show available commands |
| `ls` | List files in virtual filesystem |
| `cat <file>` | Display file contents |
| `open <file>` | Render HTML files visually |
| `grep <word>` | Search for text across all files |
| `date` | Show current date and time |
| `uptime` | Display system running time |
| `whois <site>` | Fake domain lookup simulation |
| `telnet <site>` | Connection animation with dots |
| `matrix` | Green ASCII rain animation (Ctrl+C to stop) |
| `fortune` | Random vintage internet quotes |
| `clear` | Clear terminal screen |
| `history` | Show command history |
| `hack` | Easter egg hacking animation |

### 🎮 Interactive Elements
- Command history with arrow key navigation
- Tab autocomplete for commands and filenames
- Real-time uptime counter in footer
- Fake filesystem with nostalgic content
- Easter eggs and hidden features

## 🚀 Quick Start

### Option 1: Direct File
1. Copy the HTML code into a file named `retroshell.html`
2. Open in any modern web browser
3. Start typing commands!

### Option 2: Local Server
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js
npx http-server

# Using PHP
php -S localhost:8000
```

Then navigate to `http://localhost:8000/retroshell.html`

## 🗂️ Virtual Filesystem

RetroShell includes a nostalgic virtual filesystem:

```
index.html      - Retro homepage template
about.txt       - System information
oldpage.html    - "Under Construction" vintage page
archive/
  ancient.txt   - Mysterious ancient file
  logfile.txt   - System logs from 1995
```

## 🎯 Usage Examples

```bash
# Search for text in files
grep secret

# Connect to a fake host
telnet ghost-net.org

# Start the Matrix animation
matrix
# (Press Ctrl+C to stop)

# Get a random quote
fortune

# View command history
history
```

## 🎨 Customization

### Adding New Commands
Extend the `processCommand` function in the JavaScript:

```javascript
case 'newcommand':
    addOutput("This is a new command!");
    break;
```

### Adding Files
Update the `fileSystem` object:

```javascript
'newfile.txt': 'This is new file content',
'secret/': {
    'password.txt': 'hunter2'
}
```

### Modifying Quotes
Edit the `fortunes` array:

```javascript
const fortunes = [
    "Your new quote here",
    "Another wise saying"
];
```

## 🔧 Technical Details

- **Framework**: Pure HTML, CSS, JavaScript
- **Styling**: Tailwind CSS with custom animations
- **Compatibility**: All modern browsers
- **Dependencies**: None (self-contained)
- **File Size**: Single HTML file

## 🌟 AI Integration Potential

The structure is designed for easy AI integration:

- Command parsing system ready for NLP
- Extensible command architecture
- Response formatting system
- Context-aware interactions

## 🐛 Known Issues

- Matrix animation may impact performance on older devices
- Some mobile browsers may have minor rendering differences
- Command history persists only during session

## 🤝 Contributing

Feel free to fork and enhance! Some ideas:

- Add more retro games (PONG, Snake)
- Implement SSH simulation
- Add sound effects
- Create theme system (amber, white-on-blue)
- Add BBS door games

## 📜 License

MIT License - feel free to use in personal and commercial projects.

## 🕸️ Vintage Web Revival

RetroShell celebrates the early internet era while providing a functional, entertaining terminal experience. Perfect for nostalgia trips, learning environments, or as a unique web interface.

---

**Connect to the past. Experience the future.**

*RetroShell - Where vintage meets visionary.*
