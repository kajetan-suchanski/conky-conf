# Conky configuration

My simple [conky](https://github.com/brndnmtthws/conky) configuration file. It updates every 3 seconds and shows the
following information:

* CPU usage
* RAM usage
* Swap usage
* Top 5 applications with the highest CPU usage
* Top 5 applications with the highest RAM usage

## System requirements

This branch is dedicated to **12 CPUs** and **Full HD** (1920×1080) display.

## Installation

In order to you use it, just run these simple commands (assuming you have *conky* and *git* installed):

```shell
mkdir ~/.config/conky
cd ~/.config/conky
git clone https://github.com/kajetan-suchanski/conky-conf.git .
```