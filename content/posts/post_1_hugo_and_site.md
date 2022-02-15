---
title: "This Site & Discovering Hugo"
date: 2021-07-02T09:43:05+02:00
is_post: true
---

This website of mine is set up using the static site generator [Hugo](https://gohugo.io/). Meaning there are no fancy, slow scripts running in the back-end when you open a page. Further, it's markdown, it's fast and it's mighty. It offers a lot of themes and customization and a very clean content management system. The fact, that I'm writing this in markdown and it is shown as a website is very satisfying, in my opinion.

## Getting Started with Hugo
The Hugo Documentation is pretty detailed and extensive and you find everything you need to get started [here](https://gohugo.io/getting-started/).

After installation, to setup a basic website, all you need to do is running this command  `hugo new site sitename`. To run a development server, run `hugo serve -D` and to build the page simple run `hugo` in the directory of the site. Or just check out the [CLI Doc](https://gohugo.io/commands/).

Now, to customize, there are many things you can do. The major settings are found in the `config.toml`, like the site title or menu setup. To change the appearance, you can download a [theme](https://themes.gohugo.io/) and add it to the `themes` folder and also set it in the config.

## My Site
I use the [Black & Light](https://github.com/davidhampgonsalves/hugo-black-and-light-theme) Theme and adjusted it a bit to meet my needs. The forked repository can be found [here](https://github.com/lucashabersaat/hugo-black-and-light-theme). So far, the website does not contain a lot. Blog posts, an about page with my resume and a now page with what I am currently doing.

To guarantee a smooth workflow, I set up a GitHub action on the repository of the website, that builds and deploys it on my VPS. Whenever I push something on the **main** branch, the procedure is triggered and my website is up to date, automatically. Check out the [actions-hugo](https://github.com/peaceiris/actions-hugo) workflow for GitHub Actions.

I plan to further explore Hugo, as there are many more features it offers that might end up on this site. However, for now it's quite a neat little nest for my stuff.
