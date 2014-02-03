# README

This is the sweetest initial project structure (a.k.a. boilerplate) for Mixture that includes [Normalize.css](http://necolas.github.io/normalize.css/), [Bourbon](http://bourbon.io), [Bourbon Neat](http://neat.bourbon.io) and [Bitters](http://bitters.bourbon.io).

It comes batteries–included with [git ignore rules](.gitignore), a [default project file](exalted.sublproj/default.sublime-project) for Sublime Text and best–practices for [GitHub Pages support](#github-pages-support) as well.

## What’s Mixture?

[Mixture](http://mixture.io) is the perfect front-end development tool for Mac &amp; Windows.

## GitHub Pages Support

### tl;dr

First of all, quit Mixture.

0. Add the following in `mixture.json` file by replacing `<user>` and `<repo>` accordingly:

    ```json
    "gitHubPages": {
      "repoUrl": "https://github.com/<user>/<repo>.git"
    }
    ```

0. Copy `.githubsettings-template` file in `.githubsettings`
0. Insert _your name_, _email_ and _GitHub username_ and _password_ in `.githubsettings` file:

    ```json
    {
      "email": "auto@mixture.io",
      "name": "auto",
      "password": "",
      "username": ""
    }
    ```

When you’re done, save and close everything, then open Mixture.

| Note |
| :--- |
| `.githubsettings` file is by default ignored by git (see `.gitignore`), therefore it can be “lost” if you’d clean your working copy. (e.g., `git clean`, or when switching branches, etc.) This is for your own security, so that you don’t publish your GitHub account details by mistake to the public. |

### Read more

[GitHub Pages](http://docs.mixture.io/github-pages) in Mixture documentation.
