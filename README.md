# Recreating Vim in nodejs
> Although the name suggests recreation, this project doesnt actually recreates Vim.
> I've only tried to achieve some basic features similar to vim to understand how vim works. So, this project is my personal implementation of few features from vim.
> Since, this is a playground project, there are lots and lots of bugs, solving them felt a waste of time since it was about finding possibilities, that is why the code itself is an artifact which I'll never open.
> > However, this can be partially useful to someone who wonders how vim works.

## Usage
- Nodejs is required
- Just run, `node index.js <local-file-name`
- Probably need `iterm2` of better support

## Features
- Toggle insert & escape mode with `ESC` key
- Support for vim motions `h`, `j`, `k`, & `l`, do not use arrows, haven't handle those.
- Support for backspace, doesn't work with multiline
- Although it supports `:` for command mode in normal mode, it only runs `:q` quit & for any other commands shows an error.
- Support for absolute line-numbers
- Support for footer airline bar
