# Overlays for Retropie 4.x - Retroarch/Libretro 
Arcade game overlays created for Lr-Mame2003 (latest version with correct aspect ratio) and 1280x1024 Display.

Note: These overlays are optimized for use with integer-scaled vertical games - [See this thread for details](https://retropie.org.uk/forum/topic/4046/crt-pi-shader-users-reduce-scaling-artifacts-with-these-configs-in-lr-mame2003-lr-fbalpha-lr-nestopia-and-more-to-come).  If you run into problems with overlays obscuring the edges of the game display, please [go here](https://github.com/dankcushions/crt-pi-configs), download the latest version of the script, and follow the instructions to generate new custom game-specific configuration files.

Original logos, artwork, graphics and trademarks are property of their respective owners. 

## How to install (recommended)

Using meleu's [`rpie-art.sh` script](https://github.com/meleu/rpie-art):

```
cd
git clone --depth 1 https://github.com/meleu/rpie-art
cd rpie-art
./rpie-art.sh
```

After launching `rpie-art.sh` you just have to follow the instructions in the dialog boxes.


## How to install manually

Each overlay folder contains specific instruction; generally setup OVERLAY in this way:

The `.cfg` files assume retroarch overlay folder is: `/opt/retropie/emulators/retroarch/overlays/arcade-bezels/`

If using a different folder, edit `.cfg` files accordingly.

If folder does not exist on your RetroPie, create `arcade-bezels` folder with the mentioned path.

Summarizing the steps:
- ssh or ftp into Pi
- copy romname.zip.cfg into your `mame-libretro` (lr-mame2003) ROMS folder
- copy png file and `romname.cfg` into overlay folder

Have fun !
