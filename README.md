<p align="center">
  <a href="https://github.com/spicesouls/spice.net">
    <img src="spice.net.png" alt="Logo" width="600" height="159">
  </a>

  <p align="center">
    An open-source backdoor tool for connecting to machines and executing commands!
    <br />
    <a href="https://github.com/spicesouls/spice.net"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/spicesouls/spice.net/blob/master/README.md#guide">Installation & Usage Guide</a>
    ·
    <a href="https://github.com/spicesouls/spice.net/issues">Report Bug</a>
    ·
    <a href="https://github.com/spicesouls/spice.net/issues">Request Feature</a>
  </p>
</p>
</p>


### Table of Contents
* [About](#about)
* [Guide](#guide)
  * [Installation](#installation)
  * [Setting Up](#setting-up)
  * [Backdooring The Machine](#backdooring-the-machine)
  * [Connecting Through The Backdoor](#connecting-through-the-backdoor)
  * [Using Commands](#using-commands)
* [Contact](#contact)

## About

**Spice.Net** is a tool made for assistance with compromising and enumerating machines, as well as monitoring them and acting as a simple method to access said machine remotely. It uses `python sockets` to communicate between the compromised machine running Spice.Net and any other machine connecting using spice.net.

## Guide

Here, I'll explain how to install, set up and use Spice.Net effectively.

### Installation

To Install this, you can use the `git` command. If you don't have this command, you can install it with:
```sh
sudo apt install git
```
With the `git` command, you can install **Spice.Net** with:
```sh
git clone https://github.com/spicesouls/spice.net
```
![Demonstration Of Installation](imgs/demo1.PNG)

### Setting Up

Setting up **Spice.Net** is as easy as the installation was, and can be done in as little as one line! Here it is:
```sh
cd spice.net; chmod +x setup.sh; ./setup.sh
```
![Demonstration Of Setting Up](imgs/demo2.PNG)

### Backdooring The Machine

Now we have **Spice.Net** set up and ready, we can now plant a backdoor on our target machine! Once you've setup **Spice.Net** on your target machine, run `victim.sh`. This will host a **Spice.Net** service for you to connect back to! You can run `victim.sh` by simply using:
```sh
./victim.sh
```
![Demonstration Of Running victim.sh](imgs/demo3.PNG)

![Demonstration Of Running victim.sh](imgs/demo3.5.PNG)

### Connecting Through The Backdoor

Now we have the **Spice.Net** service running on our target machine, we can connect to the machine through this and use it as a backdoor! You can connect from any machine by running `connect.sh`. You can do this by using:
```sh
./connect.sh
```
You will then be asked for the IP of the machine that is running **Spice.Net**, so you can choose which machine to connect to!

![Demonstration Of Running connect.sh](imgs/demo4.PNG)

### Using Commands

Now that you are connected, you can now input commands to be executed! You can start by using the command `help`, this will list all commands available for use as well as how to use them. You can also use the command `info` to get basic information about the machine you are connected to.

![Demonstration Of Using The 'info' Command](imgs/demo5.PNG)

## Contact

<p align="center">
  <a href="https://twitter.com/SpicysoulsV">Twitter</a>
  ·
  <a href="https://beyondr00t.wordpress.com">Blog</a>
  ·
  <a href="https://steamcommunity.com/id/SpiceSouls/">Steam</a>
</p>
