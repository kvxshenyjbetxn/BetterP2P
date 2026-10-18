# BetterP2P

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0) 

![logo](logo.png)

Better P2P and memory card for Applied Energistics 2, requires [Forgelin](https://www.curseforge.com/minecraft/mc-mods/shadowfacts-forgelin).

Documentation is now available to read: <https://lasmgratel.github.io/BetterP2P-Manual/>

## Features

Obtain a Better Memory Card.

![](img/showcase0.png)

Right-click on a P2P device or any ME attached device to inspect all P2P devices in your ME Network.

![](img/showcase1.png)

Select one of the P2P devices and pair it with other P2P, you can choose the binding mode. Once you have P2P devices paired, devices with same frequency will be highlighted in aqua color.

![](img/showcase2.png)

Input P2P will always be on the top.

![](img/showcase3.png)

A wrong setup (usually P2P devices without input) will be in red color, and devices with no channel will be in yellow.

![](img/showcase4.png)

Version 1.1 update:

P2P location is shown.

![](img/showcase5.png)

When you select one of the P2P device, outlines will render at other devices with same frequency.

You can Shift-click better memory card to clean this outline.

![](img/showcase6.png)

### Show connections

Select a bound P2P tunnel, then click the crosshair button (**Show connections**) below the refresh button. The GUI closes and highlights the selected tunnel and all same-type tunnels on its frequency **while holding the Advanced Memory Card**, with lines from the center of the screen visible through blocks. Inputs are green and outputs are cyan. Search filters do not hide connected endpoints, and tunnels without channels are included.

There is no timer. Putting the card away hides the locator; holding it again restores the lines. Right-click the card in the air or use it on any P2P tunnel to turn the locator off. Clicking a P2P still opens its GUI as usual; use **Show connections** again to enable lines for the new selection. Sneak-right-click also retains its existing clear behavior. Only endpoints in your current dimension can be drawn; chat reports how many endpoints are in other dimensions. Changing dimensions or leaving the world clears the locator. This is a client-side locator using the GUI's latest server-supplied snapshot; it does not change tunnel bindings.

## TODOs

- [ ] Documentation
- [ ] Sort modes
- [ ] Better predicate to reduce crashes
- [X] Backport to 1.7.10
- [X] A border show in the world to identify the selected P2P device
- [ ] Optimize cache
- [ ] A minimap shows all P2P devices

## Credits

Cyclic for its block outline code
