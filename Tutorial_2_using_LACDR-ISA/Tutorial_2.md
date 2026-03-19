## Tutorial 2 - using LACDR-ISA Quarto and Excel templates

After this tutorial, you will be able to:

-   Explain why using templates can benefit your research
-   Apply the Investigation-Study-Assay structure to your own research projects
-   Use LACDR-ISA Templates in RStudio and in Excel
-   Adapt the LACDR-ISA Template to your own research needs

## Why use templates?

Templates are standardized documents where you can put information in. Here we will show some flexible templates, but many more specific templates exist. Especially when metadata is needed for further analysis, it is recommended to collect the metadata, for example cell line names, in a standardized form, file, document, or column. Templates can speed up your own research, but also help to find information back later.

## What is the Investigation-Study-Assay format?

For more information, see the [ISAtools website](https://isa-tools.org/).

## Install and use LACDR-ISA Quarto templates

1.  Go to the LACDR-ISA template website: <https://www.github.com/LACDR/LACDR.ISA> and follow the installation instructions.
2.  After that, follow the usage instructions. Play around and try to fill in at least one Investigation, Study, and Assay template.
3.  Save these **as quarto .qmd file, NOT as .Rmd file.**
4.  Render the Investigation, Study and Assay files. You might need them in Tutorial 3. Tip: you can use the visual editor in RStudio for easier reading.

### Read a previous assay

Take a look at the code subfolder. Here, you find two previously created assays. Open these in RStudio and answer the following questions **without** running the code.

1.  Who performed this analysis?
2.  What was the aim of this analysis?
3.  When did they perform the analysis?
4.  Which LACDR-ISA template was used?
5.  What was the main conclusion of this assay?
6.  What did the plot look like? Which object was found most?
7.  What computer was the analysis run on? And which R version was used?

You may have found the answer on question 1, 2, 4, and 5. Especially 2 and 5 are easy to find because of the ISA-Assay template! But what about 3, 6 and 7? These observations and results are not in the code. They can only be found if the **results** are also saved.

Take a look at the results and data folder in this tutorial and answer the following questions. 1. Where were the result saved? How can you link this back to the code? 2. Which data was used? 3. Open the HTML file in the results folder. Try to answer questions 3, 6, and 7 again based on this report.

As you can see, it is pretty nice that information and observations are written down in the code, but especially the **rendered report** contains valuable information on the analysis when it was performed.

### Try to reproduce the analysis (which should fail)

In RStudio, open the assay again, and click the Quarto Render button on the top of the document. As you might see, there is something edited in the code after the last time it was used! This is what - unfortunately - happens a lot, and is why it is so important to store the rendered reports.

Now, run code chunk by chunk to find the bug. Fix it, and render the script again.

Congrats! You have just reproduced an analysis!

## Adapt the LACDR-ISA Template

Open the LACDR-ISA Assay template and the previous assay. You see that a lot of sub-headers are used, and you can imagine that you might want to have more than just the general headers. This is possible, and easy to do - as long as you know where to look.

Go to the LACDR-ISA template website: <https://www.github.com/LACDR/LACDR.ISA> and read the instructions on adapting templates. Try to adapt the templates until you are happy with your own template. Make sure that the LACDR-ISA headers all have two hashtags (h2 headers, with \##). You can write any code, or use h3 or h4 headers (with three or four hashtags). DO NOT edit/add/remove any of the h2 headers, because this is needed later for RSpace.

## Download and use LACDR-ISA Excel files

Sometimes, using R and Quarto is not really what you want. An easy and clean alternative is Excel.

1.  Download or open the Excel files in the templates folder.
2.  Fill in some fields.
3.  Try and edit one of the Template headers. Do you see that this is blocked? This Excel template is protected, which improves the standardization and reproducibility.
4.  Try to type outside of the highlighted fields. This is also blocked.
5.  Make a new Excel sheet and type something here. In this new sheet, you could add additional fields, calculations, etc.

By using these standardized templates, you might make your research more reproducible. However, someone might still accidentally edit your files after you finish this. In contrast to the HTML reports from Quarto, it is harder to avoid that here. One tip is to make the file read-only after you finish an assay.

Make the finished assay read-only. On Windows: right-click on the file \> Properties \> Click the read-only box.

## Conclusion

Now, you should be able to:

-   Explain why using templates can benefit your research
-   Apply the Investigation-Study-Assay structure to your own research projects
-   Use LACDR-ISA Templates in RStudio and in Excel
-   Adapt the LACDR-ISA Template to your own research needs

Next, we will upload your rendered assay HTML report, or the Excel file to RSpace (Tutorial 3 and 4, respectively).
