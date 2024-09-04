# Hi!

This is @ArcaneNibble, aka R! I'm a "hacker," "technologist," "catgirl," and many other descriptors. Here's a sampling of projects:

# Electronics

I build PCBs, including all of these:

![a collection of PCBs lying on a table (irl photo, not a render)](final-header.jpg)

| Project | Status | Description |
|-|-|-|
| [remex](https://github.com/ArcaneNibble/remex-wch) | PCB WIP | CH32V307 RISC-V MCU dev board with gigabit Ethernet |
| [PY32 fidget spinner](https://github.com/ArcaneNibble/puya-spinner) | PCB complete, firmware WIP | deliberately-overengineered fidget spinner built around a Chinese ARM MCU, showing off just how cheap technology has become |
| [LCSC parts tester](https://github.com/ArcaneNibble/china-lcsc-undoc-parts-test) | PCB complete, testing WIP | filling in missing documentation for some interesting parts found on LCSC |
| [Hexpansion headphone jack](https://github.com/ArcaneNibble/hexpansion-headphones) | Complete | headphone codec for the EMFCamp Tildagon badge |
| [Hexpansion infrared](https://github.com/ArcaneNibble/hexpansion-ir-tool) | Complete, no firmware | 38 kHz IR TX/RX for the EMFCamp Tildagon badge |
| [JLCPCB test cat ears](https://github.com/ArcaneNibble/jlc-katzen) | Complete, KNOWN ERRATA | I wanted to quickly test JLCPCB's turn-key assembly process with a 4-layer board with an unusual shape |
| [Yahoo! Paranoids DEFCON badge](https://github.com/theparanoids/keyhole-badge/) | Complete | conference badge with BLE, microphone, and blinkies |
| [Yahoo! Paranoids Hackme](https://github.com/theparanoids/hardware-hackme-1-eda) | Complete | platform for running hardware hackmes and teaching colleagues about embedded systems |
| [SLG46582 test board](https://github.com/ArcaneNibble/gp-ldo-test-board) | Shelved | cheap I2C-programmable LDOs with additional capabilities. Uncertain future after the string of M&As ending in Renesas |
| [CuteRunner](https://github.com/ArcaneNibble/cuterunner) | Shelved | cheap Xilinx/AMD CoolRunner-II dev board, killed due to chip shortage and parts becoming EOL |
| [Project Chibi board](https://github.com/ArcaneNibble/project-chibi-dev-board) | Shelved | Altera/Intel MAX V dev board. Single monolithic mega-board turned out to not be a good design. Shelved due to chip shortage |

# "Normal" software

Software for your computer, doing normal computer things. Contributions welcome!

| Project | Status | Description |
|-|-|-|
| [FastLZ in Rust](https://github.com/ArcaneNibble/fastlz-rs) | Stable | [FastLZ](https://github.com/ariya/FastLZ) reimplemented in pure-Rust |
| [uksirius](https://github.com/ArcaneNibble/uksirius) | Proof-of-concept | an effort to learn practical DSP by implementing a dial-up modem in pure software |
| [Tile Corruptor](https://github.com/ArcaneNibble/tile-coruptor) | Initial release | a tool for viewing binary data as images in various formats, which can be useful for reverse-engineering and taking shortcuts using the brain's visual system's pattern matching |

# "Embedded-related" software

Software related to embedded systems, either because it runs on an embedded platform or because it primarily deals with problems in the embedded space. Contributions welcome!

| Project | Status | Description |
|-|-|-|
| [UF2 bootloader for CH32V2xx](https://github.com/ArcaneNibble/wch-uf2) | Stable | an implementation of [UF2 (USB Flashing Format)](https://github.com/microsoft/uf2) for the CH32V2xx RISC-V MCUs |
| embedded compiler toolchain stuff | Proof-of-concept | putting compilers [in your browser](https://github.com/ArcaneNibble/web-llvm-thing) and [building a toolchain distribution](https://github.com/ArcaneNibble/toolchain-garbage) |
| [JEDEC programming file parser in Rust](https://github.com/ArcaneNibble/rust-jedec) | Stable | parser and writer for .jed files, commonly used with CPLDs |

# "Reverse-engineering-related" software

## [xc2bit](https://github.com/ArcaneNibble/xc2bit)

Reverse-engineered documentation of Xilinx/AMD CoolRunner-II CPLDs

## [Project Nanjing](https://github.com/ArcaneNibble/project-nanjing)

Reverse-engineering the WCH Bluetooth Low Energy IP in order to eliminate the binary blobs

## [Project Chibi](https://github.com/ArcaneNibble/project-chibi)

Reverse-engineered documentation of Altera/Intel MAX V/II CPLDs

## [Project New Millennium](https://github.com/ArcaneNibble/project-new-millennium)

Rough reverse-engineering notes of Altera/Intel MAX 7000 CPLDs

## [AccuVote flash tools](https://github.com/ArcaneNibble/accuvote-flash-tools)

Quick tool to dump and restore the flash memory of the AccuVote TSx voting machines used in some places in the United States

# Fun and games

## [Steam Deck gyro + flick stick controls for Minecraft](https://github.com/NEKOMods/mc-deck-native-controls)

Implement [flick stick motion controls](http://gyrowiki.jibbsmart.com/blog:good-gyro-controls-part-2:the-flick-stick) as a Minecraft Forge mod

This gets better performance/accuracy and more-powerful integration with the game engine compared to doing it externally using Steam Input

# Hacks

## [f055.cc](https://github.com/ArcaneNibble/f055-tuples)

I took over this domain a while back, but I haven't done a good job of marketing/promoting it

A registry of "16-bit numbers" that might be needed in some cases

## [langtool](https://github.com/ArcaneNibble/langtool)

Quick tool to look up Chinese words in CC-CEDICT and CC-Canto simultaneously in order to generate flashcards for Anki.

This is probably only useful for ABCs (American-Born Chinese) heritage speakers with a *highly* specific background and upbringing.

## [pokeemeraldfont](https://github.com/ArcaneNibble/pokeemeraldfont)

A demo abusing font ligatures and "emoji" fonts in order to turn the names of Pokemon into icons

## [BLE dog shock collar reverse engineering](https://github.com/ArcaneNibble/miniature-octo-disco)

We along with an anonymous friend reverse engineered the Dr.Trainer BLE-controlled dog shock collars

## [Sega Saturn CD controller block](https://github.com/ArcaneNibble/laughing-waffle)

I reproduced the published hack to dump the Sega Saturn CDB microcontroller

## [TPM2 LUKS](https://github.com/ArcaneNibble/tpm2-luks)

Very-old experiments with sealing LUKS keys to a TPM
