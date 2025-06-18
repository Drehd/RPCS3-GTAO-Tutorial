# RPCS3 GTAO Tutorial

## Intro

This tutorial expects that you are somewhat familiar with emulation, usage of RPCS3 and general computer usage. I'm fairly certain you can google any issue you come across and find a solution in seconds. Piracy is bad, this guide assumes you own a PS3, GTA V (maybe even the Collectors Edition) and you would like to try out exciting new technologies such as emulation, but you don't have a Blu-ray reader for your PC.

## The Basics

Download & Install [RPCS3](https://rpcs3.net/download)

Download the OS From [Sony's Website](https://www.playstation.com/en-us/support/hardware/ps3/system-software/) and Install it in RPCS3

Download [pkg2zip](https://github.com/mmozeiko/pkg2zip/releases)

Download [Nopaystation](https://nopaystation.com/)
- Download [PS3 Games TSV](https://nopaystation.com/tsv/PS3_GAMES.tsv)
- Download [PS3 DLCs TSV](https://nopaystation.com/tsv/PS3_DLCS.tsv)

## NPS Browser

- Launch it & Configure it with the following steps
- `Games > PS3 tsv` and locate PS3_GAMES.tsv
- `DLCs > PS3 tsv` and locate PS3_DLCS.tsv
- `Download and unpack dir` and locate the directory where you want files to download to
- `Any pkg dec tool` and locate pkg2zip (the executable)
- Hit close [x]

Download the following files with your newly configured program
- game: `NPUB31154`
- dlc: `BLUS31156` (Optional, but recommended Collector's Edition extras)

## Install the Game

Start RPCS3 and click `Files > Install Packages/Raps/Edats`
- Install game .pkg
- Install game .rap
- Install dlc .pkg
- Install dlc .rap

## Patch It

Download [rusty-psn](https://github.com/RainbowCookie32/rusty-psn)

- Launch it
- Look up updates with the game's serial number `NPUB31154`
- Download all of the update(s) ([GTA:1.27](https://gtao.me/) is ONLY supported for `1.27`, **you need to download all previous patches**)
- Select the downloaded [RPCS3 Patch](https://gtao.me/imported_patch.yml) in File Explorer and drag it into RPCS3 > patches, make sure to enable it on your game.
- Your game version should be `1.27` now and have the required patches enabled!

## Custom Config (Credit to [@DakrFH](https://www.youtube.com/@DakrFH))

Create custom config for GTA 5 (right click on the game) with the following settings. This is not mandatory, but it improves performance and stability. 
- `GPU > Additional Settings > Write Color Buffers: On`
- `Network > Network Configuration > Network Status: Connected`
- `Network > Network Configuration > Enable UPNP: On`
- `Network > PSN Configuration > PSN Status: RPCN`
- `Advanced > Core > Accurate RSX reservation access: On`
- `Advanced > GPU > Write Depth Buffers: On`
- `Advanced > RSX FIFO Accuracy: Atomic`

##  RPCN Setup

These steps are required to be able to play with others

- `Conifguration > RPCN > Account > Create Account` (do what it says)
- Once done click Test Account it should say: `Your account is valid!`
- If invalid repeat from step 1 again

## Enjoy

Start the game, complete `Prologue` and `Franklin and Lamar` and you should be able to play online.

## Cheating

[Moved Here](cheating.md)

## Troubleshooting

**Timed out when matchmaking for a compatible GTA Online session to join** - This just happens sometimes. Keep trying or start an Invite Only session and then select Find New Session after loading in.

**I keep getting put into empty sessions** - This can be caused by many things. Sometimes nobody is online, but if you know for sure there are other people online make sure you have the correct game version. If your game version is correct try to enable UPnP on your router. Sometimes Windows likes to ruin your networking for no reason. Navigate to `Gaming > Xbox Networking`, wait for everything to finish loading and click the `Fix it` button. After it is done fixing click `Check again`.

**The patch got separate entry in RPCS3 instead of bumping GTA V's version** - You most likely got a patch for a different version of GTA V. Make sure your game's serial matches your patch's serial. You can get the correct serial for your game by right clicking on your game in RPCS3 `Copy Info > Copy Serial`.

## Credits
- [@Tervel1337](https://twitter.com/Tervel1337) for discovering this whole rabbit-hole
- [@DakrFH](https://www.youtube.com/@DakrFH) for the configs
