# About
Welcome! Data Umbrella is building a new website. We are slowly transferring content from our current website which is hosted using Google Sites (https://www.dataumbrella.org/) to this website-in-progress (https://dev.dataumbrella.org/).

## Skills 
A background in any of these skills will enable you to contribute:  
- Git & GitHub
- CSS
- HTML
- Markdown
- UI/UX

Note:  you do not need *all* of these skills.

## Navigating Content
Here is a guide on commonly used files:  
1. **Menu** items:  to update menu items or add a page, see [navigation.yml](snowlake-v1.2/_data/navigation.yml)
2. **Images**: Data Umbrella images can be found in the folder [assets/images/data-umbrella](snowlake-v1.2/assets/images/data-umbrella/)

## Working on Issues
If you would like to claim an issue, put a note on the issue "I am working on this" and submit a pull request within 1 week or provide updates.  If there is no activity on the issue for a week or more, it will be considered stale and open to other contributors to work on.

---

# Building the Website Locally
Instructions to build and test the [dev.dataumbrella.org](https://dev.dataumbrella.org/) site locally.

## Installing Ruby & Jekyll
If this is your first time using Jekyll, please follow the [Jekyll docs](https://jekyllrb.com/docs/installation/) and make sure your local environment (including Ruby) is setup correctly.

## Deployment
To run the theme locally:
1. Navigate to the theme directory `snowlake-v1.2` and run `bundle install` to install the dependencies (if you get errors, delete Gemfile.lock and try again). 
2. Next, run `bundle exec jekyll serve` to start the Jekyll server.
3. Visit the site in your browser via [http://localhost:4000](http://localhost:4000).


### Theme Documentation
This website uses the [Snowlake theme](https://jekyllthemes.io/theme/snowlake-website-jekyll-theme). For more information on configuration/customization, navigate to [Documentation](https://github.com/data-umbrella/data-umbrella-website/tree/main/Documentation).

A demo of the [Snowlake theme](https://snowlake.tortoizthemes.com/) is available for reference.

---

# Git Workflow to Contribute

Note that pull requests (PRs) are to be submitted to the `main` branch.

We follow the ["fork and pull" Git workflow](https://github.com/susam/gitpr):  
1. Create a [GitHub account](https://github.com/).  
2. Fork the repository to your own GitHub account.
3. Clone the project to your local machine.
4. Setup an upstream remote using `git remote add upstream git@github.com:data-umbrella/data-umbrella-website.git`.
5. Checkout the **main** branch using `git checkout main`.
6. Create a branch (off of the main branch) locally with a concise name. Example:  `git checkout -b branch_name`
7. Commit changes to the local branch that you just created in the previous step.
8. Push the changes to your fork.
9. Open a PR in our [repository](https://github.com/data-umbrella/data-umbrella-website) to the **main** branch.
10. Please wait for the review and do the necessary changes.
11. In order to keep your **main** branch up to date with the latest changes, please use `git fetch upstream/main`, please use `git pull upstream/main` if `git fetch upstream/main` gives you conflicts.

