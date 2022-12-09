# Installation
Instructions to build and test the [dev.dataumbrella.org](https://dev.dataumbrella.org/) site locally.

## Installing Ruby & Jekyll
If this is your first time using Jekyll, please follow the [Jekyll docs](https://jekyllrb.com/docs/installation/) and make sure your local environment (including Ruby) is setup correctly.

## Deployment
To run the theme locally:
1. Navigate to the theme directory `snowlake-v1.2` and run `bundle install` to install the dependencies (if you get errors, delete Gemfile.lock and try again). 
2. Next, run `bundle exec jekyll serve` to start the Jekyll server.
3. Visit the site in your browser via [http://localhost:4000](http://localhost:4000).


### Theme Documentation
This uses [Snowlake theme](https://jekyllthemes.io/theme/snowlake-website-jekyll-theme). For more information on configuration/customization, please navigate to [Documentation](https://github.com/data-umbrella/data-umbrella-website/tree/main/Documentation).

# Workflow to Contribute

Note that pull requests (PRs) are to be submitted to the `main` branch.

We follow the ["fork and pull" Git workflow](https://github.com/susam/gitpr)
1. Create a github account in case you dont have one already.
2. Fork the repository to your own Github account.
3. Clone the project to your machine.
4. Setup an upstream remote using `git remote add upstream git@github.com:data-umbrella/data-umbrella-website.git`.
5. Checkout the **main** branch using `git checkout main`.
6. Create a branch (off of the main branch) locally with a concise name.
7. Commit changes to the local branch that you just created in the previous step.
8. Push the changes to your fork.
9. Open a PR in our [repository](https://github.com/data-umbrella/data-umbrella-website) to the **main** branch.
10. Please wait for the review and do the necessary changes.
11. In order to keep your **main** branch up to date with the latest changes, please use `git fetch upstream/main`, please use `git pull upstream/main` if `git fetch upstream/main` gives you conflicts.

