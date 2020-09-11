# PdfMax
PdfMax is a library built on [ImageSharp](https://github.com/SixLabors/ImageSharp), [PdfPig](https://github.com/UglyToad/PdfPig) and [PdfSharpCore](https://github.com/ststeiger/PdfSharpCore) to provide a unified interface to manipulate PDFs.

## License
Each of `ImageSharp`, `PdfPig` and `PdfSharpCore` provides their own license. This project uses the library via `nuget` but the licenses still apply. My work which builds on top of those libraries, is licensed under:

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

## Community
[![Gitter](https://badges.gitter.im/PdfMax/community.svg)](https://gitter.im/PdfMax/community?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

This is a community driven project with intent to make this production ready and as fast as possible. With that goal in mind, a Gitter channel is available for conversations for immprovements and problems. Please try contacting developers in that channel before creating an issue there.

## Features
- Extraction
    - Extract individual words from pages of a PDF
    - Extract bounding box of a word
    - Extract images from pages
- Manipulation
    - Annotate individual words

## Future
The ultimate goal is to move away from `PdfPig` and `PdfSharpCore` and replace the functionalities they provide with a new core implmenetation of PDF.

### Goals:
1. Replace *PdfSharpCore*.
2. Replace *PdfPig* to extract text and their position in stable fashion.
3. ImageSharp is going for a dual-license. It would make sense to move away from that as well eventually. Suggestions welcomed.
