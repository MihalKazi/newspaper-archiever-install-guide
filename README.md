# 📰 Newspaper Archiver

A powerful web application that allows you to archive news articles from any website for offline reading and long-term storage.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Node](https://img.shields.io/badge/node-%3E%3D%2020.0.0-brightgreen.svg)
![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey.svg)

## 🌟 Features

- **Universal Compatibility**: Archive articles from any news website
- **Offline Access**: Save articles for reading without internet connection
- **Organized Storage**: Automatically organizes articles by website and date
- **Clean Interface**: Simple, user-friendly web interface
- **Fast Performance**: Built with Node.js and Playwright for efficient scraping
- **Complete Preservation**: Saves articles with images and formatting intact

## 🚀 Quick Start

### Prerequisites

Before you begin, ensure you have the following installed:
- **Node.js** (v20.0.0 or higher)
- **Git**
- **VS Code** (recommended)

### Installation

#### 🪟 Windows

1. **Install Chocolatey** (if not already installed):
   ```powershell
   Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
   ```

2. **Install dependencies**:
   ```powershell
   choco install nodejs-lts git vscode -y
   ```

3. **Clone the repository**:
   ```cmd
   git clone https://github.com/MihalKazi/newspaper-archiever.git
   cd newspaper-archiever
   ```

4. **Install npm packages**:
   ```cmd
   npm install
   npx playwright install
   ```

#### 🍎 macOS

1. **Install Homebrew** (if not already installed):
   ```bash
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
   ```

2. **Install dependencies**:
   ```bash
   brew install node git
   brew install --cask visual-studio-code
   ```

3. **Clone the repository**:
   ```bash
   git clone https://github.com/MihalKazi/newspaper-archiever.git
   cd newspaper-archiever
   ```

4. **Install npm packages**:
   ```bash
   npm install
   npx playwright install
   ```

#### 🐧 Linux

1. **Install Node.js and Git**:
   ```bash
   # Ubuntu/Debian
   sudo apt update
   sudo apt install nodejs npm git -y
   
   # Fedora
   sudo dnf install nodejs git -y
   ```

2. **Clone the repository**:
   ```bash
   git clone https://github.com/MihalKazi/newspaper-archiever.git
   cd newspaper-archiever
   ```

3. **Install npm packages**:
   ```bash
   npm install
   npx playwright install
   ```

### Running the Application

1. **Start the server**:
   ```bash
   npm start
   ```

2. **Open your browser** and navigate to:
   ```
   http://localhost:3000
   ```

3. **Archive an article**:
   - Copy any news article URL
   - Paste it into the text box
   - Click "Archive This Article"
   - Wait for the download to complete

## 📖 Usage

### Archiving an Article

1. Find any news article you want to save
2. Copy the article URL from your browser
3. Paste the URL into the Newspaper Archiver interface
4. Click "Archive This Article"
5. Wait 30 seconds to 2 minutes for processing
6. Find your archived article in the `archives/` folder

### Accessing Archived Articles

Archived articles are saved in:
```
archives/[website-name]/[date]/[article-title]/
```

Each archived article includes:
- Full text content
- Images and media
- Original formatting
- Metadata (date, source, etc.)

## 🛠️ Technologies Used

- **Node.js**: Backend runtime
- **Express.js**: Web server framework
- **Playwright**: Web scraping and automation
- **HTML/CSS/JavaScript**: Frontend interface

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/amazing-feature`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add some amazing feature'`)
5. Push to the branch (`git push origin feature/amazing-feature`)
6. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🐛 Bug Reports

If you encounter any bugs or issues, please [open an issue](https://github.com/MihalKazi/newspaper-archiever/issues) on GitHub with:
- A clear description of the problem
- Steps to reproduce the issue
- Your operating system and Node.js version
- Any error messages or screenshots

## 💬 Support

For questions or support:
- **Email**: [rohankazi728@gmail.com](mailto:rohankazi728@gmail.com)
- **GitHub Issues**: [Create an issue](https://github.com/MihalKazi/newspaper-archiever/issues)

## 🙏 Acknowledgments

- Built with [Playwright](https://playwright.dev/)
- Inspired by the need to preserve journalism and articles for offline access

## 📊 Roadmap

- [ ] Add support for batch archiving
- [ ] Implement search functionality for archived articles
- [ ] Add export options (PDF, EPUB)
- [ ] Create browser extension
- [ ] Add tagging and categorization system
- [ ] Implement user authentication for cloud storage

## 👨‍💻 Author

**Kazi Rohanuzzaman Mehal**

- GitHub: [@MihalKazi](https://github.com/MihalKazi)
- Email: rohankazi728@gmail.com

---

<div align="center">
  <p>If this project helped you, please consider giving it a ⭐️!</p>
  <p>Made with ❤️ by Kazi Rohanuzzaman Mehal</p>
</div>
