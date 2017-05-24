# exampleUCSDDissertation

This repository contains production files for an example dissertation 
formatted in the style required by PhD dissertations from the 
University of California, San Diego.

The example text is taken from [Gregory L. Wagner][]'s dissertation
awarded in May 2016. The [original and official dissertation][] titled
'On the coupled evolution of oceanic internal waves and quasi-geostrophic 
flow' can be downloaded from ProQuest. An [informal, single-spaced and 
differently formatted version][] can be downloaded from Gregory's website.

## Nota bene

* The [Creative Commands NonCommercial-NoDerivatives][] copyright was applied 
to the original dissertation. This copyright permits free distribution, requires
attribution and prohibits commercial use.

* The figure labels that appear on the 'List of Figures' can be changed independently 
from the figure captions by using the 
`\caption[Displayed short name]{Long descriptive caption}` format. An example is given in 
figure 1.1 in chapter 1.1.  

* Many custom latex commands which are peculiar to this particular 
example are defined in the `dissertationCustomCommands.sty` file. New commands can 
also be defined in the main `tex` document, and there is no need to have a separate
file or define custom commands at all.

* There is some flexibility in formatting both the 'VITA' page 
and the 'EPIGRAPH' page. The exact format used in this example is not
required.

## Features 

Apart from satisfying the required style for UCSD PhD dissertations, this example
also implements:

* Code and Table-of-Contents formatting for both in-chapter 
appendices ('subappendices') as well as full-text appendices that appear
after the last chapter in the document. This feature is provided by the 
`appendix` package and code included in the `dissertationTableContentTweaks.sty`
style file.

* Rotated figures through the `lscape`, `scrextend`, and `rotating` packages,
as well as a code fragment in the `dissertationRotatedFigures.sty` style file.
An example rotated figure is given in chapter 3C. Rotated figures are 
useful for very large figures intended to fill an entire page.

* Hyperlinks through the `\url{}` command which appear in the document
as unformatted, black roman text.

## Lastly 

To all aspiring dissertation writers --- good luck, of course.

[Gregory L. Wagner]: https://glwagner.github.io
[original and official dissertation]: http://pqdtopen.proquest.com/doc/1799665054.html?FMT=ABS
[informal, single-spaced and differently formatted version]: https://glwagner.github.io/assets/pdf/glwDissertation.pdf
[Creative Commands NonCommercial-NoDerivatives]: https://creativecommons.org/licenses/by-nc-nd/4.0







