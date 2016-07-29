---
layout: post
title:  "Learning Jekyll"
date:   2016-05-29 23:59:39 +1000
categories: blogging automation content 
---
# Learining Jekyll

I recently put this site up - wanted a quick, controlled way of putting content & thoughts down and after attending API days looked to give Jekyll a try.

## Goals

* How can I automate publishing and deployment of a blog just by using version control?

### Criteria

* Driven from a repository - version controlled
* Hostable
* Continuous delivery on changes


## Best fit (so far)

To achieve this (you are looking at it..!) I used this combination of technologies and some useful posts.  My blog is free, version controls and auto-publishes when I commit to my github project.

* Jekyll
* Heroku
* github repo


## To start

### Create a github project

Mine is at - [https://github.com/npiper/neilpiper.blog](https://github.com/npiper/neilpiper.blog)

### Install / Import Jekyll

You'll need the pre-requisites listed at [Jekyll Installation](https://jekyllrb.com/docs/installation/)

Follow the instructions at [Jekyll Quickstart](https://jekyllrb.com/docs/quickstart/) based on your site name. This will create the required structures.

Build and test the Jekyll site following these instructions.

[Jekyll usage](https://jekyllrb.com/docs/usage/)

You can then `git add .` and `git commit` the initial structure into your github location.

### Add a 'Procfile' so Heroku can provision your Jekyll site

Follow the instructions James has left here, basically the Procfile is a provisioning instruction on how to deploy / server your Jekyll structure into a Heroku app with the [Puma web server](http://puma.io/). 

[James ward - Jekyll on Heroku](https://www.jamesward.com/2014/09/24/jekyll-on-heroku)

`web: bundle exec puma -t 8:32 -w 3 -p $PORT`

Don't forget to add this to your git repo.

### Create your Heroku Jekyll server and link your github project 

Sign up and create a Heroku account.

You can then create a new app and deploy pipeline using the github project you created.

[Creating Heroku Pipelines](https://devcenter.heroku.com/articles/pipelines#creating-pipelines)

Follow the isntructions to link your github project to your build pipeline.

![HerokuScreenshot]({{ site.url }}/media/herokuscreenshot.png)

You now have a CI enabled blog in github.

## References 

[Jekyll Quick Start](https://jekyllrb.com/docs/quickstart/)
[James Ward - Jekyll on Heroku](https://www.jamesward.com/2014/09/24/jekyll-on-heroku)

