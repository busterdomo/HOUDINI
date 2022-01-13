# 🐳 HOUDINI: Hundreds of Offensive and Useful Docker Images for Network Intrusion
HOUDINI is a curated list of **Network Security** related Docker Images for Network Intrusion purposes. A lot of images are created and kept updated through our [RAUDI](https://github.com/cybersecsi/RAUDI) repository. Pretty dope, eh?

## Table of Contents
  - [Web App](#web-app)
  - [Add a Tool](#add-a-tool)
  - [Development](#development)
  - [Credits](#credits)
  - [License](#license)

## Web App
To use HOUDINI, click the link below: 
- https://houdini.secsi.io

## Add a tool
To add a new tool you have to:
- Add it to the configuration (*src/config/tools.ts*)
- Add a **Markdown** file in the tools directory (*src/_tools/*)
You may do it manually or you may use the **bootstrap** command:
```
yarn run bootstrap
```

This command automatically copies a template Markdown in the tools directory and outputs the **JavaScript Object** that you need to insert in the configuration.

## Development
This section provides a set of commands to run the application locally. 

PLEASE use **yarn** over **npm**

### Setup
This is a **React** based application. Before running it you have to install all the needed packages with the following command:
```
yarn install
```

### Run
To execute the app locally you have to run:
```
yarn start
```

### Build
To build the app you have to run:
```
yarn run build
```

## Credits
HOUDINI is proudly developed [@SecSI](https://secsi.io) by:
- [Angelo Delicato](https://github.com/thelicato)
- [Daniele Capone](https://github.com/daniele-capone)

## License
**HOUDINI** is an open-source and free software released under the [GNU GPL v3](/LICENSE).