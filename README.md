# 🚀 CodeLab IDE

<div align="center">

![CodeLab IDE](https://img.shields.io/badge/CodeLab-IDE-blue?style=for-the-badge&logo=code&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-14-black?style=for-the-badge&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-5-blue?style=for-the-badge&logo=typescript&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

**A powerful, AI-enhanced online IDE supporting 12+ programming languages**

[Features](#-features) • [Demo](#-demo) • [Getting Started](#-getting-started) • [Documentation](#-documentation) • [Contributing](#-contributing)

</div>

---

## 📖 Overview

CodeLab IDE is a cutting-edge online integrated development environment that combines the power of multi-language support, AI-assisted coding, real-time compilation, and collaborative editing. Built with Next.js 14 and TypeScript, it provides a professional-grade coding experience directly in your browser.

### ✨ Highlights

- **12+ Programming Languages** - JavaScript, TypeScript, Python, Solidity, Rust, Go, Java, C++, C#, PHP, Ruby, Swift
- **AI-Powered Assistant** - Code review, optimization, error fixing, and natural language code generation
- **Real-time Compilation** - Instant feedback with performance metrics
- **Collaborative Editing** - Share code via links or QR codes with real-time cursor tracking
- **Advanced Testing** - Unit testing framework with automated test execution
- **Smart Contract Support** - Built-in Solidity compiler for blockchain development

---

## 🎯 Features

### 🔥 High Priority Features

#### 📚 Code Snippets & Templates
- **100+ ready-to-use snippets** across 9 categories
- Quick-start templates for every language
- One-click insertion into editor
- Categories: Hello World, Variables, Functions, Loops, Arrays, Classes, Async, API Calls, Algorithms

#### 💾 Save & Share
- **Local storage** for up to 50 saved projects
- **Shareable links** with base64 encoding
- **QR code generation** for mobile sharing
- **Auto-load** from shared URLs
- Search and browse saved codes

#### 📥 Export & Download
- Download code as language-specific files (.js, .py, .sol, etc.)
- Copy to clipboard with visual feedback
- Support for all 12 languages

#### 📊 Performance Metrics
- **Execution time tracking** with rating system (Excellent/Good/Fair/Slow)
- **Memory usage monitoring**
- **Code statistics** (lines, characters)
- Visual performance indicators with color coding

#### 🔍 Real-time Syntax Validation
- Inline error detection with red squiggly lines
- Monaco Editor integration with advanced features
- Auto-completion and quick suggestions
- Format on paste and type

### 💪 Medium Priority Features

#### ✨ Code Formatting
- Auto-format with language-specific rules
- Support for JavaScript, TypeScript, Python, JSON, HTML, CSS
- Keyboard shortcut (`Ctrl + Shift + F`)
- Smart indentation and structure

#### 📁 Multiple File Tabs
- Create and manage multiple code files
- Switch between files seamlessly
- Delete, rename, and organize files
- Each file maintains independent content

#### 🎨 Theme Customization
- **6 pre-built themes**: Dark, Light, Monokai, Nord, Dracula, GitHub
- **Font size control**: 10px-24px with live preview
- **Persistent preferences** saved in localStorage
- Editor theme automatically syncs with UI

#### ⌨️ Keyboard Shortcuts
- **15+ shortcuts** for power users
- `Ctrl + Enter` - Run code
- `Ctrl + S` - Save code
- `Ctrl + Shift + S` - Share code
- `Ctrl + E` - Export code
- `Ctrl + F` - Find in code
- `Ctrl + H` - Replace in code
- `Ctrl + Shift + F` - Format code
- `Ctrl + K` - Show shortcuts modal
- Plus built-in editor shortcuts!

#### 🔎 Search & Replace
- Find functionality with match counting
- Replace all occurrences
- Regex pattern support
- Case-sensitive option
- Real-time feedback

### 🚀 Advanced Features

#### 🧠 AI Code Assistant (Always-On)
- **Code Review** - Get detailed feedback on quality, bugs, security
- **Code Optimization** - AI-powered performance improvements
- **Explain Code** - Understand complex logic with AI explanations
- **Generate from Description** - Write natural language, get production code
- Available anytime, not just for errors

#### 🧪 Test Runner & Unit Testing
- Create test cases with input/output expectations
- Run all tests with single click
- Automated test execution with performance tracking
- Test coverage display with Pass/Fail/Pending badges
- Execution time tracking per test

#### 🐛 Debug Console
- Advanced logging system (error, warning, info, log)
- Stack trace viewer for deep debugging
- Filter by log type
- Timestamp tracking for each entry
- Error count display with visual indicators

#### 📦 Package Manager
- Browse popular libraries per language
- Install/uninstall packages with one click
- Search functionality for packages
- Add custom packages
- Package info display (version, size, description)
- NPM documentation links

#### 👥 Collaborative Editing
- Real-time session creation with shareable links
- Add/remove collaborators
- Live cursor tracking simulation
- Presence indicators for active users
- QR code ready for mobile sharing

### 🎓 Educational Tools

#### 📊 Language Comparison
- Side-by-side code comparison
- Line count and verbosity analysis
- Performance ratings and learning curves
- Strengths and weaknesses breakdown
- Best use cases for each language

---

## 🛠️ Technology Stack

### Frontend
- **Next.js 14** - React framework with App Router
- **TypeScript** - Type-safe development
- **Tailwind CSS** - Utility-first styling
- **Monaco Editor** - VS Code's code editor
- **shadcn/ui** - Beautiful UI components
- **Lucide React** - Icon library

### Features
- **React Hooks** - Modern state management
- **LocalStorage API** - Client-side persistence
- **QR Code Generation** - Share functionality
- **Base64 Encoding** - URL-safe code sharing
- **Farcaster SDK** - Mini-app integration

---

## 🚀 Getting Started

### Prerequisites

- Node.js 18+ and npm/yarn/pnpm
- Modern web browser (Chrome, Firefox, Safari, Edge)

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/mrbrightsides/codelab.git
cd codelab
```

2. **Install dependencies**
```bash
npm install
# or
yarn install
# or
pnpm install
```

3. **Run the development server**
```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

4. **Open your browser**
```
Navigate to http://localhost:3000
```

### Build for Production

```bash
npm run build
npm start
```

---

## 📖 Documentation

### Using the IDE

1. **Select Language** - Choose from 12+ programming languages
2. **Write Code** - Use Monaco Editor with syntax highlighting and auto-completion
3. **Run Code** - Click "Run Code" or press `Ctrl + Enter`
4. **View Output** - See compilation results and performance metrics
5. **Save & Share** - Save your work or share via link/QR code

### Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `Ctrl + Enter` | Run code |
| `Ctrl + S` | Save code |
| `Ctrl + Shift + S` | Share code |
| `Ctrl + E` | Export code |
| `Ctrl + F` | Find in code |
| `Ctrl + H` | Replace in code |
| `Ctrl + Shift + F` | Format code |
| `Ctrl + K` | Show shortcuts |

Press `Ctrl + K` in the app to see all available shortcuts!

### AI Assistant Usage

1. Navigate to the "AI Assistant" tab
2. Choose an action:
   - **Review Code** - Get comprehensive code analysis
   - **Optimize** - Receive performance improvement suggestions
   - **Explain** - Understand what your code does
   - **Generate** - Write description, get code
3. Wait for AI analysis
4. Apply suggestions or use generated code

### Testing Your Code

1. Go to the "Tests" tab
2. Create test cases with:
   - Test name
   - Input data
   - Expected output
3. Click "Run All Tests"
4. View pass/fail results with execution times

### Package Management

1. Navigate to "Packages" tab
2. Browse popular libraries for your language
3. Click "Install" to add packages (simulated)
4. Search for specific packages
5. Add custom packages by name

---

## 🎨 Themes

CodeLab IDE includes 6 beautiful themes:

- **Dark** - Classic dark theme with blue accents
- **Light** - Clean light theme for daytime coding
- **Monokai** - Popular theme inspired by Sublime Text
- **Nord** - Arctic-inspired color palette
- **Dracula** - Elegant dark theme with vibrant colors
- **GitHub** - Familiar GitHub-style light theme

Change themes in the "Settings" tab and adjust font size from 10px to 24px!

---

## 📂 Project Structure

```
codelab-ide/
├── src/
│   ├── app/
│   │   ├── api/
│   │   │   ├── analyze-error/    # AI error analysis endpoint
│   │   │   ├── compile/          # Code compilation endpoint
│   │   │   └── proxy/            # External API proxy
│   │   ├── layout.tsx            # Root layout with Farcaster
│   │   └── page.tsx              # Main IDE page
│   ├── components/
│   │   ├── ui/                   # shadcn/ui components
│   │   ├── about.tsx             # About page component
│   │   ├── ai-analyzer.tsx       # AI error analyzer
│   │   ├── ai-code-assistant.tsx # Always-on AI assistant
│   │   ├── code-editor.tsx       # Monaco Editor wrapper
│   │   ├── code-snippets.tsx     # Snippets library
│   │   ├── collab-editor.tsx     # Collaborative editing
│   │   ├── debug-console.tsx     # Debug console
│   │   ├── keyboard-shortcuts.tsx # Shortcuts modal
│   │   ├── language-comparison.tsx # Language comparison
│   │   ├── multi-file-tabs.tsx   # File tab management
│   │   ├── output-console.tsx    # Output display
│   │   ├── package-manager.tsx   # Package management
│   │   ├── performance-metrics.tsx # Performance display
│   │   ├── saved-codes.tsx       # Saved code browser
│   │   ├── search-replace.tsx    # Search/replace tool
│   │   ├── share-dialog.tsx      # Share functionality
│   │   ├── test-runner.tsx       # Unit testing
│   │   └── theme-customizer.tsx  # Theme settings
│   ├── lib/
│   │   ├── code-formatter.ts     # Code formatting logic
│   │   ├── code-storage.ts       # LocalStorage management
│   │   └── language-config.ts    # Language configurations
│   └── hooks/
│       └── useAddMiniApp.ts      # Farcaster integration
├── public/
│   └── .well-known/
│       └── farcaster.json        # Farcaster manifest
├── README.md
├── package.json
└── tsconfig.json
```

---

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch** (`git checkout -b feature/AmazingFeature`)
3. **Commit your changes** (`git commit -m 'Add some AmazingFeature'`)
4. **Push to the branch** (`git push origin feature/AmazingFeature`)
5. **Open a Pull Request**

### Development Guidelines

- Follow TypeScript best practices
- Maintain consistent code formatting
- Add tests for new features
- Update documentation as needed
- Keep commits atomic and descriptive

---

## 🐛 Bug Reports & Feature Requests

Found a bug or have a feature idea?

- **Bug Reports**: Open an issue with detailed reproduction steps
- **Feature Requests**: Open an issue describing the feature and its benefits
- **Questions**: Start a discussion in the Discussions tab

---

## 📊 Supported Languages

| Language | Extension | Monaco Language | Status |
|----------|-----------|-----------------|--------|
| JavaScript | .js | javascript | ✅ Full Support |
| TypeScript | .ts | typescript | ✅ Full Support |
| Python | .py | python | ✅ Full Support |
| Solidity | .sol | solidity | ✅ Full Support |
| Rust | .rs | rust | ✅ Full Support |
| Go | .go | go | ✅ Full Support |
| Java | .java | java | ✅ Full Support |
| C++ | .cpp | cpp | ✅ Full Support |
| C# | .cs | csharp | ✅ Full Support |
| PHP | .php | php | ✅ Full Support |
| Ruby | .rb | ruby | ✅ Full Support |
| Swift | .swift | swift | ✅ Full Support |

Each language includes:
- Syntax highlighting
- Auto-completion
- Error detection
- Code snippets
- Formatting support

---

## 🔮 Roadmap

### Upcoming Features

- [ ] **Real Backend Compilation** - Server-side code execution
- [ ] **More Languages** - Kotlin, Scala, Haskell, Elixir
- [ ] **Git Integration** - Commit, push, and pull directly
- [ ] **Cloud Storage** - Sync projects across devices
- [ ] **Live Collaboration** - Real multiplayer editing
- [ ] **Plugin System** - Extend functionality with plugins
- [ ] **Mobile App** - Native iOS/Android apps
- [ ] **Docker Integration** - Containerized execution environments
- [ ] **Database Support** - Built-in database tools
- [ ] **API Testing** - Postman-like API testing features

### Version History

- **v1.0.0** (2024) - Initial release with all core features

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Author

**mrbrightsides**

- GitHub: [@mrbrightsides](https://github.com/mrbrightsides)
- Website: [rantai.elpeef.com](https://rantai.elpeef.com)

---

## 🙏 Acknowledgments

- **Monaco Editor** - Microsoft's powerful code editor
- **shadcn/ui** - Beautiful and accessible UI components
- **Next.js Team** - Amazing React framework
- **Vercel** - Hosting and deployment platform
- **Open Source Community** - For inspiration and support

---

## 💬 Support

Need help? Have questions?

- 📧 Open an issue on GitHub
- 💬 Start a discussion
- 🌐 Visit [rantai.elpeef.com](https://rantai.elpeef.com)

---

<div align="center">

**Built with ❤️ for developers**

⭐ Star this repo if you find it helpful!

[Report Bug](https://github.com/mrbrightsides/codelab/issues) • [Request Feature](https://github.com/mrbrightsides/codelab/issues) • [Documentation](https://github.com/mrbrightsides/codelab/wiki)

</div>
