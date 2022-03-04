# End to End Examples

This repository servers as the home of vingettes showing how create outputs using a mixture of pharmaverse packages. 

# Adding examples

Please work in branches, and use PRs to `main` to add content.

A new `.Rmd` file should be added to `content/{url stub}/_index.Rmd`. Do not commit rendered `.html`. `{url stub}` is what will appear in the URL of the page, so it's best to keep it simple. The title you specify in the `.Rmd` file will be used for the table of contents, so it's possible to have a prettier name in the website. 

An example:

- The ADSL example is located at `content/adsl/_index.Rmd`
- Inside the `yaml` of `content/adsl/_index.Rmd` is a code block with `title: Create adsl`. 
- The table of contents renders the pretty title.
- `content/adsl/_index.Rmd` is rendered to html and added to the site via CICD.
