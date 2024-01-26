## Uploading template to overleaf
1. Download these files as zip by clicking **Code** -> **Download ZIP**
2. Go to http://www.overleaf.com
3. Create an account.
4. On the left-hand side click **New Project** -> **Upload Project**
5. Choose the ZIP file you downloaded.
6. Edit the CV Template.
7. Compile and download the PDF.

## Requirements and Compilation
* AltaCV uses [`fontawesome`](http://www.ctan.org/pkg/fontawesome) and [`academicons`](http://www.ctan.org/pkg/academicons); they're included in both TeX Live 2016 and MikTeX 2.9.
* Loading `academicons` is optional: enable it by adding the `academicons` option to `\documentclass`.
* Can now be compiled with pdflatex, XeLaTeX and LuaLaTeX!
* However if you're using `academicons`, you _must_ use either XeLaTeX or LuaLaTeX. If the doc then compiles but the icons don't show up in the output PDF, try compiling with LuaLaTeX instead.
* The samples here use the [Lato](http://www.latofonts.com/lato-free-fonts/) font.
* You can use page2sidebar.tex with the same syntax if your CV exceeds one page with the information on the right-hand side.