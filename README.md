🚀 NovaStudio-IDE

A multi-language Web IDE and code workbench built for GitHub.
Developed by ItsNovaTVs.

🌟 Overview

NovaStudio-IDE is a client-side IDE operating directly inside the browser. It combines multi-language code editing, instant execution sandboxes, real-time web previews, a database execution engine, and an AI-powered coding assistant powered by Gemini API.

Whether you're developing web apps, querying SQL databases, writing WebAssembly Python scripts, or drafting Java logic, NovaStudio-IDE offers a complete local workbench without requiring server installs.

⚡ Features

💻 Multi-Language Workbench: Full syntax highlighting, line numbers, themes, and auto-indent for Java, Python, SQL, HTML, CSS, JavaScript, JSON, and Markdown.

🐍 In-Browser Python Execution (Pyodide): Run Python scripts directly using WebAssembly with sys.stdout streaming output.

📊 Live SQL Database Engine (AlaSQL): Create tables, seed data, run complex SQL queries, and inspect interactive tabular output.

🌐 Instant Web Sandbox: Combine HTML, CSS, and JS files with live rendering inside an isolated iframe, complete with captured console.log streaming to the integrated terminal.

☕ Java Code Execution & Analysis: Built-in AST/Execution engine for running Java class files, method calls, loops, and standard stdout.

🤖 Nova AI Coding Assistant: Integrated Gemini API assistant (gemini-3-flash-preview) to explain code, auto-fix runtime bugs, refactor code, and generate unit tests.

📂 Workspace & File System: Multi-tab editor, create/rename/delete files and folders, auto-persist to localStorage, and export project as .ZIP archives.

🐙 GitHub Integration: Connect directly to your GitHub target repo (ItsNovaTVs/NovaStudio-IDE), export Gists, and manage project code.

🎨 Sleek VS Code-Inspired UI: Built with Tailwind CSS, custom dark mode themes (Dracula, Monokai, Material Darker, Nord), responsive layout, and split pane view.

📂 Project Repository Structure

NovaStudio-IDE/
├── index.html         # Main single-file IDE application (HTML + CSS + JS)
├── README.md          # Project documentation


🚀 Quick Start

1. Run Locally (No Server Required)

Simply download or clone the repository and open index.html in any modern web browser:

git clone https://github.com/ItsNovaTVs/NovaStudio-IDE.git
cd NovaStudio-IDE
open index.html


2. Deploy to GitHub Pages

Go to your repository settings on GitHub: https://github.com/ItsNovaTVs/NovaStudio-IDE/settings/pages

Under Source, select Deploy from a branch.

Set the branch to main (or master) and directory to / (root).

Click Save. Your IDE will be live at https://ItsNovaTVs.github.io/NovaStudio-IDE/!

🛠️ Integrated Execution Engines

Language

Engine / Technology

Features

Python

Pyodide (WASM)

Real Python runtime, standard library, stdout/stderr capture

SQL

AlaSQL Engine

Tables, JOINs, SELECT, INSERT, tabular visual output

HTML / CSS / JS

Isolated Iframe Sandbox

Real-time DOM preview, active console interception

Java

Simulated Client Runtime

Java class parsing, main method execution, System.out stream

JSON

Native Parser & Inspector

Syntax checking, formatting, minification, tree viewer

Markdown

Dynamic Render

Live rich-text preview engine

🤖 Configuring Gemini AI Assistant

Open the Nova AI panel from the right sidebar in the IDE.

(Optional) Provide your personal Gemini API Key, or use the integrated system fallback runtime.

Use quick action buttons like "Explain Code", "Fix Bugs", or "Refactor" to interact with the current active file code.

🤝 Contributing

Contributions, issues, and feature requests are welcome!

Feel free to check out the Issues page.

Fork the Project

Create your Feature Branch (git checkout -b feature/AmazingFeature)

Commit your Changes (git commit -m 'Add some AmazingFeature')

Push to the Branch (git push origin feature/AmazingFeature)

Open a Pull Request

📄 License

Distributed under the MIT License. See LICENSE for details.

Developed with ❤️ by ItsNovaTVs.
