# Particle Jekyll Theme

![](./particle.jpg)

This is a simple and minimalist template for Jekyll designed for developers that want to show of their portfolio.

The Theme features:

- Gulp
- SASS
- Sweet Scroll
- Particle.js
- BrowserSync
- Font Awesome and Devicon icons
- Google Analytics
- Info Customization

## Basic Setup

1. [Install Jekyll](http://jekyllrb.com)
2. Clone the particle theme: `git clone https://github.com/nrandecker/particle.git`
3. Edit `_config.yml` to personalize your site.

## Site and User Settings

You have to fill some informations on `_config.yml` to customize your site.

```
# Site settings
title: Cole Ternes | Resume
description: A resume website showing off me, my skills, and my portfolio
url: "" # the base hostname & protocol for your site

# User settings
username: coleternes
user_description: Cole Ternes at Chapman University
user_title: Cole Ternes
email: ternes@chapman.edu
github_username:  coleternes
```

## Color and Particle Customization
- Color Customization
  - Edit the sass variables
- Particle Customization
  - Edit the json data in particle function in app.js
  - Refer to [Particle.js](https://github.com/VincentGarreau/particles.js/) for help

## Running the blog in local

In order to compile the assets and run Jekyll on local you need to follow those steps:

- Install [NodeJS](https://nodejs.org/)
- Install [Jekyll](https://jekyllrb.com): `sudo gem install bundler jekyll`
- Install [Yarn](https://yarnpkg.com/): `npm install -g yarn`
- Install dependencies: `yarn`
- Run: `gulp`

## License

This theme is free and open source software, distributed under the The MIT License. So feel free to use this Jekyll theme anyway you want.

## Credits

This theme was partially designed with the inspiration from these fine folks
- [Willian Justen](https://github.com/willianjusten/will-jekyll-template)
- [Vincent Garreau](https://github.com/VincentGarreau/particles.js/)
