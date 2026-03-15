# 🔬 TinyScanner — Lexical Analyzer (Compiler Project)

A desktop application built with **C#** and **Avalonia UI** that performs **lexical analysis** (scanning/tokenization) on source code. It reads input code and breaks it down into classified tokens displayed in a table.

---

## ✨ Features

- 📝 Input any source code into the text editor
- 🔍 Scans and tokenizes the code with one click
- 📊 Displays tokens in a clean DataGrid table
- 🌙 Dark mode UI using Avalonia FluentTheme
- ⚡ Built on .NET 10 with cross-platform support (Windows / Linux / macOS)

---

## 🧩 Token Types

| Type | Examples |
|------|----------|
| `Keyword` | `int`, `float`, `string`, `if`, `else`, `return`, `read`, `write`, `repeat`, `until` |
| `Identifier` | `myVar`, `counter`, `x1` |
| `Number` | `42`, `3.14` |
| `String` | `"hello world"` |
| `Operator` | `:=`, `+`, `-`, `*`, `/` |
| `Symbol` | `(`, `)`, `{`, `}`, `;`, `,`, `<`, `>`, `=` |

---

## 🛠️ Tech Stack

- **Language:** C#
- **UI Framework:** [Avalonia UI](https://avaloniaui.net/) v11.3.x
- **Runtime:** .NET 10
- **Packages:**
  - `Avalonia`
  - `Avalonia.Desktop`
  - `Avalonia.Themes.Fluent`
  - `Avalonia.Controls.DataGrid`
  - `Avalonia.ReactiveUI`

---

## 🚀 Getting Started

### Prerequisites

- [.NET 10 SDK](https://dotnet.microsoft.com/download)

### Installation

```bash
# Clone the repository
git clone https://github.com/HamzaTaigo/Compiler_project.git
cd Compiler_project/TinyScanner

# Restore dependencies
dotnet restore

# Build the project
dotnet build

# Run the application
dotnet run
```

---

## 📸 Usage

1. Launch the app with `dotnet run`
2. Type or paste your source code into the text box
3. Click the **Scan** button
4. View the tokenized output in the table below

---

## 📁 Project Structure

```
TinyScanner/
├── App.axaml               # Application entry & theme
├── App.axaml.cs            # App initialization
├── MainWindow.axaml        # Main UI layout
├── MainWindow.axaml.cs     # Scanner logic & token classification
├── Program.cs              # App entry point
└── TinyScanner.csproj      # Project configuration
```

---

## 👨‍💻 Author

**Hamza Taigo** — [GitHub](https://github.com/HamzaTaigo)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
