
<!-- README.md is generated from README.Rmd. Please edit that file -->

# rmarkdown-website

<!-- badges: start -->

<!-- badges: end -->

a template for creating a website in R Markdown

## Set up hosting (once)

1.  Turn on hosting via GitHub Pages
    1.  Settings -\> GitHub Pages -\> Source -\> select “master branch
        `/docs` folder”
2.  View your website at given URL
    1.  In case: (<https://sds236-s20.github.io/website-beanumber/>)

## Maintainence

1.  Change content as necessary
    1.  Modify existing `.Rmd` files
    2.  Add new files as necessary
    3.  Update `_site.yml` as necessary
2.  Render entire site by running:

<!-- end list -->

``` r
rmarkdown::render_site("www")
```

1.  Commit and push changes.
    1.  Make sure to commit changes to **both** the `.Rmd` files in
        `www/` **and** the `.html` files in `docs/`

## Resources

  - [R Markdown
    websites](https://bookdown.org/yihui/rmarkdown/rmarkdown-site.html)
  - [Bootstrap 3.3
    components](https://getbootstrap.com/docs/3.3/components/)
  - [Bootswatch themes](https://bootswatch.com/3/)
  - [Font Awesome icons](https://fontawesome.com/icons?d=gallery&m=free)
