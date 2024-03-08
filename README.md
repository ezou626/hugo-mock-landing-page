# hugo-mock-landing-page
## **Demo** (not real) Static Landing Page generated with Hugo hosted with GitHub pages
Based on hugo-bootstrap-theme

## Branches
* main: source branch
* gh-pages: source for github pages deployment

## Structure
### Top Level Folders
* assets holds SCSS stylesheets
* content holds MD files with text
* layouts holds HTML files
* static holds image files
* themes contains the submodule hugo-bootstrap-theme, which this project is based on
* .github/workflows holds the workflow to autodeploy this Hugo site
### Files
Standard: LICENSE, README.md, .gitignore, and .gitmodules
config.toml is the hugo config file
publish_to_gh_pages.sh is a utility script to publish the site to GitHub pages
USER-STORIES.md describes use cases for this made-up app

## Run Locally
1. Clone the repo
2. Run `cd hugo-mock-landing-page`
3. Install hugo (> v99 should be good)
3. Run `hugo server`
