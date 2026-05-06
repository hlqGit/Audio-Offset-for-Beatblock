# Audio Offset for Beatblock

For some reason, the only method of offset for so long in beatblock as been input offset. While functional, high offset devices do not visually match up with the song. I wanted to fix that! By installing this mod, the taps and blocks will finally visually match up.

## Disclaimer - 

If you use this mod, chances are likely you will add positive offset delay, meaning the hitsounds will not line up with the actual song. This is not avoidable, and is a very common issue among many rhythm games.

Note: If you use negative offset, the hitsounds will still line up with the visuals.

> TLDR: You will likely have to turn off hitsounds to have the audio and visuals match up.

# How to Install
1. You will need to install [lovely injector](https://github.com/ethangreen-dev/lovely-injector/releases/tag/v0.9.0). Lovely injector will allow the code to be initialized when Beatblock starts.
2. Download the latest release of my mod and leave it as a .zip file.
3. Extract the download of lovely injector, inside should be a `version.dll` file. Open steam and right click on Beatblock and select `Manage > Browse local files`. Move `version.dll` into the directory (should contain `Beatblock.exe`).
4. Run Beatblock once. Note: You will see a command prompt pop up, that is normal. That is lovely injector working its magic.
5. Next navigate to where beatblock saves custom levels. For windows, it should be `%AppData%/beatblock`. In this directory, there should be a `Mods` folder (create one if not). 
6. Drag the zip folder of the audio-offset mod into the `Mods` directory, and then you are good to go! Close everything up and launch Beatblock.
   
# IMPORTANT! Settings and Customization
* For all adjustments, the setting `Audio Offset` will be added into Beatblock under the `Audio` submenu.
* `Settings > Audio > Audio Offset`
* This is a global offset.
* Quick tip for adjusting:
  * Positive offset usually helps with setups where the sound feels late (bluetooth), and negative helps when the sound feels ahead of the beat.