# MakeWebfont
Small Shellscript to convert OTF/TTF to WebFonts on Linux.
Based on http://www.koffeinfrei.org/2012/08/06/how-to-generate-a-webfont-kit-with-open-source-tools

 - Install fontforge via your Package Manager.
 - Download and `make` [https://github.com/metaflop/ttf2eot](ttf2eot) and [http://people.mozilla.org/~jkew/woff/](sfnt2woff)
 - Copy the two binaries and this script to `~/bin` or somewhere else on your PATH
 - call with a .ttf or .otf font-name: `make-webfont foo.otf`
