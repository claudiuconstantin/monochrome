_(This page is work in progress)_

## About
Cult is a minimal Jekyll theme for personal blogs, built on top of [Monochrome](https://github.com/dyutibarma/monochrome) and [Emerald](https://github.com/KingFelix/emerald) themes.

Demo [here](https://claudiuconstantin.github.io/cult/).

## Features

- Completely responsive and mobile first
- Clean SEO friendly URLs, auto-generated from post title (no messy dates in the url)
- SEO title/description integration
- Sitemap ready
- Pagination support
- Mobile friendly navigation menu
- Easy customization for header, footer, navigation links, colors, favicon etc
- Default Cult Color Palette - black, white, greys
- About page
- 404 page

## Install/Setup Jekyll

(Skip if you already have Jekyll 2.2)

1. Make sure Ruby 2.5 is installed 
```
sudo apt-get install ruby2.5
sudo apt-get install ruby2.5-dev
```
2. Install bundle: `sudo gem install bundler`
3. Install jekyll: `sudo gem install jekyll`


## Install Cult dependencies

```
sudo gem install jekyll-paginate
sudo gem install jekyll-sitemap

```

## Write a Post

- cd into  ``_posts/``
- create new file with format yyyy-mm-dd-title-of-post.md
- add title/description (refer any of the test posts)
- add markdown and save


## Customization Options

You can customize this layout using instructions below. 

### Header/Footer/Navigation

Set a custom header tag by setting the related option in the ``_config.yml`` file to "true". Then insert your custom code into the ``header-custom.html`` file.
In the same way, you can customize the footer of the navigation menu, by setting to "true" the related option and put your code into the ``nav-footer-custom.html`` file.
Moreover select a reverse option that allows to move the navigation menu to the left side, by setting it to "true".

### Colors

The basic colors are set into the ``base.scss`` file:
- $background-color: used for background and links in the navigation menu
- $text-color: used for text and title in posts and pages 
- $text-light-color: used for text lighter than text-color
- $text-dark-color: used for text darker than text-color

To customize the colors, just set the values in HEX, RGB (or RGBa) or any other format accepted by CSS.

### Navigation menu

The links inside the navigation menu are autogenerated from pages having the layout set to ``page``.
You can set custom links, by putting in the ``<a>`` tag into the ``link.html`` file.

### Branch
There is one single ``master`` branch used for development and also as a source for the demo.

### Baseurl

You can change the 'baseurl' value in the 'config.yml' file, from '' to your preferred directory/project name (example '/blog' or '/' to install in root)

### Typography

To maintain the vertical rhythm, it has been applied a **Typographic scale** as a modular scale, with a baseline set to 24px. To maintain this rhythm you need to insert elements like image, video or other contents with a 24px (or multiple) height as refer.

## Maintainer

- [Claudiu Constantin](http://claudiuconstantin.com/), a versatile software developer

This theme is based on the great work of Dyuti Barma (Monochrome) and Jacopo Rabolini (Emerald). 

## License
Released under [MIT License](license.md).
