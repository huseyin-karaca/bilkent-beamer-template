# Bilkent University Beamer Template

A clean and professional LaTeX Beamer template for presentations using Bilkent University colors and branding.

**Note:** This template is built upon the original [Bilkent Beamer Template by Alican Büyükçakır](https://github.com/abuyukcakir/bilkent-beamer-template). The documentation and examples in this repository have been enhanced and reorganized with AI assistance to make the template more accessible for public use.

## Features

- Custom Bilkent color scheme (Pantone Reflect Blue and Flag Red)
- University logo in header
- Clean, professional layout
- Multiple block styles (regular, alert, example)
- Support for multi-column layouts
- Built-in reference formatting

## Quick Start

### Prerequisites

- LaTeX distribution (TeX Live, MiKTeX, or MacTeX)
- Required packages: `beamer`, `currfile`, `graphicx`, `booktabs`, `xcolor`, `tikz`

### Usage

1. Clone or download this repository
2. Edit `main.tex` with your content
3. Compile with `pdflatex`:

```bash
pdflatex main.tex
```

Or use your preferred LaTeX editor (TeXShop, TeXstudio, Overleaf, etc.).

## File Structure

```
├── main.tex                    # Main presentation file (edit this)
├── theme/
│   ├── beamerthemeBilkent.sty     # Main theme file
│   ├── beamercolorthemeBilkent.sty # Color definitions
│   └── logo-uni.png               # University logo
├── figures/                    # Place your figures here
└── latex_build/               # Compilation artifacts (auto-generated)
```

## Customization

### Presentation Metadata

Edit these lines in `main.tex`:

```latex
\title[Short Title]{Your Presentation Title}
\author[Short Name]{Your Name}
\date{\today}
```

### Available Colors

The theme defines two custom colors:
- `pantonereflectblue` - RGB(0, 83, 160)
- `flagred` - RGB(237, 29, 36)

Use them with: `\textcolor{pantonereflectblue}{Your text}`

### Block Types

Three block styles are available:
- `\begin{block}{Title}` - Regular block
- `\begin{alertblock}{Title}` - Alert/warning block
- `\begin{exampleblock}{Title}` - Example block

### Frame Options

- `[c]` - Centered content
- `[t]` - Top-aligned content
- `[b]` - Bottom-aligned content

## Example Slides

The template includes examples for:
- Title slide
- Itemized lists
- Block layouts
- Multi-column layouts
- Tables with references
- Color usage
- Conclusion slide

## License

MIT License - see [LICENSE](LICENSE) file for details.

This template is based on the original work by Alican Büyükçakır (2019), also released under the MIT License.

## Credits

- Original Bilkent theme by [Alican Büyükçakır](https://github.com/abuyukcakir) (2019)
- Template documentation and examples enhanced with AI assistance

## Git Setup

To push this template to GitHub:

```bash
git init
git add .
git commit -m "Initial commit: Bilkent Beamer template"
git branch -M main
git remote add origin https://github.com/yourusername/bilkent-beamer-template.git
git push -u origin main
```

## Support

For issues or questions, please open an issue on GitHub or contact your local LaTeX support.

