uealttr - A letter class for the University of East Anglia (UEA)
===============================================================

The `uealttr` class is version of the standard LaTeX letter
class customised for use at the University of East Anglia (UEA).
It is based on the Word template made available by the
Publications Office. Although aimed at UEA, the class is readily
adapted to other organisations.

Installation
------------

The package is supplied in `.dtx` format and as a pre-extracted
`.zip` file, `uealttr.tds.zip`. The later is most convenient for
most users: simply unzip this in your local `texmf` directory.
If you want to unpack the `.dtx` yourself, running `tex
uealttr.dtx` will extract the package whereas `latex
uealttr.dtx` will extract it and also typeset the documentation.

Typesetting the documentation requires a number of packages in
addition to those needed to use the package. This is mainly 
because of the number of demonstration items included in the 
text. To compile the documentation without error, you will 
need the packages:
 - `hypdoc`
 - `listings`
 - `lmodern`
 - `mathpazo`
 - `microtype`