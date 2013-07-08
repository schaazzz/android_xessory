Xessory
=========

Xessory is an attempt at taking a library based approach towards Android Accessories. The goal is to create abstraction top of the ADK, this includes a framework for the host side application, e.g. embedded hosts on microcontrollers (AVR, PIC32, a few ARM variants), a Linux PC (or an Embedded Linux target for that matter).

History
========

I needed a way to attach a terminal for some basic IO to a *"headless"* Embedded Linux system in an instance where the network was temporarily unavailable (details unimportant), and thought that a tablet running in accessory mode would be the perfect solution. I prototyped the Linux USB host application on a desktop Linux VM (Linux Mint on Virtual Box to be exact). It was an interesting exercise so I decided to do a write-up for my own record which could perhaps serve as a tutorial for someone else as well but along the way decided to go one step further with a few demo applications.

 License
===========

MIT
