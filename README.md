# workspaces-poc
Evaluate Yarn Workspaces, and add ability to build Docker Images per package


# Yarn 2 notes

FIRST READ THIS: https://dev.to/arcanis/introducing-yarn-2-4eh1

When you clone the repo, it is already configured to use yarn 2.

`yarn -v` should return `2.0.0+`

According to Yarn, it is not recommended to install `yarn2` as global.

## Some useful commands

`yarn workspaces list` - list of all workspaces.

`yarn workspace <workspace> command` to do something in a workspace. (e.g `yarn workspace lib1 add lodash` will add lodash dependency to lib1)

## Plugins

yarn exposes extra functionality via plugins.

`yarn plugin import workspace-tools` will install workspace-tools plugin.

Will allow you to

`yarn workspaces foreach command` to do something on every workspace.