# README

## Cash

**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [Download (Fork) the project](#intro)
- [Node.js installation](#installNode)
  - [Windows install](#WindowsNode)
  - [Linux install](#LinuxNode)
- [Lybrary installation](#installLibrary)
  - [Windows install](#WindowsLibrary)
  - [Linux install](#LinuxLibrary)
- [Use the program](#use)

## Download (Fork) the project

To start you need to download [this](#https://github.com/NicoMonteil/3-musketeers) project on your computer.

#### To do this :
1. You need to Fork on the ```github```
2. After, you can clone the forked project in your repository ```https://github.com/YOUR_USERNAME/3-musketeers```

```sh
❯ cd /path/to/workspace
❯ git clone git@github.com:YOUR_USERNAME/3-musketeers.git
```
## Node.js installation

#### Windows installation
To install node.js on Windows, you can follow [this tutorial](#http://blog.teamtreehouse.com/install-node-js-npm-windows)

#### Linux installation
To install node.js on Linux, you have to install npm, by enter the following commands on on the terminal :
###### install npm
```sh
$ sudo apt-get install npm
```
###### install learnyounode
```sh
$ sudo apt-get install learnyounode
```

## Library installation
#### Windows installation
Go on the cmd in your workspace, in /3-musketeers/cash and enter the following command :
```sh
$ npm install
```

#### Linux installation
Go on the terminal in your workspace, in /3-musketeers/cash and enter the following command :
```sh
$ npm install
```

## Use the program
Open the cmd (on Windows) or the terminal (on Linux) and go on the /3-musketeers/cash/bin, and enter the following command :
#### Windows installation
Go on the cmd in your workspace, in /3-musketeers/cash and enter the following command :
```sh
node index.js 1 USD
```
You can enter any amount you want and the program will convert it for you.
You can also select in which currency you want to convert by adding behind the ones your looking for, like the following command:
```sh
node index.js 1 USD EUR GBD CAD
```
