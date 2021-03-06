# node-fxos

Simplify interaction between mankind and FirefoxOS during webapps development

![presentation](https://raw.githubusercontent.com/nicola/node-fxos/master/site/media/presentation.png)

- node-fxos [website](http://nicola.github.io/node-fxos)
- Presentation [slides](http://nicola.github.io/node-fxos-presentation)
- Video [Mozilla SF - Nicola Greco, node-fxos ninja tools for Firefox OS development](https://air.mozilla.org/nicola-greco-node-fxos-ninja-tools-for-firefoxos-development/)
- Discuss on [HackerNews](https://news.ycombinator.com/item?id=8472673)

## Idea

Instead of having a big tool that does everything, the idea here is to have very little libraries that do one thing well, so that you can roll your own command line tool, deployment and testing strategies and gulp/grunt script to enhance your Firefox OS development experience.

The aim of these components is to use the [Firefox Remote Debugging Protocol](https://wiki.mozilla.org/Remote_Debugging_Protocol) with [harthur/firefox-client](https://github.com/harthur/firefox-client).

## Modules

- [x] **[fx-ports](https://github.com/nicola/fx-ports)** - Find Firefox(OS) listening debugging ports
- [x] **[fxos-simulators](https://github.com/nicola/fxos-simulators)** - Find FirefoxOS simulators binaries
- [x] **[fxos-start](https://github.com/nicola/fxos-start)** - Start a FirefoxOS simulator
- [x] **[fxos-deploy](https://github.com/nicola/fxos-deploy)** - Deploy a webapp to FirefoxOS
- [x] **[fxos-findapp](https://github.com/nicola/fxos-findapp)** - Find an app on FirefoxOS given a manifest
- [x] **[fxos-reloadcss](https://github.com/nicola/fxos-reloadcss)** - Live-reload CSS in FirefoxOS
- [x] **[fxos-connect](https://github.com/nicola/fxos-connect)** - Connect to an open simulator or start a new one
- [x] **[fxos-console](https://github.com/nicola/fxos-console)** - Bind interactive FXOS console
- [x] **[fxos-console-logs](https://github.com/nicola/fxos-console-logs)** - Bind console.log-s to node
- [ ] **fxos-screenshot**

## Projects using fxos modules

- **[FirefoxOS Gulp Example](https://github.com/nicola/gulp-firefoxos-example)**: Gulpfile.js using node-fxos modules
- **[FirefoxOS Grunt Example](https://github.com/Mte90/grunt-firefoxos-example)**: Gruntfile.js using node-fxos modules
- **Fireplay Atom**: Plugin for Atom for live editing FirefoxOS apps' HTML and CSS
