# Columbia Dissertation LaTeX Template

I created this generic Colubmia Dissertation LaTeX template based on a classmates dissertation. I wanted to start with something simple and fresh and be sure it compiled correctly. I don't know the origin story of the formatting, but there was a README in with the other files that said:

"LaTeX template files for the PhD thesis format required by Columbia.
Created by Agustin Gravano from original files by Panagiotis Ipeirotis.
On Unix-like systems, run `make' to create a DVI file, or `make pdf' 
to create a PDF file. Good luck!"

Credit where credit is due!

## To use

The .tex file for the introduction, each chapter, and conclusion are each stored in separate folders for organizational purposes. You can have as many chapters as you want, you will just need to add them into the Dissertation.tex file in a similar style to Chapters 1 through 3 in this template. Note that Dissertation.tex also has an option to add Appendices that is currently commented out but the sample structure is there.

The FrontMatter folder contains tex files for the abstract, acknowledgements, and title page. The TitlePage.tex file loads all of the needed packages. If you need to include any special packages or define special functions, there is a section at the botton for your own additions.

To use, just compile the Dissertation.tex file using PDFLaTeX. I think  you have to run it a few times to get the table of contents.
