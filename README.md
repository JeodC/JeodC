# Hello, I'm Jeod!

[![Twitter: JeodPM](https://img.shields.io/twitter/follow/JeodPM?style=social)](https://x.com/JeodPM)
[![GitHub JeodC](https://img.shields.io/github/followers/JeodC?label=follow%20Me&style=social)](https://github.com/JeodC)
[![Kofi](https://img.shields.io/badge/Kofi-F16061.svg?logo=ko-fi&logoColor=white)](https://ko-fi.com/jeodc)

#

I bring PC games to retro handhelds as ports!

Linux handhelds often use aarch64 architecture. Since many games aren't built for aarch64 by default, I design wrappers to help them run. I use many tools to help with this, including:

- [GPtoKeyB](https://github.com/EmuELEC/gptokeyb) by EmuELEC, a Gamepad to Keyboard emulator that also supports mouse emulation.
- [GMLoader](https://github.com/JohnnyonFlame/droidports) and [GMLoader-Next](https://github.com/JohnnyonFlame/gmloader-next) by JohnnyOnFlame, which translate GameMaker bytecode to linux (with some limitations)
- [Gl4es](https://github.com/ptitSeb/gl4es) by ptitSeb, which translates OpenGL functions and symbols to GLES (helps embedded systems)

My ports always require the end-user supply their own game data for games that are not licensed for distribution. This means games must be purchased on Steam or GOG or another supported PC platform. In other words, the port wrapper supplies the ship, and end-users supply the cargo.

#

I also work with a bit of Python:

- [EmulationStation Tools](https://github.com/JeodC/EmulationStation-Tools) - A collection of scripts for various use cases within the emulationstation frontend.
- [EmulationStation ImageMaker](https://github.com/JeodC/EmulationStation-ImageMaker) - Takes several elements meant for a single image and combines them into one. Makes it easy to generate custom cover art.
