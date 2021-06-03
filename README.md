# goldcomparts.show

This repo exists to redirect to the current year's website. 

## Current site

* http://third.goldcomparts.show/

## Creating a new site

1. Ideally pick the name of the show, otherwise come up with a `workingname` while developing the new site. (tip: Avoid names which start or end with anything other than letters or numbers, as otherwise it gets complex to add `https` to the site later!)
2. Create a new repo in this org, named `workingname.goldcomparts.show`
3. You can then use [Github Pages](https://pages.github.com/) to create your site, or you can do it some otherwise, it's very flexible! So if you already have someone who has a lot of experience making websites and they know what do to then great! otherwise you could try copying one of the previous sites below and adapting for your show
4. When the site is ready to go live, create a new subdomain in PorkBun using a `CNAME` record which will point `workingname` at your site. Here's instructions for how to do it for [Github Pages](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site#configuring-a-subdomain)   (tip: it's good to make it live at least two weeks before the show so there's some hope that search engines will find it)
5. To redirect the toplevel domain to your subdomain, edit the urls in `index.html` in this repo. We have to use [meta refresh](https://www.w3.org/TR/WCAG20-TECHS/H76.html) as Github pages doesn't currently have a way to configure server-side redirects.
6. Good luck, hope the show goes well!


## Previous sites

* https://2020.goldcomparts.show
* https://2019.goldcomparts.show
* http://echosystems.xyz

