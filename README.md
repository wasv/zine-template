# zine-template
LaTeX template for creating a zine. Builds using GitHub actions and tectonic.

## Build Instructions

I used [tectonic](https://tectonic-typesetting.github.io/en-US/index.html) for building and dependency management.

Once tectonic is installed, run `tectonic pages.tex && tectonic zine.tex` and it should take care of the rest.

## Usage Instructions

The `pages.tex` file can be edited to add digital content, which is then typeset and arranged based on `zine.tex`,
or `pages.tex` can be left blank, so that `zine.pdf` can be printed and drawn on.

## Folding Instructions

Print `zine.pdf` then cut between pages 3+8 and between 4+7. Then fold horizontally the long way, then fold as shown below.

![Folding Diagram for an 8-sided single sheet zine 1](https://upload.wikimedia.org/wikipedia/commons/0/01/Zinemaking-folding-8cut-4.png)
![Folding Diagram for an 8-sided single sheet zine 2](https://upload.wikimedia.org/wikipedia/commons/b/be/Zinemaking-folding-8cut-5.png)
![Folding Diagram for an 8-sided single sheet zine 3](https://upload.wikimedia.org/wikipedia/commons/1/1d/Zinemaking-folding-8cut-6.png)
![Folding Diagram for an 8-sided single sheet zine 4](https://upload.wikimedia.org/wikipedia/commons/3/37/Zinemaking-folding-8cut-7.png)

For more detailed (possibly clearer) instructions see the section titled "An 8-sided zine from 1 sheet with 1 cut"
in [The Zine Making WikiBook](https://en.wikibooks.org/wiki/Zine_Making/Putting_pages_together).
