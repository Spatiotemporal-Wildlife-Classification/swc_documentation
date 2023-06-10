# Spatiotemporal Wildlife Classification (SWC) Docs
Documentation Encompassing the Spatiotemporal Wildlife Classification (SWC) Organization. 
The organization makes use of MKDocs and GitHub pages in order to make a comprehensive documentation 
structure stretching across all repositories within the organization.

## Deploying Changes
Two independent repositories are required to deploy the documentation for the SWC Organization:
The proposed file structure should look like the below, containing the swc_documentation repository and 

```angular2html
    swc_documentation/
        resources/
        docs/
        mkdocs.yml

    Spatiotemporal-Wildlife-Classification.github.io/
        assets/
        resources/
        search/
        404.html
        index.html
        sitemap.xml
        sitemap.xml.gz
```

Make the changes to the MKDocs within the `swc_documentation` repository. 
To preview the changes made, run on the local server using the following command `mkdocs serve`. You must be inside the 
swc_documentation repository and execute the command from the command line. 

To deploy the documentation live at the URL: https://spatiotemporal-wildlife-classification.github.io/ 
Navigate into the `Spatiotemporal-Wildlife-Classification.github.io` repository and execute the following from the command line:
```
mkdocs gh-deploy --config-file ../swc_documentation/mkdocs.yml --remote-branch main
```

## Useful Links and Style Guide
- Google's Python docstring style guide:L https://google.github.io/styleguide/pyguide.html
- MKDocs intro tutorial: https://realpython.com/python-project-documentation-with-mkdocs/
- MKDocs Home page: https://www.mkdocs.org/
