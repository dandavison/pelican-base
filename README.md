A pelican blog skeleton with mathjax and footnotes plugins, and a theme.

#### Instructions

First, go to github and fork this repo into your own account.

Next, rename the forked repo so that it has the name you want.

In the code below, substitute your github user name, and the name of the repo.

##### Get it working locally

```
git clone https://github.com/YOUR_GITHUB_USER_NAME/pelican-base.git REPO_NAME
cd REPO_NAME
git submodule init
git submodule update
mkdir output
make html
make serve
# It should now be served at localhost:8000
```

##### Publish to github pages

```
# In publishconf.py, change SITEURL to https://YOUR_GITHUB_USER_NAME.github.io/REPO_NAME/
# Commit that change
make github
# It should now be served at https://YOUR_GITHUB_USER_NAME.github.io/REPO_NAME/
# Might take a minute
```
