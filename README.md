# Status

Just a spot to publish our status.

## Install

1. Run: `brew install hugo`
2. Clone this repo
3. Run: `hugo`
4. Run `cd public`
5. Clone this repo again...
6. Run `mv status/.git .`
7. Run `rm -rf status`
8. Run `git checkout gh-pages`

## Publish Content

1. Make new post `hugo new post/name-of-md-file.md`
2. Edit markdown file & remove `draft = true` from file
3. Once you're set run `hugo server` & verify you get what you're expecting
4. Inside the public folder run `git status` & commit & push changes

