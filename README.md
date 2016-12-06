# LaTeX Tutorial of the Fachschaft WIAI

This tutorial for the typesetting system [**LaTeX**](https://www.latex-project.org) comprises the most important topics for writing a beautiful, high-quality thesis or scientific paper.

* Basic formatting
* Footnotes
* Images
* Formulas
* Tables
* Enumerations
* Literature management
* Best practices for writing large documents 

The tutorial is designed as a **one-day crash course** for **non-programmers** to learn LaTeX.
The didactic concept is an alteration between **lectures** about the beforementioned topics and **hands-on exercises** where the learner's task is to recreate simple documents using LaTeX. 


## Contents of this Repository

* [**English Slides**](English/beamer)
* [**English Exercises**](English/tasks)
* [**German Slides**](Deutsch/beamer)
* [**German Exercises**](Deutsch/aufgaben)


## Software Used

To work on this tutorial it is required to install
* an up-to-date [**LaTeX compiler**](https://www.latex-project.org/get) (software that translates your LaTeX code into a beautiful PDF),
* a **LaTeX editor**, e.g., [TeXstudio](http://www.texstudio.org), &
* any **PDF viewer**.

## Compiling the Sources

The PDFs can be created by compiling the LaTeX sources located in [English/beamer](English/beamer) and [Deutsch/beamer](Deutsch/beamer).
The compiler has to be invoked via `pdflatex presentation.tex` at least two times.
For convenience there are `Makefile`s available for building the the presentation and the handout version of the tutorial
```Makefile
# Usage
make handout      # Compiles the sources to handout.pdf without organisational slides
make presentation # Compiles the sources to presentation.pdf used for presentation

```


## Background

Since 2009 this tutorial is offered for the freshman and other interested students at the University of Bamberg.
It is powered by [Prof. Dr. Udo R. Krieger](https://www.uni-bamberg.de/ktr/mitarbeiter/krieger), [Professorship for Computer Science](https://www.uni-bamberg.de/ktr), Communication Services, Telecommunication Systems and Computer Networks at the [University of Bamberg](https://www.uni-bamberg.de).

The original authors were

* Marcel Großmann,
* Steffen Illig,
* Martin Sticht, &
* Michael Timpelan,

and the tutorial is maintained by members of the [Fachschaft WIAI](https://wiai.de) (the students' union of the faculty).


## Contributing

You are very welcome to suggest improvements/fix errors by submitting an [issue](issues) or by creating a pull request. Note that due to the temporal limitations of a one-day tutorial, we might not merge new sections/features to maintain the scope. In case of doubts just open an [issue](issues) so we can discuss your suggestions before you implement them.


## License

The tutorial is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/). Please attribute **Fachschaft WIAI, University of Bamberg** as author.

---
**This license means that you are free to:**

* **Share** — copy and redistribute the material in any medium or format
* **Adapt** — remix, transform, and build upon the material

for any purpose, even commercially.

The licensor cannot revoke these freedoms as long as you follow the license terms.

**Under the following terms:**

* **Attribution** — You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.
* **ShareAlike** — If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.
---

This is the [short version](https://creativecommons.org/licenses/by-sa/4.0/) of the license, please refer to the [full legal text](https://creativecommons.org/licenses/by-sa/4.0/legalcode) for the details.

