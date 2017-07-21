# Foundation CSS framework

Sixgill CSS framework is based on Foundation for Apps by ZURB

  - [Foundation for Apps homepage](http://foundation.zurb.com/apps.html)
  - [Foundation for Apps on Github](https://github.com/zurb/foundation-apps)

### Requirements

You'll need the following software installed to get started.

  * [Node.js](http://nodejs.org) 0.12+: Use the installer provided on the NodeJS website.
  * With Node installed, run `[sudo] npm install -g gulp bower`.
  * [Git](http://git-scm.com/downloads): Use the installer for your OS.
  * Windows users can also try [Git for Windows](http://git-for-windows.github.io/).


### Installing

Easiest is to install The Foundation CLI through npm.

```bash
npm install -g foundation-cli
```

This will add the `foundation` command to your system.

### Updating

The CLI periodically gets updates that add features or fix bugs. Use npm to upgrade the CLI to the newest version.

```bash
npm update -g foundation-cli
```

To check what version you currently have, use `-v`.

```bash
foundation -v
```

### Running

While inside of `foundation-css` folder, run `foundation watch` to assemble app and automatically run a test server for css.

```bash
cd foundation-css
foundation watch
```

While this process is running, you can view the assembled app in your browser, at this URL:

```
http://localhost:8079/
```

### Building

To build css for production, use `foundation build`.

```bash
foundation build
```

### CSS organization

All source SCSS files live inside: `client/assets/scss/` folder

All template HTML files can be found inside: `client/templates/` folder

All build outputs go to: `build` folder

### Edits
