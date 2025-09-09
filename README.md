# swe-latex-resume

A clean, compact, minimal LaTeX resume template optimized for software engineering applications.

- Modular design for easy customization
- Optimized spacing for single-page resumes  
- Clean, professional formatting

## Usage

Compile the resume using any LaTeX compiler (pdflatex recommended):
```bash
pdflatex resume.tex
```

## Structure

- `resume.tex` - Main LaTeX file that imports all components
- `src/` - Modular resume sections:
  - `custom-commands.tex` - LaTeX command definitions (`\name`, `\sectionhead`, `\daterange`, etc.)
  - `heading.tex` - Name and contact information
  - `education.tex` - Education section
  - `experience.tex` - Work experience
  - `projects.tex` - Project descriptions
  - `skills.tex` - Technical skills
  - **Optional sections** (commented out by default):
    - `awards.tex` - Academic/professional awards and honors
    - `certifications.tex` - Professional certifications
    - `clearance.tex` - Security clearance information
    - `courses.tex` - Relevant coursework
    - `leadership.tex` - Leadership experience and roles
    - `opensource.tex` - Open source contributions
    - `publications.tex` - Research publications and papers

## Customization

Replace placeholder content with your information. Comment out irrelevant sections and reorder projects based on job requirements. Optional sections are commented out in `resume.tex` by default.

For automated tailoring to job descriptions, check out my project [Loom](https://github.com/ggfincke/loom) - a CLI tool designed to help customize resumes for specific job applications.

## License

MIT License - see LICENSE file for details.
