These versions of the `drangreport.sty` and `drangsymbols.sty` are modified versions of the LaTeX style files originally written by Dr. Drang and posted at [http://www.https://github.com/drdrang/drangreport/](github.com/drdrang/drangreport/).

These files are mostly used for typing lectures notes in an undergraduate mathematics course. Thus, the symbols and shortcuts are chosen primarily to allow me to write as fast as I can during lectures.

It's a hassle to install fonts and compile with LaTeX, so I use XeLaTeX. This allows me a much wider variety of fonts with minimal effort.

Large sections of the original code are unchanged; these are mostly superficial edits.

<hr />

Dr. Drang's original README:

The `drangreport.sty` file is a redacted version of the LaTeX style file for reports I discussed in these two blog posts ([first][1] and [second][2]). It includes provisions for:

* Plates, as distinct from figures.
* A title page.
* A digitized signature.
* A variety of font combinations.
* The sort of paragraph spacing, margins, and heading styles I prefer.

Most of the font combinations use the Mathematica fonts. You'll need both [these virtual font files][3] and the [version 4.1 PostScript files][4]. To get the fonts on a non-Windows machine, use the link at the bottom of the page to download the .exe file and unzip "by hand."

    unzip MathFonts_Type1_42.exe

You'll need to know a fair amount about how a TeX system uses fonts to install these correctly and get your system to know they're there.

The `drangsymbols.sty` file is a set of convenient commands for units and small fractions.


[1]: http://www.leancrew.com/all-this/2011/04/text-files-and-me-part-3/
[2]: http://www.leancrew.com/all-this/2011/04/text-files-and-me-part-3-5/
[3]: http://library.wolfram.com/infocenter/MathSource/3200/
[4]: http://support.wolfram.com/technotes/fonts/windows/latestfonts.html

