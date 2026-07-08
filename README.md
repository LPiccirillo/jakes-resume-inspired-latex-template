# LaTeX Resume Template

A clean, ATS-friendly résumé template written in LaTeX. The project is designed to provide a modular and easily customizable structure suitable for academic, technical, and professional résumés.

## Features

- Clean one-page résumé layout
- Modular design with formatting separated into a dedicated `.sty` file
- Built-in bibliography support using **biblatex** (APA 7th edition)
- Publications section
- Sections for:
  - Profile
  - Professional Experience
  - Education
  - Projects
  - Skills
  - Publications
- Optional handwritten signature
- ATS-friendly PDF output with Unicode support
- Font Awesome icons for contact information
- Ready-to-use template with anonymized placeholder content

## Project Structure

```text
.
├── resume-LaTeX-template.tex   # Main CV document
├── resume-style.sty            # Custom commands and formatting
├── references.bib              # Publication database
├── image/
│   └── handwritten_signature.png
└── README.md
```

## Compilation

The template uses **biblatex** with the **Biber** backend.

Compile using:

```text
pdflatex resume
biber resume
pdflatex resume
pdflatex resume
```

or configure your LaTeX editor to use **Biber**.

## Customization

Simply edit the placeholder content in `resume-LaTeX-template.tex`:

- Personal information
- Professional experience
- Education
- Projects
- Skills
- Publications

Publication entries are stored separately inside `references.bib`.

The document formatting and reusable commands are defined in `resume-style.sty`, making it easy to maintain or extend the template.

## What's Different from the Original Template?

This template is based on [**Jake's Resume (Anonymous)**](https://www.overleaf.com/latex/templates/jakes-resume-anonymous/cstpnrbkhndn), but has been substantially reorganized, extended, and adapted with additional functionality.

Main changes include:

- separation of all formatting commands into a dedicated `resume-style.sty` file;
- improved code organization and documentation;
- new reusable commands for projects, skills, profile, and publications;
- integrated bibliography management using **biblatex** and **Biber**;
- dedicated `references.bib` file for publication management;
- support for APA-formatted publication lists;
- optional handwritten signature section.

## Credits

This project is derived from:

- **Jake's Resume (Anonymous)** (Overleaf)  
  https://www.overleaf.com/latex/templates/jakes-resume-anonymous/cstpnrbkhndn  
  License: **Creative Commons Attribution 4.0 International (CC BY 4.0)**

Jake's Resume is itself based on:

- **sb2nov/resume**  
  https://github.com/sb2nov/resume  
  License: **MIT License**

Many thanks to the original authors for making their work openly available.

## License

This repository is released under the **MIT License**.

The MIT License was chosen because this project is a LaTeX template intended for reuse, modification, and redistribution. The license provides a simple and permissive framework that allows others to adapt the template for personal, academic, or professional purposes while preserving appropriate attribution.

The original works remain subject to their respective licenses:

- **Jake's Resume (Anonymous)** — Creative Commons Attribution 4.0 International (CC BY 4.0)  
- **sb2nov/resume** — MIT License

Please retain the original attributions and comply with the licenses of the upstream projects when redistributing modified versions.