# Resume

~ Howdy Recruter


# Note to self
Install Compiler (Linux): `sudo apt install texlive-full`
Compile using: `pdflatex yourfile.tex`
Or with a build folder as an object dump:
```sh
pdflatex -output-directory=build Resume.tex && rm build/Resume.{aux,log,out,toc,synctex.gz}
```