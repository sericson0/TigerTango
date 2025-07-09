# Setting up VirtualDJ and TigerTango for Tango DJing
By: Sean Ericson (Sericson0@gmail.com)


A good Tango DJ can enables dancers to find that magical flow and connection we all crave. The art of picking the perfect tandas requires untold hours of study and practice. And nothing kills the magic you are working so hard to create like technical issues. Your DJ software should enable your creativity and not be a hindrance to the flow you are striving so hard to create. This is why I created the TigerTango skin for Virtual DJ. It provides a layout custom suited for the needs of and requirements of tango DJs and other social dances.

This guide discusses how to to get set for DJing tango music with virtual DJ. It walks through the following:
* Installing Virtual DJ
* Loading the TigerTango Skin
* Installing third party plugins such as EQs
* Description of the layout and use of TigerTango

You can find a video tutorial of TigerTango here https://youtu.be/k9lrT9ofaWw

!!!CHECK TigerTango is currently in its first version. I have tried my best to make it a tool that will be valuable to Tango DJs and DJs of other social dances, but the only way to know what will be most useful is to have people try it and give feedback. If you run into any issues, or if there were any functionality you wish were updated or added, please reach out to me at sericson0@gmail.com. You can also post an issue on https://github.com/sericson0/TigerTango/issues

 I would love to hear from you!
## Intalling Virtual DJ

To install Virtual DJ, go to https://virtualdj.com/, click on download, choose your system type, and follow the installation instructions.

Virtual DJ is a powerful software used by millions of amateur and professional DJs around the world. Furthermore, it is **free to download and use!**.

The license stipulates that you buy a license (currently $299) if you are using it regularly for paid performances. They have put a lot of time and effort into making a great product, so once you start using it to headline your big festivals and marathons make sure to purchase a license. But in the meantime you can try it out at home and at your local milonga for free.

## Loading the TigerTango Skin

While Virtual DJ is a powerful tool, it is primarily designed for club DJs to mix tracks together. This means there are a lot of buttons and settings that are not useful for tango DJing...unless of course you want to add some cool scratches and beat breaks into that Biagi tanda ;-) There are capabilities that are not in the default Virtual DJ layouts that are very useful for tango DJs.

This is where TigerTango comes in. It provides an interface that has removed what is not needed and added features that are useful for DJing tango.

You can load a stable version directly from Virtual DJ, or can install the development version from Github https://github.com/sericson0/TigerTango
* Loading from Virtual DJ is simpler but may not have the latest updates (It takes a while to get updates through their review process)
* Loading the development version from GitHub allows for the latest features and updates.

### Loading TigerTango from VirtualDJ
1. Open VirtualDJ and select settings (the gear icon in the upper right)
2.  Select the Interface tab (looks like a computer monitor)
3.  Select *Get More*
4.  Type *TigerTango* in the search box
5.  Click *Install*
6.  Return to the interface button
7.  Select the TigerTango Skin (should now appear as an option)

You should be all set! (See screen shots for step by step)

![alt text](<docs/Selecting Skin.png>)
![alt text](<docs/Clicking Install.png>)
![alt text](docs/LoadingTheSkin.png)

### Loading the Development Version of TigerTango

To load the development version:
1. Go to https://github.com/sericson0/TigerTango
2. Click Code (see image below)
3. Click Download ZIP (see image below)
4. Open the downloaded zipfile (TigerTango-main.zip)
5. Open the zipfile and the TigerTango-main folder (There should be a TigerTango folder inside)
6. Move this folder into where VirtualDJ saves skins. On Windows this is likely C:\Users\<USERNAME>\AppData\Local\VirtualDJ\Skins.

![alt text](<docs/Installing Development Branch-1.png>)

## Installing Plugins

Tango DJs and Club DJs are opposites: *Club DJs play high quality recordings of low quality music while tango DJs play low quality recordings of high quality music* ;-) Jokes aside, what club DJs do is mix and modify parts of songs to enhance the energy and flow in the room, whereas when tango DJs modify a song it is primarily to remove artifacts such as hiss or add lost frequencies such as bass frequencies to bring out to enhance the sound quality of the recording. This is why different tools are required.

Enhancing the sound quality of older recordings can be done with EQing. While there is a 3-band EQ built into the TigerTango skin, more advanced EQ plugins can be installed.

Here I show how to install *TDR NOVA*, a powerful and free parametric EQ by Tokyo Dawn Records.

1) Go to https://www.tokyodawn.net/tdr-nova/ and select the correct installer for your computer
2) Run the installer on your computer (If on Windows, you need to open the downloaded zip file)
3) Accept the license agreement and click through next on each popup.
4) Close and restart Virtual DJ

* Tokyo Dawn has some additional nice free and paid plugins. * https://analogobsession.com/ also has a number of free analog emulations that are worth checking out
* Voxengo has a free 16 band graphic equalizer https://www.voxengo.com/product/marvelgeq/
* You can also connect any VST3 plugin into Virtual DJ.

## Using TigerTango

This section decribes how to set up your workflow for Tango DJing. The Virtual DJ user manual here https://virtualdj.com/files/VirtualDJ_User_Manual.pdf has additional useful information.

### Configuring Audio
For Virtual DJ to work correctly, you need to configure your audio to play how you want it.

1. Click on settings
2. Select the Audio tab (looks like a speaker)
3. Select Speaker only or Speaker + Headphones. Setting speaker + headphones gives you the ability to use headphones for prelistening.

1. Select where you want your speakers and headphones to play from.
   1. When in doubt, select chanel 1 & 2 for your *master* out.
   2. If you want to send your sound through an interface such as an Apollo, where you apply additional plugins, then you might select Virtual 1 and 2.
   3. Make sure to send headphones to a different output than the master speakers.
2. Select Apply to accept the configured changes.

![alt text](<docs/Setting up audio.png>)

### Layout

![alt text](<docs/TangoTiger Breakdown.png>)

TangoTiger is separated into 6 main components.
1. **Browser** Set up playlists and can search for songs in your library.
2. **Staging Area** Prepare your tandas.
   Note: The staging area is an always viewable automix panel, which allows you to use the side view in the File explorer panel to pull up playlists. This is one of the additions of TigerTango to help with tango DJing.
3. **Decks 1 and 2** Where songs will play from. TigerTango is set up to switch between decks when in auto mode.
4. **Master** Includes master effects (plugins) and your master fader. Also includes information on headphone volume and mic volume (when one is plugged in).
5. **Info** Access settings and information such as time, master VU metering, and battery life.
6. **Panels** Opens movable windows of parts of the browser window.

#### Browser
You can find detailed documentation on the browser section in the virtual DJ user manual [here](https://virtualdj.com/manuals/virtualdj/interface/browser.html) (https://virtualdj.com/manuals/virtualdj/interface/browser.html)

Main notes are:
* You can access your music files in the left panel
* You can Build subfolders and playlists to organize your music
* You can search for songs in the File list panel (second from the left)
* You can add folder shortcuts and build playlists in the sideview planel (middle right)
* You can access and update song information, including editing and adding tags and metadata, in the File Info panel on the right.

### Staging Area
The staging area is an always-available automix panel. Here you can build your tandas and cortinas.

You can read more about how automix works [here](https://virtualdj.com/manuals/virtualdj/interface/browser/sideview/automix.html)

You can also read about importing playlists into Virtual DJ, such as from ITunes or traktor [here](https://virtualdj.com/manuals/virtualdj/interface/database/playlists/index.html)

### Decks

![alt text](<docs/Deck Breakdown.png>)

TigerTango uses two decks so you can prepare the next **track** while one is playing. Each deck has the same sections, with the following properties:

1. **Track Info** Gives information such as track name, key, and time remaining in song. You can skip ahead or back by moving the line on the waveform.
2. **Effects** You can add effects such as EQing to a deck here.
   1. The dropdown allows you to select the effect.
   2. Clicking on the plus button opens up the effect graphical interface.
   3. Click the effect button not on the dropdown chevron to toggle the effect. The effect button will light up when active.
3. **Dropzone** Add a track to the deck by dragging and dropping it here. The turntable will spin when a deck is playing. TangoTiger should automatically change settings to turn off scratching, but this is something you may want to test before playing to the public :-)
4. **EQ and Pitch** You can adjust the Low, Mid, and High of a track along with adjusting the playback pitch by moving the sliders here.
5. Adjust the deck volume here. If a deck is playing but no sound is coming out, it may be because the deck volumne is down.
6. The prelisten button allows you to listen to a song ahead of time in headphones. It implements the following logic:
   1. when turned on it first checks to make sure the deck is not playing to the main speakers. Then it turns the volume of the deck off, sets to play through headphones, and starts the track.
   2. When durned on it resets volume to 100% and resets track to starting.

!!! If you want the deck volumne other than full, then remenmber to change it after toggling off prelisten.
7. **Controls** TigerTango has implemented four playback controls:
   1. **Play/Pause** Starts or stops the current track.
   2. **Fade** Fades out current track. At end of fade it resets the deck volume to 100%.

!!!NOTE if you want the deck volumne other than full, then remenmber to change it after the fade completes.
   3. **AUTO** Toggles on or off automix. The automix will start with whichever deck you select auto on.
   4. **AutoFade** Fades out deck, starts song on other deck, and loads next song in playlist onto current deck. If you have a cortina that you want to fade out and then start the next tanda, you can do this with AutoFade.

### Master

The Master section Has four components:
1. **Master Effects** This is where you can add plugins such as compressors, limiters, saturation, or EQ. TigerTango has four master effects slots.
   1. Click the dropdown to select the effect
   2. Press the plus to toggle the effect's graphic interface
   3. Click the effects button to toggle on or off the effect (when on the effect button will change color)
2. **Master Video** Here you can add video effects such as projecting the song album art or title to an external monitor
3. **Master Volume** This fader changes the sound going to the speakers.
4. **Headphone Volume** When audio is set up for both speakers and headphones, then you can change the headphone volume here. The Mix slider determines what percent of the main mix comes through headphones. If you want to just head the headphone song, then turn mix volume to zero.
5. **Mic Volumne** If you have a mic connected to your interface, then you can selet the mic volume here.

### Info Section
The Info section presents the following:

1. A VU meter for the master fader along with a clipping indicator. **!!!IF THE CLIPPING INDICATOR IS LIGHTING UP, TURN DOWN THE MASTER FADER!!!**
2. A CPU usage indicator. **If the CPU is high, then make sure to turn off other programs or reduce the number of plugins used**
3. Battery level if the computer is not plugged into a power source. **If you see a battery symbol, this means your computer is not plugged in**
4. Current time
5. Settings menu (gear icon)

### Panels
The following panels are options
* **BROWSER** Opens a movable and expandable browser panel. Most useful for prework if you want to use multiple monitors.
* **SEARCH** Opens an expandable search panel. Best suited for prework
* **SIDEVIEW** Opens an expandable sideview panel
* **STAGE** Opens an expandable automix panel for staging songs. Can be helpful if you have a large playlist. Currently you cannot add songs from the movable staging panel but you move from the staging panel to a track.
* **SIDELIST** Opens an expandable sidelist panel. Can be useful if you have preset possible tandas that you would like to pull from
* **INFO** Opens and expandable info panel. Useful for metadata work.

## Example Workflow
This section walks through how you could use TigerTango for DJing.

### Prework
* You can create subfolders, such as most liked songs by artist, period, and singer in the browser panel
* You can attach shortcuts to folders and playlists which can be seen in the side view. For example, you could have shortcuts to cortinas, vals tandas, milonga tandas, modern orchestras, and alternative tandas
* You can use the sidelist to start planning tandas and potential flow

#### During the night
* Drag your first tandas into the staging area and click AUTO to begin playing. This will loop through the playlist one song at a time.

> [!WARNING]
> Make sure your Automix Type is set to "None (back-to-back)". If you want Automix to remove songs from the list once played then toggle "Auto remove played".

* Use the **Prelisten** button on the non-active deck to listen to the up upcoming song.
* Use the deck effect and master effects areas. to do any needed EQing or addition of other effects.
* You can preset effects and then toggle them on or off as needed.
* The **AUTO FADE** button can be used to fade out a cortina and allow the automix to continue as desired.
* For performances, Turn off the Automix and load one deck at a time into the player. This will ensure that the next sond does not start playing before the performers are ready.
*  Once performances are over you can restart **AUTO** to continue the night

> [!WARNING]
>  The automix can be finicky at times in VirtualDJ. Make sure to click Auto on the track that you want to play from.

!!!NOTE check the song on the other deck to make sure the song you want to play next is lined up

!!!CHECK When adding the next song in automix, it tends to work best to add to the next in line in the staging area instead of directly to the deck.


## Providing Feedback
Please consider this version of TigerTango as an initial stable release. I have tried my best to make it a tool that is useful and valuable to Tango DJs and other social dances, but I am sure there are additional steps to make it more useful and robust.

If you run into any issues, or have any thoughts, suggestions, or requests for improvements, I would love to hear from you. I would also love to hear if you find this tool useful.

!!!CHECK You can reach me at sericson0@gmail.com or can post to the Virtual DJ forum https://virtualdj.com/forums/264357/addons/TigerTango.html