# SourcePeek+ Pro

**Advanced Web Scraper & Source Viewer**  
A powerful developer tool to inspect website source code, bypass restrictions, and extract data using proxy rotation. Built with vanilla HTML, CSS, and JavaScript.


## Features

- **Source Code Viewer**  
  - Fetch and display raw HTML with syntax highlighting  
  - Beautify or minify code formatting  
  - Copy or download source code with one click  

- **Proxy Bypass System**  
  - Rotates through 7+ proxy servers to bypass CORS and other restrictions  
  - Automatic retry on failure  
  - Proxy health monitoring  

- **Data Extraction**  
  - Extract all links, images, and scripts from the source  
  - Exportable lists with direct URLs  

- **User-Friendly UI**  
  - Dark/light mode toggle  
  - Keyboard shortcuts (e.g., Ctrl+Enter, Ctrl+B)  
  - Request history tracking  
  - Responsive design  

- **Developer Tools**  
  - Error diagnostics  
  - HTTP status feedback  
  - Rate limit handling  


## Usage

1. Enter a URL (e.g., `https://example.com`)  
2. Click **Fetch Source** or press `Ctrl + Enter`  
3. Use **Advanced Bypass** if blocked (`Ctrl + B`)  
4. Extract data with **Extract Links/Images/Scripts** buttons  

---

## Keyboard Shortcuts

| Shortcut    | Action                   |
|-------------|--------------------------|
| Ctrl + Enter | Fetch source             |
| Ctrl + B    | Activate proxy bypass    |
| Ctrl + C    | Copy source to clipboard |
| Ctrl + D    | Download source as HTML  |

---

## Tech Stack

- Frontend: Vanilla HTML, CSS, JavaScript  
- Libraries:  
  - [highlight.js](https://highlightjs.org/) (syntax highlighting)  
  - [js-beautify](https://github.com/beautify-web/js-beautify) (code formatting)  
- Proxy services: CORS Anywhere, Yacdn, AllOrigins, etc.

---

## Installation

```bash
git clone https://github.com/MrOwner-alt/SourcePeek
cd sourcepeek-pro
open index.html
