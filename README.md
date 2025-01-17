# OpenSumi IDE Electron

English | [中文文档](https://opensumi.com/zh/docs/integrate/quick-start/electron)

![OpenSumi Desktop](./snapshots/sumi-electron.png)

## Startup

```shell
git clone git@github.com:opensumi/ide-electron.git
cd ide-electron
yarn
yarn run build
yarn run rebuild-native -- --force-rebuild=true
yarn run download-extension # install extension (Optional)
yarn run start
```

## Develop

Start application:

```shell
yarn run watch
yarn run start
```

When there are new changes in the code, open the command panel in the editor <kbd>shift</kbd>+<kbd>command</kbd>+<kbd>p</kbd>, select and run the 'Reload Window' to reload the current editor window.

## package to DMG

package the project, and the installation package in the `out` directory:

```shell
yarn run pack
```
