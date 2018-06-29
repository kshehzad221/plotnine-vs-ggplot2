# Notebook Description
In this Jupyter Notebook, we perform a detailed comparison of plotnine (the equivalent of R's ggplot2 package), written by Hassan Kibirige, against the native ggplot2. The comparison is made possible by means of rpy2, a high-level interface designed to facilitate the use of R by Python programmers. 

We use the R magic command %load_ext to load the rpy2 IPython extension into the notebook, essentially initializing the R interface and allowing the notebook to connect and pass objects between the two languages. This is followed by the %%R magic command at the top of any code cell in which we want to write our R code.

The code for the plots has been taken from Chapter 19 of the book "R in Action - 2nd Ed - by Robert Kabacoff (2015)". The adaptations of the code for plotnine have been experimented and finalized by the Notebook author. It is hoped that this comparison will encourage the contributors of plotnine for the amazing job they have done and to spur further development. Furthermore, people who come from an R-intensive background will be able to appreciate the use of plotnine in their Python projects as needed.
