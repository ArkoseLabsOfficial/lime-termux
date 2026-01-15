[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg?style=flat)](LICENSE.md)

ArkoseLab's Lime Fork
====

This Lime fork is using for the Android and iOS ports I provided. Although Homura's Fork is no longer support for those ports, this fork is reviving the support for those ports


License
=======

My Lime Fork uses the same [MIT license](LICENSE.md) that OpenFL provides.


Installation
============

1. Clone the Lime repository:

        https://github.com/ArkoseLabsOfficial/lime-termux

2. Install required dependencies:

        haxelib git format https://github.com/FNF-SE/format
        haxelib git hxp https://github.com/FNF-SE/hxp

3. After cloning see [project/README.md](project/README.md) for details about building native binaries.

4. After any changes to the [tools](tools) or [lime/tools](src/lime/tools) directories, rebuild from source:

        lime rebuild tools

5. To switch away from a source build:

        haxelib set lime [version number]
