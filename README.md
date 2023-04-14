# NEU Autonomy Lab

## To add yourself to the Team page

1. Clone the repository locally
1. Create a new branch (e.g., `git checkout -b add_person/<name>`)
1. Add a picture in `images/members`
1. Add an entry to `_data/students.yml`
1. Check that the site builds/looks ok in a browser locally (instructions below)
1. Commit and push that to GitHub
1. Open a Pull Request on GitHub and the webmaster will merge it in

## To run locally (not on GitHub Pages, to serve on your own computer)

1. Clone the repository and made updates as detailed above
1. Make sure you have ruby-dev, bundler, and nodejs installed: `sudo apt install ruby-dev ruby-bundler nodejs`
1. Run `bundle clean` to clean up the directory (no need to run `--force`)
1. Run `bundle install` to install ruby dependencies. If you get errors, delete Gemfile.lock and try again.
1. Run `bundle exec jekyll serve` to generate the HTML and serve it from `localhost:4000` the local server will automatically rebuild and refresh the pages on change.

