[![We accept GEN](https://img.shields.io/badge/We_accept-GEN-brightgreen.svg)](https://github.com/GenesisCommunity/go-genesis/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![Go Report Card](https://goreportcard.com/badge/github.com/GenesisKernel/go-genesis)](https://goreportcard.com/report/github.com/GenesisKernel/go-genesis)
[![Build Status](https://travis-ci.org/GenesisKernel/go-genesis.svg?branch=master)](https://travis-ci.org/GenesisKernel/go-genesis)
[![Documentation](https://img.shields.io/badge/docs-latest-brightgreen.svg?style=flat)](http://genesiskernel.readthedocs.io/en/latest/)
[![](https://tokei.rs/b1/github/GenesisKernel/go-genesis)](https://github.com/GenesisKernel/go-genesis)
![](https://reposs.herokuapp.com/?path=GenesisKernel/go-genesis&style=flat)
[![API Reference](
https://camo.githubusercontent.com/915b7be44ada53c290eb157634330494ebe3e30a/68747470733a2f2f676f646f632e6f72672f6769746875622e636f6d2f676f6c616e672f6764646f3f7374617475732e737667
)](https://godoc.org/github.com/GenesisKernel/go-genesis)
[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/GenesisKernel?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

<p align="center">
  <img src="https://i.imgur.com/4lMw23m.png" width="500">
</p>
<br>

## Contents

- [Introduction](#introduction)
- [Why is Genesis Unique?](#why-is-genesis-unique)
- [How Genesis Works](#how-genesis-works)
- [Quick Start](#quick-start)
- [Plans](#plans)
- [Participation in Development](#participation-in-development)
- [Documentation](#documentation)
- [Developers](#developers)
- [License](#license)

## Introduction
Genesis is an open-source blockchain platform, the basis of which was laid in 2011 by programmer Oleg Strelenko. The platform's code was written completely from the ground up. Currently, there is a team of over 15 top-tier software developers working on the project. We can't run an ICO for the concept of Genesis the way that we like, that's why we decided to give away 85% of all tokens to a maximum number of programmers, so that with the help of the community Genesis becomes the best blockchain platform in the world.

## Why is Genesis Unique?
 - In Genesis you can create your own blockchain ecosystem with customized rules. In essence, you can create your own "Ethereum", which can easily interact and communicate with your neighbor's "Ethereum" (another ecosystem on Genesis).
 - Developing applications on the Genesis platform is easy and fun. Mastering the platform's programming languages – Simvolio and Protypo - will take you around just four hours.
 - You'll be able to immediately upload your newly developed applications on Simvolio and Protypo directly to your mobile device running IOS or Android. You can do this using our application, which is soon to be available from Appstore and Google Play. Or you can upload your version after making some changes to our source codes.
 - All of the platform's parameters (even the consensus algorithm!) are fully customizable, and can be changed by community voting or by any other algorithms.

## How Genesis Works
Develop your applications using [Simvolio](http://genesiskernel.readthedocs.io/en/latest/introduction/script.html#simvolio-contracts-language). Simvolio is a С-like programming language used for creating contracts and which is compiled to byte code. It has a minimum required number of program control commands and predefined functions.
<p align="center">
    <img src="https://i.imgur.com/qHosOsw.jpg">
</p><br>

Create interfaces using [Protypo](http://genesiskernel.readthedocs.io/en/latest/introduction/templates2.html#protypo-template-language). Protypo is a language for creating frontend pages. It is in essence a template engine which transforms a sequence of functions with parameters into a tree structure with elements, which can be then used for the front-end.

<p align="center">
    <img src="https://i.imgur.com/CYL1b95.jpg">
</p>
<br>

Establish [rights](https://genesiskernel.readthedocs.io/en/latest/introduction/what-is-Apla.html#access-rights-control-mechanism) for changing the code of contracts/interfaces and data in registers

<p align="center">
    <img src="https://i.imgur.com/DkvR7MZ.jpg">
</p>
<br>

Post your blockchain application on Google Play or Appstore. <br>
https://github.com/GenesisKernel/genesis-reactnative <br>


## Quick Start
<p align="center">
    <img src="https://i.imgur.com/6oYykyk.jpg">
</p>

https://github.com/GenesisKernel/quick-start<Br>

Deploy an instance on macos:<br>
```bash
bash manage.sh install 3 (creates and launches 3 local nodes)
```
Deploy an instance on linux:<br>
```bash
bash manage.sh install 3 (creates and launches 3 local nodes)
```
Deploy an instance on windows:<br>
https://github.com/GenesisKernel/quick-start-win/releases<br>
```bash
win_install.exe
```

#### Console Blockexplorer 
```bash
bash manage.sh db-shell 1
```
```bash
select id, time, node_position, key_id, tx from block_chain ORDER BY ID DESC LIMIT 20;
```
List of block-generating nodes:<br>
```bash
select value from system_parameters where name='full_nodes';
```
The web version of the Blockexplorer will be available soon.<br>


## Plans
We believe that our code can be improved, that is why we are committed to further enhancing its quality and performance.

#### Testnet

[date to be announced]<br>

#### Mainnet

[date to be announced]<br>

## Participation in Development
Please, read the [CONTRIBUTING.md](https://github.com/GenesisKernel/go-genesis/blob/master/CONTRIBUTING.md) to get all the detailed information about sending Pull Requests.

## Documentation
Please, study and expand our [documentation](https://genesiskernel.readthedocs.io/en/latest/#contents)

## Developers
See the list of [developers & contributors](https://github.com/GenesisKernel/go-genesis/graphs/contributors) who participated in this project.
<br>
[Join](mailto:hello@genesis.space) the Genesis team!

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/GenesisKernel/go-genesis/blob/master/LICENSE) file for details

<p align="center">
<a href="#"><img src="http://www.kgsbo.com/wp-content/themes/kgsbo/images/top.png" width=100 align="center"></a><br>
  <a href="#">Back to top</a>
</p>
