## Installation

* [Handbrake](http://www.videohelp.com/tools/HandBrake): Extract user_presets.xml into the Handbrake install/config directory
 * Windows 7/8?/10?: Win+R (Start > Run) > %userprofile%\AppData\Roaming\HandBrake or copy and paste this into the explorer address bar; C:\Users\%username%\AppData\Roaming\HandBrake
 * Windows Vista: Win+R (Start > Run) > %userprofile%\AppData\HandBrake or copy and paste this into the explorer address bar; C:\Users\%username%\AppData\HandBrake
* [MeGUI](http://www.videohelp.com/tools/MeGUI): Extract the profiles to ...MeGUI > allprofiles > x264
* [Tx264](http://www.videohelp.com/tools/TX264): Extract the PreDefs folder into the folder containing Tx264.exe (If you want to update x264 download the latest 8bit/10bit version from [here](http://download.videolan.org/pub/videolan/x264/binaries/) and extract x264.exe into ...tx264 > tools > x264. If you want to update FFMPEG download the latest version from [here](http://ffmpeg.zeranoe.com/builds/) and extract ffmpeg.exe into ...tx264 > tools > ffmpeg)
* StaxRip/x264vfw/etc: Select a profile from the Profiles.txt file, then copy and paste it into the 'command line'

## Notes

* MeGUI/Tx264: Some profiles have been separated into folders, If you want to use these profiles extract them from the folders first
* Handbrake: If you have your own presets and want to keep them; Extract user_preset.xml to your desktop and open it in notepad, copy all the text except the first two lines ( , ? XML ... and < ArrayOf ... ) and close notepad, then go to the Handbrake install/config directory and open user_preset.xml in notepad, go to the end, delete the last line ( < / ArrayOfPreset > ), paste the text you copied from the first user_preset.xml and save it (Ctrl+S). 
