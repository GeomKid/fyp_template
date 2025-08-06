# Final Year Project LaTeX Template - Universiti Malaya

A professional LaTeX template for final year project reports designed specifically for Universiti Malaya students. This template provides a complete structure with proper formatting, frontmatter sections, and customizable content areas.

## Features

- ✅ Compliant with Universiti Malaya formatting requirements
- ✅ Includes all required frontmatter (abstract, acknowledgements, declarations)
- ✅ Pre-structured content sections for easy organization
- ✅ Support for figures, tables, and references
- ✅ Customizable fonts and styling

## Prerequisites

Ensure LaTeX is installed on your system:

### Online (Recommended for beginners)
- Register at [Overleaf](https://www.overleaf.com)
- Upload these files to a new project

### Local Installation
- **Windows**: `winget install miktex.miktex strawberryperl.strawberryperl`
  - Launch `MikTeX Console` to update packages
- **Ubuntu/Debian**: `sudo apt install texlive-basic`
- **macOS**: Install [MacTeX](https://www.tug.org/mactex/)

## Quick Start

### Using Overleaf (Online)
1. Upload all template files to your Overleaf project
2. Set the main document to `main.tex` (Project → Settings → Main document)
3. **Important**: Change compiler to LuaTeX ([Menu → Compiler → LuaTeX](https://www.overleaf.com/learn/how-to/Changing_compiler))
4. Click the "Recompile" button to generate the PDF
5. Overleaf will automatically recompile when you make changes

### Using Local LaTeX Installation
1. Clone or download this template
2. Compile using LuaTeX (required for this template):
   - `lualatex main.tex` - Single compilation
   - `lualatex -pvc main.tex` - Continuous compilation (auto-recompiles on save)
   - `latexmk -lualatex main.tex` - Using latexmk with LuaTeX

## Customization Checklist

Before using this template, customize the following sections:

1. **Personal Information** (in `main.tex`):
   - [Date](main.tex#L74) - Day of signature in original work declaration
   - [Title](main.tex#L75) and [TitleMS](main.tex#L76) - English and Malay titles
   - [Author](main.tex#L77) - Your full name
   - [Matric No](main.tex#L78) - Student ID number
   - [IC No](main.tex#L79) - Identity card number
   - [Degree Name](main.tex#L80) - Your degree program
   - [Faculty](main.tex#L81) - Your faculty name

2. **Academic Content**:
   - [Field of Study](frontmatter/original.tex#L24) - Your research area
   - [Symbols and Abbreviations](main.tex#L123) - List of symbols used
   - [Acknowledgements](frontmatter/acknowledgements.tex) - Thank you section
   - [Abstract](frontmatter/abstract.tex) - Project summary

3. **Project Content**:
   - Add images to [`assets/`](assets/) folder
   - Update all sections in [`content/`](content/) folder

## Project Structure

```
fyp_template/
├── main.tex              # Main document file
├── main.pdf              # Compiled output
├── ref.bib              # Bibliography references
├── frontmatter/         # Title pages, abstracts, declarations
├── content/             # Main content chapters
├── assets/              # Images and figures
└── fonts/               # Custom fonts (Arial)
```

## Contributing

Feel free to submit issues or pull requests to improve this template for the UM community.
