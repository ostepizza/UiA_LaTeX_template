# UiA LaTeX Template

This repository contains a LaTeX template for a generic UiA report. It provides a UiA front-page, preset fields, example structure, as well as example Appendix structure with front-pages.

## Features

- Default UiA front page with UiA logo, title, various info, and confirmations that are usually required
- Front matter and main matter (roman numerals before main text, then arabic)
- Example content (Sections, Figures, Tables, References)
- Appendix examples with front pages (This appendix contains...)
- Various layout setups (margins, header title, etc.)

## Usage
### Using with [Overleaf](https://www.overleaf.com/)
1. Download [release](https://github.com/ostepizza/UiA_LaTeX_template/releases) (.zip file)
2. Navigate to project overview on Overleaf 
3. Create new project, "Upload Project"
4. Add .zip
5. Modify files as needed, add files as needed, and compile

### Using locally
1. Download and install a LaTeX compiler (For example [TeX Live](https://tug.org/texlive/)), if you don't have one already
2. Download [release](https://github.com/ostepizza/UiA_LaTeX_template/releases) (.zip file)
3. Modify files as needed, add files as needed, and compile

## Contents

- `main.tex`: Main LaTeX document file, where subfiles/sections are added.
- `chapters/`: Directory for individual chapters or sections.
- `img/`: Directory for storing images used in the document.
- `ref/`: Directory for storing reference files (e.g., BibTeX files).
- `appendix/`: Directory for appendix files.
- `template/packages.tex`: Contains packages for the template.
- `template/frontpage.tex`: Contains the title page content.
- `template/appendixprepare.tex`: Contains setup for the appendix.
- `template/othersetup.tex`: Contains other setup settings for the template.

## Example

Placeholder text

## Contributions

Contributions are welcome! If you have suggestions, improvements, or bug fixes, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.