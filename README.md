# Resume README

## Overview

This repository contains a LaTeX template for my resume. The resume is designed to showcase my professional experiences, skills, and education in a clean and organized format.

## Files Included

- `resume.tex`: The main LaTeX source file for the resume.
- `resume.pdf`: A compiled PDF version of the resume.
- `resume.cls`: A custom LaTeX class file used for styling the resume (if applicable).
- `bibtex.bib`: A BibTeX file for any references or publications (if applicable).

## Requirements

To compile the resume, you will need the following LaTeX packages:

- `geometry`
- `fontspec`
- `titlesec`
- `enumitem`
- `xcolor`
- `hyperref`

You can install these packages using your LaTeX distribution's package manager.

## How to Compile

1. Ensure you have a LaTeX distribution installed (e.g., TeX Live, MiKTeX).
2. Open a terminal or command prompt.
3. Navigate to the directory containing `Resume.tex`.
4. Run the following command to compile the resume:

   ```bash
   pdflatex resume.tex
   ```

5. If you are using BibTeX for references, you may need to run:

   ```bash
   bibtex resume
   pdflatex resume.tex
   pdflatex resume.tex
   ```

6. The compiled PDF will be available as `resume.pdf`.

## Customization

Feel free to customize the `resume.tex` file to better suit your needs. You can modify sections, add or remove content, and adjust formatting as necessary.

## Contact

For any questions or feedback, please contact me at [abishkakrishnakumar@gmail.com].

---

Feel free to adjust the sections according to your specific needs and the contents of your resume.
