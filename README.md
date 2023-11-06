# E-book starter
Powered by Pandoc

## Setup
- Install [Node](https://nodejs.org/en/download) for your platform
- Install [Pandoc](https://pandoc.org/installing.html) for your platform
- Install [LaTeX](https://www.latex-project.org/get/) for your platform

> ℹ️ For macOS users the fastest way to install the above dependencies is via `homebrew`:
> ```
> brew install node pandoc basictex
> ```


## Edit
- Open the `source.md` file in your text editor (for example [Visual Studio Code](https://code.visualstudio.com/))
- Update the file taking into account [Markdown](https://www.markdownguide.org/cheat-sheet) syntax and save it

## Build
- Run `npm run build:epub` to generate **epub**
OR
- Run `npm run build:pdf` to generate **pdf**
OR
- Run `npm run build` to generate all formats

The generated files will be available at the `books` folder
