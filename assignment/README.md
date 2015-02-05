# Assignment

## Intro
This template provides a clean, consistent structure suitable for medium-length homework assignments. Some features include:

  1. A cover page with the course name, assignment name, student name, and date.
  2. A table of contents with a listing of all sections and subsections.
  3. A notes section for important notes to the reader. By default, this contains a disclaimer (See [`notes.tex`](notes.tex)).
  4. Consistent headers and footers with the assignment name, student name, current section names, and page number.
  5. A new environment, `Proof` (replaces `proof`), to make proofs stand out more from the body text.


## Setup
After copying this template to a new directory, all you need to do is replace the values in [`config.tex`](config.tex) with proper values for your assignment.

If you want to modify the template (add new environments, use other packages, etc.), make your changes in [`setup.tex`](setup.tex).

## Usage
Once you have set up the document to your liking, you can start writing in `main.tex`.

This template requires the usage of `pdflatex`. It will not work with DVI output. To compile your assignment from the command line, use

    pdflatex main.tex

This should generate a file, `main.pdf`, with the generated transcript. You may need to compile multiple times for everything to be formatted correctly.


## Example
See [`sample.pdf`](sample.pdf)


## Notes
When you compile your assignment, the table of contents might not get updated and some references may appear as `??`. If this is the case, you'll likely see some output/warning messages telling you to re-compile the document to fix them. Most of the time, this should work. If it does not give you the desired results, make sure the rest of your document is formatted properly.
