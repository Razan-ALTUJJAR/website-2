

# convert to R Markdown
nb_rmd = rmarkdown:::convert_ipynb(Analyse.ipynb)
xfun::file_string(nb_rmd)

