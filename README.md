# my_website

Hello world
#to start the site
library(blogdown)
blogdown::serve_site()

#check hugo version
hugo_version()
#then change that in netlify.toml 

#to update, type these in terminal
git add -A #add
git commit -m "commit name"
git pull
git push