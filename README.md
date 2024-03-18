# Deepin screenshot

### Why would you fork a fork and modify that?
TLDR; I'm lazy. See [Qubes-Docs](https://github.com/ClaraCrazy/qubes-docs/blob/main/modified-things/readme.md) for why this is even "needed".

<br>

> [!CAUTION]
> Some of this is stil slightly broken. QMagic makes no sense to me, neither does cpp, so I wont be able to fix it. Main issue: [This](https://github.com/ClaraCrazy/deepin-screenshot/blob/fork-of-a-fork/src/controller/resource.qrc) (aka. [this](https://github.com/ClaraCrazy/deepin-screenshot/blob/fork-of-a-fork/src/controller/menucontroller.cpp)) doesnt wanna import the images properly. Might be a super easy fix, but I dont really have time to try, nor do I care just for my stupid fork to run it in dom0. GLHF

<br>

<summary>Original README</summary>
<details>
    
## Description

This is a default screenshot app for Linux Deepin.

## Dependencies

- Qt (>=5.6),
- debhelper (>=9),
- cmake, qt5-default, qtbase5-dev, pkg-config, libqt5svg5-dev, libqt5x11extras5-dev, qttools5-dev-tools,
- libxcb-util0-dev, libstartup-notification0-dev,
- qtbase5-private-dev, qtmultimedia5-dev, x11proto-xext-dev, libmtdev-dev, libegl1-mesa-dev, x11proto-record-dev,libxtst-dev,
- libudev-dev, libfontconfig1-dev, libfreetype6-dev, libglib2.0-dev, libxrender-dev,
- libdtkwidget-dev, libdtkwm-dev, deepin-gettext-tools

## Installation

- On the Deepin operation system: the deepin screenshot is published within!
- On other operation system, you could download the source code of deepin screenshot:
    - firstly, install the dependencies rightly;
    - secondly, run `cd deepin-screenshot`;
    - thirdly, make a directory: build; run `cmake ../`; `make`; `make install`

## Usage
Run the command: `deepin-screenshot`

## Getting help

Any usage issues can ask for help via

* [Official Forum](https://bbs.deepin.org/)
* [Developer Center](https://github.com/linuxdeepin/developer-center)
* [WiKi](https://wiki.deepin.org/)
* [Gitter](https://gitter.im/orgs/linuxdeepin/rooms)
* [IRC channel](https://webchat.freenode.net/?channels=deepin)

## Getting involved

We encourage you to report issues and contribute changes

* [Contribution guide for developers](https://github.com/linuxdeepin/developer-center/wiki/Contribution-Guidelines-for-Developers-en). (English)
* [开发者代码贡献指南](https://github.com/linuxdeepin/developer-center/wiki/Contribution-Guidelines-for-Developers) (中文)

## License

deepin-screenshot is licensed under [GPLv3](LICENSE).

</details>
