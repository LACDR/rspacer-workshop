# Workshop rspacer

Materials and instructions for workshops on how to use rspacer and LACDR-ISA templates.

## Introduction

This repository contains materials and instructions for workshops on how to use rspacer and LACDR-ISA templates in combination with RSpace.

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

### Tutorial 1 - using R projects

After this tutorial, you will be able to:

-   Explain how an R project can make your research more reproducible
-   Set up your own R project in RStudio

### Tutorial 2 - using LACDR-ISA Quarto and Excel templates

After this tutorial, you will be able to:

-   Explain why using templates can benefit your research
-   Apply the Investigation-Study-Assay structure to your own research projects
-   Use LACDR-ISA Templates in RStudio and in Excel
-   Adapt the LACDR-ISA Template to your own research needs

### Tutorial 3 - document from HTML

After this tutorial, you will be able to:

-   Upload a rendered Quarto HTML report as an RSpace Document using [rspacer](https://lacdr.github.io/rspacer).

### Tutorial 4 - document from Excel

After this tutorial, you will be able to:

-   Upload information from Excel, CSV or TSV files to specific fields in an RSpace Document using [rspacer](https://lacdr.github.io/rspacer).

## Future tutorials to be written

### Tutorial 5 - reuse data from RSpace

After this tutorial, you will be able to:

-   Download metadata from RSpace using [rspacer](https://lacdr.github.io/rspacer)
-   Reuse stored metadata in R
-   Upload metadata to an RSpace lab journal entry 

The functionality already exists, but we have not yet written the tutorial. For now, read the Help pages and the vignette of: `rspacer::folder_tree`, `rspacer::document_list_attachments` and `rspacer::file_download`.

### Tutorial 6 - add attachments to an existing document

After this tutorial, you will be able to:

-   Upload files to RSpace from R using [rspacer](https://lacdr.github.io/rspacer)
-   Attach files to an existing document using [rspacer](https://lacdr.github.io/rspacer)

### Tutorial 7 - append information to an assay 1.

-   For now, see our [preprint](https://lacdr.github.io/rspacer-manuscript) and our [website](https://lacdr.github.io/rspacer/index.html)
-   Use `rspacer::document_append_from_html` to get this done.

## Installation instructions {#installation-instructions}

Requirements: you need to have R Studio and R installed, and you need an account on RSpace.

1.  Clone or download this git repository.
2.  Go to the folder with files you just created.
3.  Go to the folders and click on the Tutorial.md file or read the pdf version.
