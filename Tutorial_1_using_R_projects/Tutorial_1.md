## Tutorial 1 - using R projects

After this tutorial, you will be able to:

-   Explain how an R project can make your research more reproducible
-   Set up your own R project in RStudio

## Why use R projects?

R projects are a helpful tool for reproducible scientific computing in R.

This has several advantages:

-   scripts, data and results remain organized
-   relative file paths can be used
-   analyses become easier to reproduce
-   collaborators can run the same code

More details are available in the RStudio [documentation](https://www.docs.posit.io/ide/user/ide/guide/code/projects.html).

After this, answer these questions.
You can find the answers at the bottom of this page.

**Question 1:** What is main the purpose of an R project?

**Question 2:** How can you create a new R project in RStudio?

**Question 3:** How can you close an R project, and what is saved when you close the project?

### Materials to learn about R projects

Many folder structures have been suggested to use.
If you want, you can take a look at these resources:

-    Schnell, S. (2015). Ten Simple Rules for a Computational Biologist’s Laboratory Notebook. PLOS Computational Biology, 11(9), e1004385. https://doi.org/10.1371/journal.pcbi.1004385
-    Folder structure. RDM Guide. Elixir Belgium https://rdm.elixir-belgium.org/folder_structure
-    Folder Structure. The Graduate Institute Geneva https://libguides.graduateinstitute.ch/rdm/folders.
-    Folder/data organisation. Ghent University https://www.ugent.be/en/research/datamanagement/during-research/collection.htm#Folder/dataorganization.

In Tutorial 2, we will set up an ISA structure in your own R project!

### Absolute and relative file paths

When working in an R project it is recommended to use **relative file paths**.

Example:

```         
data/raw_data/data.csv
```

instead of

```         
C:/Users/username/Documents/project/data/raw_data/data.csv
```

Using relative paths ensures that code runs on different computers.
A useful package for this is the [here package](https://here.r-lib.org).

Example:

``` r
library(here)

read_csv(here("data", "raw_data", "data.csv"))
```

## Set up your own R project in RStudio

Now it is your turn! Let's build an R project for one of your research projects, or follow our Tutorial story. In the next Tutorials, we will analyze a small dataset.
To prepare for this:

1. In RStudio click **File → New Project**
2. Select **New Directory**
3. Choose **New Project**
4. Name the project `example_project`.

## Conclusion

You should now be able to explain how an R project can make your research more reproducible, and set up an R project in RStudio.
In Tutorial 2, we will extend this project using the ISA structure.

## Answers on questions

*Last edited on 19-03-2026*

1.  R projects can help to keep all files related to a project together.
2.  RStudio has the option to create and open projects in the right top.
3.  You can either close an R project or just close RStudio.
Depending on your settings, the history and environment variables can be saved.
