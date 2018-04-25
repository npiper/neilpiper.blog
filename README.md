# Jekyll Blog with Heroku
 
Where it's deployed [neilpiper-blog](https://neilpiper-blog.herokuapp.com)

# How to build & test

Branch for Oauth on Heroku

## Pre-Requisites

https://jekyllrb.com

https://jekyllrb.com/docs/installation/

* Ruby
* Jekyll  `gem install jekyll`
* Linux, Unix, MacOs - preferred

# Security

Oauth authentication

Github app name: mypages

Client ID
e5ed26d6f690ff9d9e11

Client Secret
20677c5cca1327ddd7a281d209e671657dcfe05e


Auth callback URL:
https://mypages.herokuapp.com/auth/github/callback


# Build

https://jekyllrb.com/docs/usage/

`jekyll build` (builds to _site)

`jekyll serve` at http://localhost:4000/

'bundle exec jekyll serve --watch`

# Add a Post

Create a markdown file under the _posts folder

# Deploy / Build on Heroku

https://www.jamesward.com/2014/09/24/jekyll-on-heroku



# Password Protect??

Heroku / Dropbox
http://daverupert.com/2015/02/jekyll-heroku-dropbox/

Jekyll Auth
https://github.com/benbalter/jekyll-auth

Heroku / Github
https://devcenter.heroku.com/articles/github-integration

# Travis-CI build
