## Seville LaTeX beamer theme 

![Showcase](demo/demo.gif)

Do you like this? Have a look at the [PDF](demo/demo.pdf) and the [LaTeX code](demo/demo.tex).

## How to use

Copy `beamerthemeseville.sty` to your beamer presentation's folder, add

```
\usetheme{seville}
```

to the preamble.

If you're going to use it often, you can place `beamerthemeseville.sty` somewhere in your TeX distribution tree instead. 

## Options

```
\usetheme[options]{seville}
``` 
where `options` may be some of these (comma-separated):


- `alegreya` uses Huerta Tipográfica's [Alegreya Sans](https://www.huertatipografica.com/es/fonts/alegreya-sans-ht) font.
- `lmodern` uses the Latin Modern font, for a more classical LaTeX look.
- `fira` uses Mozilla's [Fira Sans](https://mozilla.github.io/Fira/) font and its [Fira Math](https://github.com/firamath/firamath) companion.
- `noto` uses Google's [Noto](https://fonts.google.com/noto) font.
- `academicons` uses [Academicons](https://jpswalsh.github.io/academicons/) for some links.

Since the first four options select the main fonts, you should only use one of them. The last one is compatible with the rest.

The last three options require compilation with **LuaLaTeX**. You can use **XeLaTeX** instead, but this forces you to install the Fira and Noto fonts in your system, if you use these options. In fact, if you use Fira, you also have to install [Euler Math](https://www.ctan.org/tex-archive/fonts/euler-math) (used for calligraphic and fraktur math fonts) and [XITS](https://github.com/aliftype/xits) (used for missing symbols in Fira Math).

## Acknowledgements

This theme is inspired by Matthias Vogelgesang's beautiful [Metropolis theme](https://github.com/matze/mtheme/). It uses the [Solarized](https://ethanschoonover.com/solarized/) color palette, Adobe's [Source Sans Pro](https://fonts.adobe.com/fonts/source-sans) and [Source Code Pro](https://fonts.adobe.com/fonts/source-code-pro) fonts, icons by [Font Awesome](https://fontawesome.com), and a lovely logo by [Graficatessen](https://graficatessen.es/), along with many other FOSS things. I'm grateful to all creators that make this possible.

## Why this theme?

The Metropolis theme is unfortunately unmaintained. Changes in its dependencies have caused glitches. Seville is extremely simple. It is therefore easy to maintain although it has way less options. Seville is probably a drop-in replacement for people that was using Metropolis without tweaking too much.

I've also added some goodies for mathematicians and academics in general. 

## Contributing

If you'd like to use this theme but you feel you need some missing options or features, let me know by opening an issue. Or even better, make a pull request adding what you need.

## TODO

- [ ] Cleanup and comment `beamerthemeseville.sty`.
- [ ] Check missing symbols in Fira Math and find replacements.
- In case anyone is interested:
  - [ ] Documentation.
  - [ ] Extra features.
  - [ ] [CTAN](https://www.ctan.org).
  - [ ] Overleaf.

## License

Copyright 2022 F. Muro

This work may be distributed and/or modified under the
conditions of the LaTeX Project Public License, either version 1.3
of this license or (at your option) any later version.
The latest version of this license is in

[http://www.latex-project.org/lppl.txt](http://www.latex-project.org/lppl.txt)

and version 1.3 or later is part of all distributions of LaTeX
version 2005/12/01 or later.

This work has the LPPL maintenance status `maintained'.
 
The Current Maintainer of this work is F. Muro.

This work consists of the file beamerthemeseville.sty.
