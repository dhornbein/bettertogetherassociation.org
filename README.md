# denverfreelancing.com
It's a website for denverfreelancing.com

# Getting started

We are using [Jekyll](https://jekyllrb.com) to build a static site and hosting
that site on github pages.

For local development you'll need to pull the repository, install Jekyll ([docs](https://jekyllrb.com/docs/))
then push changes to a branch and make a pull request to master for those changes
to show up live online.

## Installing Jekyll

1. Install a full [Ruby development environment](/docs/installation/)
2. Install Jekyll and [bundler](/docs/ruby-101/#bundler) [gems](/docs/ruby-101/#gems)
```
gem install jekyll bundler
```

## Running this site

1. Perform a `git clone` of the repository.
2. Navigate to the repository directory in terminal and run `jekyll serve` to start
rendering the site.
3. In your browser navigate to the URL indicated by the program typically: `Server address: http://127.0.0.1:4000/`

## Editing

Once the site is running on your local environment you're ready to edit. Please
look to the Jekyll documentation to better understand how the file structure works

# TODO

## Version control bulma
Currently bulma exists in the `_scss` folder and is not managed via npm or other means.
Find a means to manage bulma and other vendor libraries through npm or package
manager.
