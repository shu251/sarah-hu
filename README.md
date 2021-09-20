### Personal website
_Instructions in Rmarkdown_

1. create Github repo. Enable readme and .gitignore with R
2. clone locally
3. open new Rstudio project (the newly cloned github repo), select Distill website and configure for Github pages.
4. Distill in R instructions: https://rstudio.github.io/distill/website.html
5. in R Studio, create a file using the command:
> file.create(".nojekll")
6. Commit all changes to github repo, go to settings and enable GitHub Pages, and select source ```/docs```

overview of files:
* ```_site.yml```: information for complete site navigation
* ```filename.Rmd```: page files for each page of the website, edit and use Rmarkdown to construct content here. When done, make sure a link to this page is available with ending .html. To render, click 'Build Website' in the build tab of RStudio, and each of these Rmd files will be knit to make a .html file.
* ```theme.css```: theme information for whole website design. See theme CSS online to modify distill websites. 
