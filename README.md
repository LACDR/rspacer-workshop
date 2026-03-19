# Workshop rspacer

Materials and instructions for workshops on using rspacer together with RSpace and LACDR-ISA templates.

These tutorials demonstrate how R can be used to generate structured reports and automatically upload these to an RSpace electronic lab notebook (ELN).

Contributions and suggestions are welcome. Please open an issue or submit a pull request if you notice problems or have improvements.

---

Feel free to help us improve these materials, we are very happy with any suggestions. You can reach us by either submitting an issue or directly fix a problem using a pull request.

## Introduction

This repository contains materials and instructions for workshops on using rspacer and LACDR-ISA templates together with RSpace.

At the point of writing, the workshops are step by step guides with example documents, 
and are meant as LACDR-specific extensions to the tutorials on the [rspacer website](https://lacdr.github.io/rspacer/articles/), 
and instructions on the [LACDR-ISA](https://github.com/LACDR/LACDR.ISA) package page.

You can also find our preprint [here](https://lacdr.github.io/rspacer-manuscript)

## Links to tutorials

-   [Tutorial 1](Tutorial_1_using_R_projects/Tutorial_1.md)
-   [Tutorial 2](Tutorial_2_using_LACDR-ISA/Tutorial_2.md)
-   [Tutorial 3](Tutorial_3_document_from_html/Tutorial_3.md)
-   [Tutorial 4](Tutorial_4_document_from_excel/Tutorial_4.md)
-   [Installation instructions](#installation-instructions)

## Tutorial details

### Tutorial 1 - Using R Projects

After this tutorial, you will be able to:

-   Explain how an R project can make your research more reproducible
-   Set up your own R project in RStudio

### Tutorial 2 - Using LACDR-ISA Quarto and Excel templates

After this tutorial, you will be able to:

-   Explain the benefits of using structured templates
-   Apply the Investigation-Study-Assay (ISA) structure to your own research projects
-   Use LACDR-ISA Templates in both RStudio and Excel
-   Adapt the LACDR-ISA Templates to your own research needs

### Tutorial 3 - Document from HTML

After this tutorial, you will be able to:

- 	Generate a Quarto report
-   Upload a rendered Quarto HTML report as an RSpace Document using [rspacer](https://lacdr.github.io/rspacer).

### Tutorial 4 - Document from Excel

After this tutorial, you will be able to:

-   Upload information from Excel, CSV or TSV files to specific fields in an RSpace Document using [rspacer](https://lacdr.github.io/rspacer).

## Tutorials to be written

### Tutorial 5 - Reusing data from RSpace

After this tutorial, you will be able to:

-   Download metadata from RSpace using [rspacer](https://lacdr.github.io/rspacer)
-   Reuse stored metadata in R
-   Upload metadata to an RSpace lab journal entry 

The functionality already exists, but we have not yet written the tutorial. For now, read the Help pages and the vignette of: `rspacer::folder_tree`, `rspacer::document_list_attachments` and `rspacer::file_download`.

### Tutorial 6 - Add attachments to an existing document

After this tutorial, you will be able to:

-   Upload files to RSpace from R using [rspacer](https://lacdr.github.io/rspacer)
-   Attach files to an existing document using [rspacer](https://lacdr.github.io/rspacer)

### Tutorial 7 - append information to an assay 1.

-   For now, see our [preprint](https://lacdr.github.io/rspacer-manuscript) and our [website](https://lacdr.github.io/rspacer/index.html)
-   Use `rspacer::document_append_from_html` to get this done.

## Installation instructions {#installation-instructions}

Requirements: you need to have R Studio and R installed, and you need an account on RSpace.

1.  Clone or download this repository
2.  Open the repository as an RStudio project
3.  Navigate to a tutorial folder
4.  Open the `Tutorial_X.md` file
