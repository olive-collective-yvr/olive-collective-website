We are OLIVE Collective (Our Liberation in Vegan Ethics), a grassroots collective
based in so-called Vancouver and dedicated to total liberation. This is the
source repository for our website.

The webpage is built using Jekyll (https://jekyllrb.com/), a static site generator
built in Ruby, and based upon the Alembic theme (https://jekyllthemes.io/theme/alembic).

# Setup

You will need the following tools to build the site locally on your machine:

1. Install git (https://git-scm.com/).
2. Install all of the prerequisites for Jekyll (https://jekyllrb.com/docs/).

# Contributing

The easiest way to contribute is to read and comment on the existing issues,
or suggest new ones -- viewable in the "Issues" tab.

If you would like to modify the source code directly (e.g. tackling an existing issue),
first tackle all points in the "Setup" section above. Then from a terminal,

1. Obtain a local copy of this repository using
```git clone https://github.com/olive-collective-yvr/olive-collective-website.git```
and `cd` into the directory.

2. To build the website locally, `cd` into the repository you created and do
```
bundle install
bundle exec jekyll serve
```
You should be able to open a browser to `localhost:4000/` and view a local copy
of the website as long as this terminal is open. 

3. Create a working branch, e.g. `git checkout -b your-working-branch-name`,
and make your changes there. You can re-generate the website with `jekyll serve`.
`git push` once you are ready to share changes.
