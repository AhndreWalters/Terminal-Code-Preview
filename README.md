# Terminal Code Preview

A simple web-based tool to preview how code and terminal commands look in a terminal environment, with the ability to take screenshots for documentation.

## Features

Live Terminal Preview - Type or paste any code/commands and see them rendered in real-time in a terminal-style preview

Screenshot Capability - Capture the terminal preview with curved edges as a PNG image, perfect for documentation and presentations

Multiple Terminal Types - Support for different terminal environments:
  - Bash
  - Command Prompt (CMD)
  - PowerShell
  - Zsh

Mac-Style Design - Clean, modern interface inspired by ChatGPT and DeepSeek with authentic macOS terminal styling including red, yellow, and green window control dots

Responsive Layout - Works seamlessly on desktop and tablet devices

## Getting Started

### Usage

1. Open the Application
   - Simply open terminal-preview.html in any modern web browser
   - No server or installation required

2. Input Your Code
   - Paste your terminal commands or code in the left input area
   - Content updates in real-time

3. Select Terminal Type
   - Choose from the dropdown menu: Bash, CMD, PowerShell, or Zsh
   - The preview updates automatically with the appropriate prompt style

4. Take a Screenshot
   - Click the Take Screenshot button
   - The terminal preview is downloaded as a PNG image with preserved rounded corners

### Example Use Cases

- Creating technical documentation
- Teaching and tutorials
- Writing blog posts or articles
- Presentations and reports
- Network configuration backups (like Cisco CLI output)

## Features in Detail

### Terminal Types

Each terminal type displays with its characteristic prompt style:

- Bash: `user@machine:~$`
- CMD: `C:\Users\User>`
- PowerShell: `PS C:\Users\User>`
- Zsh: `user@machine ~`

### Screenshot Functionality

- Captures only the terminal box with curved corners
- No surrounding UI elements included
- High-quality 2x scale rendering
- Automatically downloads as `terminal-[timestamp].png`

## Requirements

- Modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection (for html2canvas library)

## Technologies Used

- HTML5 - Structure
- CSS3 - Styling and layout
- JavaScript - Interactivity and screenshot functionality
- html2canvas - Screenshot library via CDN

## Contributing

Contributions are welcome! Feel free to submit issues or pull requests to improve the tool.

## Support

If you encounter any issues or have suggestions for improvements, please open an issue on the GitHub repository.

<b>[&copy; 2026 Ahndre Walters](https://github.com/AhndreWalters/Terminal-Code-Preview/blob/main/LICENSE)</b>
