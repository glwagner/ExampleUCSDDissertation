# exampleUCSDDissertation

This repository contains production files for an example dissertation 
formatted in the style required by PhD dissertations from the 
University of California, San Diego.

The example text is taken from [Gregory L. Wagner][]'s dissertation
awarded in May 2016. The [original and official dissertation][] titled
'On the coupled evolution of oceanic internal waves and quasi-geostrophic 
flow' can be downloaded from ProQuest. An [informal, single-spaced and 
differently formatted version][] can be downloaded from Gregory's website.

Apart from satisfying the required style for UCSD PhD dissertations, this example
also implements

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

In addition, many custom latex commands which are peculiar to this particular 
example are defined in the `dissertationCustomCommands.sty` file.

[Gregory L. Wagner]: https://glwagner.github.io
[original and official dissertation]: http://pqdtopen.proquest.com/doc/1799665054.html?FMT=ABS
[informal, single-spaced and differently formatted version]: https://glwagner.github.io/assets/pdf/glwDissertation.pdf







