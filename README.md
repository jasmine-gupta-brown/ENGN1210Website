# ENGN1210Website

Steps to Creating a New Page for the Website
  1. Create a New Folder and File by clicking New File and titling it FolderName/FileName
  2. Copy and paste html frame work from "Page Template.html" File. Save and create files by clicking Commit Changes
  3. Convert desired .tex to .html
  4. Copy BODY of new html file
  5. Paste body into section of template labeled "Unique Page Content". Save changes by Commit Changes (or Save/Commit/Push using Desktop       App)
  6. In GitHub Click into the New Folder and Upload Files to add all related images
  7. If this is a New Section, add the a new button to "Links for the Side Menu"


To Convert .tex to .html:
1. download Pandoc
2. In terminal use the following commands to convert the file:

  Option 1: .tex to .html with Equations
  pandoc FileToConvert.tex -o ConvertedFile.html --mathjax

  Option 2: To specify files types, incase there are other types of files you want to convert
  pandoc FileToConvert.tex -f latex -t html -s -o ConvertedFile.html 

