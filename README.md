This has been archived - it is now part of the
[Tin Whistle Tablature](tin-whistle-tablature) project.

# musescore-low-whistle
This repo provides an extra instrument file for adding Low Whistle types to Musescore.

The Low Whistle, which is a metal 6 hole Flageolet, is larger than the more well-known tin
whistle and has a lower pitch. The low whistle is commonly available in three tunings:
* "D Low Whistle" tuned to D4, also used for keys Em and G
* "F Low Whistle" tuned to F4, also used for Gm and B♭
* "G Low Whistle" tuned to G4, also used for Am and C

## Install
The file `low-whistle.xml` needs to be installed as an instrument extension using the MuseScore
menu. Use the same file for both MuseScore version 2.x and MuseScore version 3.x :

### MuseScore 2.x
1. copy file `low-whistle.xml` to `Documents/MuseScore2/Extensions/low-whistle.xml`
2. within Musescore menu, navigate to `MuseScore` then `Preferences...` then `Score` tab
3. in the Default Files panel, add the file to 'Instrument List 2' extension by:
4. browsing to `Documents/MuseScore2/Extensions/low-whistle.xml` and add to 'Instrument List 2'

### MuseScore 3.x
1. copy file `low-whistle.xml` to `Documents/MuseScore3/Extensions/low-whistle.xml`
2. within Musescore menu, navigate to `MuseScore` then `Preferences...` then `Score` tab
3. in the Default Files panel, add the file to 'Instrument List 2' extension by:
4. browsing to `Documents/MuseScore3/Extensions/low-whistle.xml` and add to 'Instrument List 2'

You may now add a low whistle staff using MuseScore menu item `Edit` then `Instruments...`, 
where MuseScore lists the low whistles instruments under 'World Music' 'Woodwinds'.

Once a low whistle staff is added to the score there is no need to keep this instrument
file in the 'Instrument List 2' extension.

The score `low_whistle_range_test.mscz` is an example score showing all three whistle staves.
