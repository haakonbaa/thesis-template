# Thesis Template

A ![https://www.latex-project.org/](/build/latex.svg) thesis template licensed under the
[Creative Commons Zero v1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/)
license.

---

## Preview

**View / Download**: [main.pdf](https://raw.githubusercontent.com/haakonbaa/thesis-template/main/build/main.pdf)

## Motivation

Many thesis templates are distributed under restrictive licenses, limiting your
ability to use or modify them without attribution. This template is licensed
under the **CC0 license**, granting you complete freedom to use, modify, and
redistribute it without any obligation to credit the original author.

## Usage Instructions

The $\LaTeX$ source code is located in the `src` directory. To generate the PDF,
simply run `pdflatex` on the `main.tex` file.

Alternatively, you can use the `Makefile` provided in the root directory to
build the PDF. The `Makefile` ensures the document is compiled the correct
number of times to resolve all references. Use the following command to build
the PDF:

```sh
make all
```

To compile without resolving references, use the `small` target:

```sh
make small
```

## Acknowledgements

This template draws inspiration from the
[ntnu-itk-thesis-template](https://github.com/mortenfyhn/ntnu-itk-thesis-template)
by [Morten Amundsen](https://github.com/mortenfyhn), originally released under
the MIT license. Relicensing was performed with the author’s permission.

While attribution to me or the original author is not required, it is always
appreciated.

## License Information

This repository is licensed under the [CC0 license](/LICENSE).

**Note:** The NTNU logo included in
[./src/assets/NTNU.svg](/src/assets/NTNU.svg) is the property of the Norwegian
University of Science and Technology. It is used here for illustrative purposes
only. For details on usage rules, please refer to the
[NTNU logo usage guidelines](https://i.ntnu.no/wiki/-/wiki/Norsk/Bruksregler+for+NTNU-logoen).

---

Created by [Håkon Bårsaune](https://github.com/haakonbaa) <br>
Originally released on [GitHub](https://github.com/haakonbaa/thesis-template)
