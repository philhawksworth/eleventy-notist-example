# Notist listings

An example of using [Notist](https://noti.st)'s JSON feed to populate a listing of your events on your own, pre-rendered site.


## Quick start

You can get your own version of this site by just clicking the button below, and then providing a suitable Medium RSS feed URL.

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/philhawksworth/eleventy-notist-example)


## Description

Here we are pre-rendering the site with a static site generator called <a href="https://11ty.io">Eleventy</a> and serving the content that it finds at a given JSON feed.


### Give it a try

You can get your own version of this site by just clicking the button below, and then providing a the URL of suitable JSON URL (or leaving it as the default while you explore).

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/philhawksworth/eleventy-notist-example)


### 👆 Ummm... What will clicking that button do?


Fair question. After clicking the button, [Netlify](https://www.netlify.com) will ask for your permission to clone this repo into your own GitHub account, and then create a new site for you in Netlify linked to that repo.

It will also ask for a Notist feed to ingest at build time (get yours from Notist or it will just default to [this one](https://noti.st/philhawksworth.json) which is just [mine](https://noti.st/philhawksworth))

Then it will build and deploy a new site for you, complete with hosting and continuous deployment all configured.

The whole thing should take less than a minute!



## Local development

This site is built with [Eleventy](https://11ty.io) and has very few prerequisites:

- Node
- Npm or Yarn

### Install and bootstrap

```bash
# clone this repository (or do that via the button above)
git clone git@github.com:philhawksworth/eleventy-notist-example.git

# move into the working directory and install dependencies
cd eleventy-notist-example
yarn

# generate and serve the site while watching for changes
yarn start

# build the site
yarn run build

```
