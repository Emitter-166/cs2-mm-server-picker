[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]

# **CS2** MM SERVER PICKER

![app](https://github.com/Jyben/csgo-mm-server-picker/blob/master/app/assets/img/app.gif)

## Prerequisites

On Windows, the app create a new rule in your firewall. **So you have to activate it.**

## Download
Available on Windows & Linux : [download](https://github.com/Jyben/csgo-mm-server-picker/releases/latest)

## Description

This application allows you to select the Steam servers on which you want to play for the game Counter Strike : Global Offensive.  
Administrator rights are required to block the IP addresses of the servers. For security reasons, requests for rights are systematic with each click on the "GO" and "Reset" buttons.  
The IP addresses are automatically updated without any action on my part and the application is updated automatically.  
This app is developed with the [Electron](https://electronjs.org/) framework.

## Disclaimer

Since we do not have direct access to the IP addresses of the game servers but only to the relayed addresses, you may not be connected to the desired server. The application is therefore used to get as close as possible to the desired server.

## Tips

- You can launch CS:GO with the associate button 
- You can reset the configuartion at any time with the associate button (it will remove all the rules from your firewall or your iptables)
- You just have to block the servers one time and you don't have to let the app open when you play
- But, Valve regulary update his servers so you have to reset the configuration too
- You can select several regions and servers
- The reset button also reset your selection of servers in the list
- The application updates itself (you just have to restart it when asked)

## Installation

Windows installer :
> **csgo-mm-server-picker-setup-*x.x.x*.exe**

Linux app image :
> **csgo-mm-server-picker-*x.x.x*-x86_64.AppImage**

## Report a bug

Please provide the log file when you report an issue, you can find the files under the name "csgo-mm-server-picker.log" here :

Windows : 

> C:\Users\\**user name**\AppData\Local\Programs\csgo-mm-server-picker

Linux : (I have to found a better way to put logs in is own folder)

> file:///home/**user name**

## Development & Build

This app requires [Node.js](https://nodejs.org/) and [Electron](https://electronjs.org/) to run.

Install the dependencies and devDependencies and start the app :

```sh
$ cd csgo-mm-server-picker/desktop
$ npm install -d
$ npm run start
```

To build and package :

```sh
$ npm run dist
```

[contributors-shield]: https://img.shields.io/github/contributors/Jyben/csgo-mm-server-picker.svg?style=for-the-badge
[contributors-url]: https://github.com/Jyben/csgo-mm-server-picker/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Jyben/csgo-mm-server-picker.svg?style=for-the-badge
[forks-url]: https://github.com/Jyben/csgo-mm-server-picker/network/members
[stars-shield]: https://img.shields.io/github/stars/Jyben/csgo-mm-server-picker.svg?style=for-the-badge
[stars-url]: https://github.com/Jyben/csgo-mm-server-picker/stargazers
[issues-shield]: https://img.shields.io/github/issues/Jyben/csgo-mm-server-picker.svg?style=for-the-badge
[issues-url]: https://github.com/Jyben/csgo-mm-server-picker/issues
