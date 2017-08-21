# Sense UI CSS framework

Sixgill Sense UI CSS framework is based on Foundation for Apps by ZURB

  - [Foundation for Apps homepage](http://foundation.zurb.com/apps.html)
  - [Foundation for Apps on Github](https://github.com/zurb/foundation-apps)

### Requirements

You'll need the following software installed to get started.

  * [Node.js](http://nodejs.org) 0.12+: Use the installer provided on the NodeJS website.
  * With Node installed, run `[sudo] npm install -g gulp bower`.
  * [Git](http://git-scm.com/downloads): Use the installer for your OS.
  * Windows users can also try [Git for Windows](http://git-for-windows.github.io/).


### Installing

After cloning the repo run:

```bash
npm install
```

This will install all dependencies that you need to run the framework.

### Running

Run `gulp sever` to assemble app and automatically run a test server for css. The CSS framework will watch for changes and update automatically.

```bash
gulp server
```

While this process is running, you can view the assembled app in your browser, at this URL:

```
http://localhost:8079/
```

### Building

To build css for production, use `gulp build --production`.

```bash
gulp build --production
```

This will minimize & compile all scss files into a single app.css file that is used in Sixgill Sense App.

### CSS organization

All source SCSS files live inside: `client/assets/scss/` folder

All template HTML files can be found inside: `client/templates/` folder

All build outputs go to: `build` folder

### Making New Build with Tag

To view all existing tags run `git tag`

Make a new tag by running `git tag v0.0.X` and bump X to a higher version than the last tag.

Last thing to do is run `git push --tags` which will push the tag to Git and make it live.

Remember to update `package.json` and update the version to correspond with new tag!
