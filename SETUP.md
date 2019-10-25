# Setup Instructions
Use this guide to learn how to setup everything you need to build a workbook with GitHub Pages.

* Repository Setup
* Local Environment Setup
* Customize Your Workbook

## Repository Setup

1. Navigate to https://github.com/sfdx-isv/github-pages-workbook
2. Click the "Use this template" button
3. ??? Does a template-created org need to do the GitHub Pages setup steps?
4. ???

## Local Environment Setup

### Install Tools and Dependencies
1. Install Git
2. Install VS Code
3. [Install Jekyll](https://jekyllrb.com/docs/installation/)

### Clone Repository and Test Your Local Config
1. Clone the repository you just created
2. Open the cloned directory as a project in VS Code
3. Open the VS Code Integrated Terminal (`COMMAND+J`)
4. In the VS Code Integrated Terminal...
    * Type `cd sample_docs` to navigate to the `sample_docs` directory
    * Type `jekyll build; jekyll serve` which asks Jekyll to..
      * Build actual HTML, CSS, and JavaScript files from the `sample_docs` source files
      * Start a local HTTP server so you can preview the generated site and pages locally
6. Open your web browser to http://127.0.0.1:4000/sfdx-workshop/
7. Verify that you can click around the locally-served documentation site
8. In the VS Code Integrated Terminal...
    *  Press `CTRL+C` to stop the Jekyll HTTP server
    *  Type `cd ..` to navigate back to the root of your repository

## Start Building Your Own Docs

### Customize Your Configuration
1. Open the file `docs/_config.yml` in VS Code and modify EACH of the following configuration options
    * **Site Settings**
      * `title`
      * `name`
      * `description`
      * `url`
      * `baseurl`
      * `repository`
    * **Social Sharing**
      * `twitter.username`
      * `social.type`
      * `social.name`
    * **Site Author**
      * `author.name`
      * `author.avatar`
      * `author.bio`
      * `author.location`
      * `author.links(Email):url`
      * `author.links(GitHub):url`

### Customize Navigation

In the VS Code Integrated Terminal...
    * Type `cd docs` to navigate to the `docs` directory





## Additional Resources
### GitHub Pages
* Official Documentation
  * [GitHub Pages Official Homepage](https://pages.github.com)
  * [GitHub Docs: Setting up a GitHub Pages site with Jekyll](https://help.github.com/en/github/working-with-github-pages/setting-up-a-github-pages-site-with-jekyll)
  * [GitHub Docs: Working with GitHub Pages](https://help.github.com/en/github/working-with-github-pages)
* Community Documentation
  * [Community Blog: Creating and Hosting a Personal Site on GitHub](http://jmcglone.com/guides/github-pages/)
  * [YouTube: Go Go gh-pages! Build a website with GitHub Pages and Jekyll (workshop)](https://www.youtube.com/watch?v=SWVjQsvQocA)

### Jekyll
* Official Documentation
  * [Jekyll Docs: Installation](https://jekyllrb.com/docs/installation/)
  * [Jekyll Docs: GitHub Pages](https://jekyllrb.com/docs/github-pages/)
  * [Jekyll Docs: Configuration](https://jekyllrb.com/docs/configuration/)
  * [Jekyll Docs: Front Matter](https://jekyllrb.com/docs/front-matter/)
  * [Jekyll Docs: Liquid](https://jekyllrb.com/docs/liquid/)
* Community Documentation
  * [YouTube: Getting Started With Jekyll, The Static Site Generator](https://www.youtube.com/watch?v=iWowJBRMtpc)
  * [YouTube: Hosting on Github Pages | Jekyll - Static Site Generator](https://www.youtube.com/watch?v=fqFjuX4VZmU)

### Liquid
* Official Documentation
  * [Liquid Docs: Introduction](https://shopify.github.io/liquid/basics/introduction/)
* Community Documentation
  * [YouTube: Introduction to Liquid in Jekyll](https://www.youtube.com/watch?v=6pCdOh_I4EM)