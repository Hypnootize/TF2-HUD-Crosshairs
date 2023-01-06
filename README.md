# TF2 Hud Crosshairs

![Screenshot](https://raw.githubusercontent.com/Hypnootize/TF2-Hud-Crosshairs/master/crosshairs/TF2Crosshairs.png)

This hud crosshairs pack aims to unify all the known crosshairs from different sources and creators into one single font file for practicality and hud optimization purposes!

Huds are known for slowing down the game load times when a lot of font definitions are added to them, in order to prevent any lag I unified all the crosshairs in a single font file to reduce the ammount of font definitions needed to run the crosshairs as well as making it possible to enable and disable some of the less common font schemes featuring properties like blur and dropshadows by simply commenting/uncommenting them.

# Installation

1) Download and extract the crosshair pack

2) Copy the crosshairs folder and paste it inside the hud's resource folder

3) Add the following paths to the ClientScheme, HudLayout and Animations_Manifest to make the crosshair files work

   - **Resource/ClientScheme.res**
       - #base "../resource/crosshairs/crosshair_scheme.res"


   - **Scripts/HudLayout.res**
       - #base "../resource/Crosshairs/crosshair.res"


   - **Scripts/HudAnimations_Manifest.txt**
       - "file" "resource/Crosshairs/crosshair_animation.txt"


### Notes
For `HudAnimations_Manifest.txt`, you want to paste the mentioned line right after the `"file" "scripts/hudanimations.txt"` line, also a pre-existent `event DamagedPlayer` in your HUD animations could interfere with this.

## Credits
- **Fog** for [Fog Crosshair](https://www.teamfortress.tv/14702/release-fogs-crosshairs-v3)
- **Pete** for [KnucklesCrosses](https://www.teamfortress.tv/26790/official-knucklescrosses-release)
- **Broesel** for [BroeselHUD Crosshairs](https://sourceforge.net/projects/broeselhud)
- **Whayay** for [Yahud Crosshairs](https://github.com/whayay/yahud)
- **Griever** for [ToonHud Crosshairs](https://toonhud.com/)
- **Seeker** for Seekers Crosshair
- **Garm3n** for wings Crosshairs

## Special Thanks
- [**Whisker**](https://github.com/rbjaxter)
- [**omnibombulator**](https://github.com/omnibombulator)
- [**JarateKing**](https://github.com/JarateKing)