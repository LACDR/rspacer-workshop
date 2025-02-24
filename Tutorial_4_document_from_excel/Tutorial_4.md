## Tutorial 4 - document from Excel

After this tutorial, you will be able to:

-   Upload information from Excel, CSV or TSV files to specific fields in an RSpace Document using [rspacer](https://burgerga.github.io/rspacer).

## Prerequisites

For this tutorial, you need information or files from previous tutorials. Make sure that you:

-   have created an RStudio project
-   have LACDR-ISA installed
-   have filld in an LACDR-ISA Excel template.
-   have an account on RSpace that you can log in to.

## Install and set up rspacer

1.  Follow the instructions on [rspacer](https://burgerga.github.io/rspacer).
2.  Also make sure you set up your API key and URL.

### Step by step tutorial

This tutorial is a specific adaptation from the rspacer [article](https://burgerga.github.io/rspacer/articles). That tutorial is written more general. Here, we will show how to upload LACDR-ISA documents. This can be done by adapting an additional template that is installed when installing LACDR-ISA.

1.  Open your RStudio project
2.  Click on File \> New File \> R Markdown \> From Template \> LACDR-ISA upload to RSpace
3.  Follow the instructions EXCEPT:
    1.  Change all file paths so that they point to your XLSX file.
    2.  Remove lines of code that point to the quarto script.
    3.  In the `Upload the file` section, replace `document_create_from_html` with `document_create_from_excel`.
    4.  That's it!

## Conclusion

Now, you should be able to:

-   Upload information from Excel, CSV or TSV files to specific fields in an RSpace Document using [rspacer](https://burgerga.github.io/rspacer).
