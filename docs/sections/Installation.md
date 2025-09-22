# Intalling Virtual DJ

To install Virtual DJ, go to https://virtualdj.com/, click on download, choose your system type, and follow the installation instructions.

Virtual DJ is a powerful software used by millions of amateur and professional DJs around the world. Furthermore, it is **free to download and use!**.

The license stipulates that you buy a license (currently $299) if you are using it regularly for paid performances. They have put a lot of time and effort into making a great product, so once you start using it to headline your big festivals and marathons make sure to purchase a license. But in the meantime you can try it out at home and at your local milonga for free.

## Loading the TigerTango Skin

While Virtual DJ is a powerful tool, it is primarily designed for club DJs to mix tracks together. This means there are a lot of buttons and settings that are not useful for tango DJing...unless of course you want to add some cool scratches and beat breaks into that Biagi tanda ;-) There are capabilities that are not in the default Virtual DJ layouts that are very useful for tango DJs.

This is where TigerTango comes in. It provides an interface that has removed what is not needed and added features that are useful for DJing tango.

The simplest way to download TigerTango is directly from Virtual DJ. If you want the latest version with any new features, you can also install the version from Github https://github.com/sericson0/TigerTango

### Loading TigerTango from VirtualDJ

1. Open VirtualDJ and select settings (the gear icon in the upper right)
2.  Select the Interface tab (looks like a computer monitor)
3.  Select *Get More*
4.  Type *TigerTango* in the search box
5.  Click *Install*
6.  Return to the interface button
7.  Select the TigerTango Skin (should now appear as an option)

You should be all set! (See screen shots for step by step)
![alt text](<../images/Selecting Skin.png>)

![alt text](<../images/Clicking Install.png>)

![alt text](../images/LoadingTheSkin.png)
### Loading from GitHub

To load the development version:
1. Go to https://github.com/sericson0/TigerTango (If you are reading these instructions online you have already completed this step! You will just need to scroll to the top of the page to clide Code for step 2).
2. Click Code (see image below)
3. Click Download ZIP (see image below)
4. Open the downloaded zipfile (TigerTango-main.zip)
5. Open the zipfile and the TigerTango-main folder (There should be a TigerTango folder inside). I.e., you need the folder labeled TigerTango that has a .xml file and several images inside.
> [!NOTE]
> You can get the path to the virtual DJ skins by going to settings in Virtual DJ, moving to the interface tab, and clicing 'Edit This Skin' in the bottom right. **Go one up from this folder!!! This is where you want to place the TigerTango folder you downloaded.**
6. Move this folder into where VirtualDJ saves skins (See note above). On Windows this is likely C:\Users\<USERNAME>\AppData\Local\VirtualDJ\Skins.

![alt text](<../images/Installing Development Branch.png>)

Once you have installed the TigerTango interface, you can open it as follows:
1. Click settings (gear image in upper right).
2. Click **Interface** in left tab (see image below)
3. Select the TigerTango skin (you may have to scroll down)
4. You can now close the settings interface and should have TigerTango loaded!

## OPTIONAL Load the TigerTangoVideo Video Skin.
Some DJs like to Display song information while DJing. However, the default video skin is not ideally suited for displaying what we would want as tango DJs. Therefore we have added the TigerTangoVideo video skin to this repository as well. You can read more about connecting to the Video Skin in the [Video Skin Section](VideoDisplay.md).

You can load the TigerTango Video skin using the following steps.
1. Follow the steps in Loading from GitHub (section above) to download and unzip the TigerTango-main.zip file.
> [!NOTE]
> You can get the path to the virtual DJ video skins by going to settings in Virtual DJ, moving to the interface tab (on left), change to Video Overlay tab (on top) and clicing 'Edit This Skin' in the bottom right. **Go one up from this folder!!! This is where you want to place the TigerTangoVideo folder you downloaded.**
2. You need to move the **TigerTangoVideo** folder to where Virtual DJ saves video skins. In Windows this is C:\Users\<USERNAME>\AppData\Local\VirtualDJ\VideoSkins

3. Open Settings -> Interface (tab on left side) -> Video Overlay (tab on right side) -> Select *TigerTangoVideo (edit)*
4. You can now close settings.

When you display video it should now use the TigerTangoVideo interface.

## OPTIONAL Install Plugins.

Tango DJs and Club DJs are opposites: *Club DJs play high quality recordings of low quality music while tango DJs play low quality recordings of high quality music* ;-) Jokes aside, what club DJs do is mix and modify parts of songs to enhance the energy and flow in the room . When tango DJs modify a song, it is primarily to remove artifacts such as hiss, or enhance the sound quality of the recording such as by boosting or reducing certain frequencies. 

TigerTango has a semiparametric EQ built into the skin to help with sound quality. However, plugins can offer powerful ways to help provide the best sound quality. There are a number of possible plugins that Tango DJs may find useful:
* Parametric equalizer for removing hiss and clarifying sound
* Limiter 
* Tape or saturation plugin for some songs
* Audio visualizers (more useful for understanding music than active DJing)

The following steps walk through an example of how to install *TDR NOVA*, a powerful and free parametric EQ by Tokyo Dawn Records.

1) Go to https://www.tokyodawn.net/tdr-nova/ and select the correct installer for your computer
2) Run the installer on your computer. 
> [!NOTE]
> Take a note of the folder path where the installer saves the **VST3** file to.
1) Accept the license agreement and click through next on each popup.
2) Open Virtual DJ options, search **vstFxFolder**, and set to where your VST3 files save to. On Windows this is "C:\Program Files\Common Files\VST3"
3) Close and restart Virtual DJ

### Other Plugins you May be Interested In
* Tokyo Dawn has some additional nice free and paid plugins. 
    * TDR Prism is a nice spectrum analyzer for visualizing music 
    * TDR Limiter 6 GE has a limiter.

* https://analogobsession.com/ hvas a number of free analog emulations that you may find worth checking out
* Voxengo has a free 16 band graphic equalizer https://www.voxengo.com/product/marvelgeq/
* Toneboosters has a free audio spectrogram for those interested in visualizing the music https://www.toneboosters.com/tb_spectrogram_v1.html
* Loudmax https://loudmax.blogspot.com/ is a simple free limiter

> [!NOTE]
> You can also connect any VST3 plugin into Virtual DJ. This can be useful if you use something like an Apollo interface and want to have their plugins available in your DJ interface. 


## Next Section ➡️ [Getting Started](docs/sections/GettingStarted.md)
