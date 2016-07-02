# Habitica for macOS (unofficial)
![alt tag](dock.png)

## install
1. Download [Habitica.dmg](Habitica.dmg)
2. Run the file and copy the app into your Applications folder
3. Run Habitica from the Applications folder

## or build it yourself
This app is built with [nativefier](https://github.com/jiahaog/nativefier).

```bash
npm i -g nativefier
nativefier https://habitica.com
```

The dmg file is created with [appdmg](https://github.com/LinusU/node-appdmg)

```bash
npm i -g appdmg
appdmg appdmg.json Habitica.dmg
```