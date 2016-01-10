# FreePI
FreePI is a router where FreeBSD meets Raspberry PI 2 model B.

The goal is to support: VLANS, PF firewall, Squid/SquidGuard, HTTP anitvirus, VPNS and much more features that a home router can have.

Raspberry PI 2 model B has only one ethernet port but its not an issue at all, FreePI is built with support of VLANS, in DIY project I use [Mikrotik RB260GSP](http://routerboard.com/RB260GSP) switch.

FreePI is still in developing stage same as FreeBSD 11. 

The existing biggest bug is pfctl crashes when is being run with the show flag. 

There are many packages were compiled but not tested, if you decide to try FreePI you can contact me at pg@ambient-md.com or you can build your own FreePI using the [wikis`](https://github.com/PetruGarstea/FreePI/wiki) instructions.

