This repository contains the code for the Open Case Studies Project Website: https://www.opencasestudies.org/ 

To contribute:

1) Edit the files in the main dir
2) In terminal run hugo server
3) In terminal run hugo to check what the site looks like at the url provided
4) Commit and push your changes
5) Move to the public directory
6) Push all changes to this directory

To add to the blog:

- create a new file in the content/post directory
- ensure that the date has a zero in front of months or days that are less than 2 digits, so that the blog will order posts correctly

To add or update an author:

- each author has a directory titled with the first initial followed by last name (for example cwright for Carrie Wright).
- the image should be called avatar.jpg 
- the _index.md file contains information about the author what team the author should be listed in according to the content/home/team.md page


To add custom css/html - there are two options:
1) you can use the <rawhtml> tag to allow you to add html:

{{< rawhtml >}}
<p style="margin-right: .7em"; align="center" ><iframe src="https://www.opencasestudies.org/OCS_search/" width="1200" height="1900" </iframe></p>
{{< /rawhtml >}}

2)
Custom css/html can be added in the layouts/shortcodes files.

For example,  (NOTE: this is not currently being used), but one the code to embed the search table is within the ocstable.html file within this directory. 

This could then be added to files inside content/home like so:
` {{< ocstable >}}`

To add files to the site, adding it to the config/_default/menus.toml file.

This website was made with the following tools:

# [Academic Kickstart](https://sourcethemes.com/academic/)

**Academic** makes it easy to create a beautiful website for free using Markdown, Jupyter, or RStudio. Customize anything on your site with widgets, themes, and language packs. [Check out the latest demo](https://academic-demo.netlify.com/) of what you'll get in less than 10 minutes, or [view the showcase](https://sourcethemes.com/academic/#expo).

**Academic Kickstart** provides a minimal template to kickstart your new website.

- [**Get Started**](#install)
- [View the documentation](https://sourcethemes.com/academic/docs/)
- [Ask a question](http://discuss.gohugo.io/)
- [Request a feature or report a bug](https://github.com/gcushen/hugo-academic/issues)
- Updating? View the [Update Guide](https://sourcethemes.com/academic/docs/update/) and [Release Notes](https://sourcethemes.com/academic/updates/)
- Support development of Academic:
  - [Donate a coffee](https://paypal.me/cushen)
  - [Become a backer on Patreon](https://www.patreon.com/cushen)
  - [Decorate your laptop or journal with an Academic sticker](https://www.redbubble.com/people/neutreno/works/34387919-academic)
  - [Wear the T-shirt](https://academic.threadless.com/)

[![Screenshot](https://raw.githubusercontent.com/gcushen/hugo-academic/master/academic.png)](https://github.com/gcushen/hugo-academic/)

## Install

You can choose from one of the following four methods to install:

* [**one-click install using your web browser (recommended)**](https://sourcethemes.com/academic/docs/install/#install-with-web-browser)
* [install on your computer using **Git** with the Command Prompt/Terminal app](https://sourcethemes.com/academic/docs/install/#install-with-git)
* [install on your computer by downloading the **ZIP files**](https://sourcethemes.com/academic/docs/install/#install-with-zip)
* [install on your computer with **RStudio**](https://sourcethemes.com/academic/docs/install/#install-with-rstudio)

Then [personalize your new site](https://sourcethemes.com/academic/docs/get-started/).

## Ecosystem

* **[Academic Admin](https://github.com/sourcethemes/academic-admin):** An admin tool to import publications from BibTeX or import assets for an offline site
* **[Academic Scripts](https://github.com/sourcethemes/academic-scripts):** Scripts to help migrate content to new versions of Academic

## License

Copyright 2017-present [George Cushen](https://georgecushen.com).

Released under the [MIT](https://github.com/sourcethemes/academic-kickstart/blob/master/LICENSE.md) license.

[![Analytics](https://ga-beacon.appspot.com/UA-78646709-2/academic-kickstart/readme?pixel)](https://github.com/igrigorik/ga-beacon)
=======
Open Case Studies 
==================

* GitHub organization with all case study repositories: [https://github.com/opencasestudies](https://github.com/opencasestudies). 

Note that the DT search table is hosted at this URL (http://www.opencasestudies.org/OCS_search/) from a separate repo: https://github.com/opencasestudies/OCS_search

The html code used is located within the `layouts/shortcodes` directory and added to the markdown files within the `content/home/` directory using `{{<>}}` labels. The `config/_default` directory has the files for the overall layout of the site. Use `hugo server` to preview what the website looks like before pushing to the repo. Follow this by `hugo` to generate any additional files to be added to the `public` directory. The `public` directory is a submodule that points to a different repo that the final changes to the website are pushed to if you commit and push changes to that directory. That repo lives at: https://github.com/opencasestudies/opencasestudies.github.io. If you have challenges look at the [hugo documentation](https://gohugo.io/) for any updates. This is typically why things may not be working as expected.
