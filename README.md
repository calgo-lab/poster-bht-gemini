# BHT Poster Template

This is a fork of the [Gemini] theme adjusted to the Berlin University of Applied Sciences and Technology (BHT) [corporate design]. Checkout the [original README](./original_README.md) file for more background information.

![](.assets/poster.jpg)


## Changes

* Use colors regarding [BHT style guide] + `light` versions that are 90% lighter
* Add BHT logo to the header
* Use the [BHT Case font]


## Dependencies

* A TeX installation that includes [LuaTeX]
    * You also need `latexmk` if you want to use the provided `Makefile`
* LaTeX package dependencies including beamerposter (these usually come with
  your TeX installation, but if not, you can get them from [CTAN])
* [BHT Case font] must be installed on your computer


## Usage

1. Copy the files in this repository (or clone the repository)
2. In `poster.tex`, set up your paper size, column layout, and scale the
   content as necessary
3. (Optional) Make a copy of `beamercolorthemebht.sty`, update the `\usecolortheme`
   line in `poster.tex`, and theme the poster to your liking
4. Run `make` to build your poster or use your favorite app (take care of using [LuaTex]!)


## FAQ

See the [FAQ] in the Wiki for answers to frequently asked questions such as how
to add an institution logo to the poster.


## License

Copyright (c) Anish Athalye. Released under the MIT License. See
[LICENSE.md][license] for details.


[Gemini]: https://github.com/anishathalye/gemini
[corporate design]: https://www.bht-berlin.de/corporate-design
[BHT style guide]: https://www.bht-berlin.de/fileadmin/oe/pressestelle/dokumente/BHT-Styleguide.pdf
[BHT Case font]: https://www.bht-berlin.de/schrift
[LuaTeX]: http://www.luatex.org/
[CTAN]: https://ctan.org/
[license]: LICENSE.md
[FAQ]: https://github.com/anishathalye/gemini/wiki/FAQ
