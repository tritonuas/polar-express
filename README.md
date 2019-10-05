# Polar Express
> [ALLLLLLLLL ABOOOOAAAARD](https://www.youtube.com/watch?v=syzjW0YK_FQ)

Welcome to TUAS Software Team!

This repo (hopefully) contains all knowledge necessary to get you up and
running. There are a series of scripts and bash tweaks to ease set up of your
development environment. Running ./setup.sh should do everything you need.

Check out the Wiki for more info.

Why is this called the Polar Express? In the *Polar Express* a young boy learns
that in order to hear the magic he simply needed to believe. Thus, for us to
succeed in everything we do we must believe that we can!

## Things To Install
### Everyone
- [git](https://git-scm.com/) (Duh) - version control and getting everything in the first place
- [docker](https://docs.docker.com/v17.12/install/#supported-platforms) - setting up containerized environments, running simulations of other parts of software suite
- [docker-compose](https://docs.docker.com/compose/install/) - for running multiple docker containers at the same time
- python3 - most of our codebase is written in this (doesn't matter which version you install, pyenv will override it)
- pip3 - package manager
- [pipenv](https://github.com/pypa/pipenv) - package/environment management (like virtualenv but better)
  - [Real Python Tutorial](https://realpython.com/pipenv-guide/)
- [pyenv](https://github.com/pyenv/pyenv) - python version management (use to switch to python 3.7)
  - [Real Python Tutorial](https://realpython.com/intro-to-pyenv/)

### Computer Vision Team
- [opencv](https://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_tutorials.html) - computer vision shenanigans
- [pytorch](https://pytorch.org/) - for ML

- OPTIONAL: [Download more RAM](https://downloadmoreram.com/)

### Path Planning Team
- [rust](https://www.rust-lang.org/) - dubins path algorithm currently implemented in Rust
- [mavproxy](http://ardupilot.github.io/MAVProxy/html/index.html)
- [SITL stuff](http://ardupilot.org/dev/docs/setting-up-sitl-on-linux.html) - for simulating plane

### Frontend Team
- [nodejs](https://nodejs.org/en/download/) - because web dev
  - [NodeSchool Interactive Tutorial](https://nodeschool.io/#workshoppers) - Skip all the pure node stuff, learn node with express
- [yarn](https://yarnpkg.com/lang/en/) - because someone decided to use yarn instead of npm... (should be installed automatically with node)
- [ReactJS](https://reactjs.org/) - frontend web dev

### Infrastructure ~Team~Anh
- [golang](https://golang.org/) - for concurrent communication
- [protobufs](https://developers.google.com/protocol-buffers/) - serialization just got real

### Hardware Team
- If Jose decides not to set up the Nvidia Jetson OBC for us, someone's gonna have to go flash it and install our saliency suite onto it

### Strongly Suggested
- Vim - great editor, lightweight and very easy to make quick changes as well as program
- [Tmux](https://www.hamvocke.com/blog/a-quick-and-easy-guide-to-tmux/) - terminal multiplexer, lets you split terminal windows and run things in background
- [Ubuntu 18.04](http://releases.ubuntu.com/18.04/) - linux > mac >>> windows
  - [Dual Boot](https://opensource.com/article/18/5/dual-boot-linux) - install Linux alongside Windows on same hard drive
    - [YUMI](https://www.pendrivelinux.com/yumi-multiboot-usb-creator/)
    - [Etcher](https://www.balena.io/etcher/)
  - Virtual Machine: [VMWare Player](https://www.vmware.com/products/workstation-player.html) - install Linux on a "simulated" machine with different kernel
  - [Windows Subsystem](https://docs.microsoft.com/en-us/windows/wsl/install-win10) - Windows installs a cute little Linux distribution on your computer. Sort of unreliable and slow, but it's the easiest method
