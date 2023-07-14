# n64brew-gamejam-2023
A Nintendo 64 game, created with libdragon for the 2023 N64Brew Summer Game Jam

I'm using the libdragon cli and docker to make my project setup a lot cleaner and easier.

## System prereqs:

* docker >=24

  * I'm using latest [Docker Desktop for Windows](https://www.docker.com/products/docker-desktop/), which has docker 24.0.2

* npm >=18
	
  * I'm using the lts version, 18.16.1, installed with [nvm for windows](https://github.com/coreybutler/nvm-windows/releases)


## Setup commands:

	git clone --recursive https://github.com/kivan117/n64brew-gamejam-2023.git
	cd .\n64brew-gamejam-2023\
	npm install -g libdragon
	libdragon make

You don't strictly *have* to use npm or the libdragon cli. But I am.
