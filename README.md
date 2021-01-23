# Akash's build of dwm

My build of dwm on top of Luke Smith's build. Right now it's a fork but as the time progresses, I'll try to configure it acocrding to my taste.

## Patches and features

- Clickable statusbar with my build of [dwmblocks](https://github.com/skywalker212/dwmblocks).
- Reads xresources colors/variables (i.e. works with `pywal`, etc.).
- scratchpad: Accessible with mod+shift+enter.
- New layouts: bstack, fibonacci, deck, centered master and more. All bound to keys `super+(shift+)t/y/u/i`.
- True fullscreen (`super+f`) and prevents focus shifting.
- Windows can be made sticky (`super+s`).
- stacker: Move windows up the stack manually (`super-K/J`).
- shiftview: Cycle through tags (`super+g/;`).
- vanitygaps: Gaps allowed across all layouts.
- swallow patch: if a program run from a terminal would make it inoperable, it temporarily takes its place to save space.

## Installation

```
git clone https://github.com/LukeSmithxyz/dwm
cd dwm
sudo make install

```
