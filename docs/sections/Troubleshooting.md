# Troubleshooting
Here are a few common issues along with troubleshooting steps

## No Audio is coming out?
1. If the deck wont move when you press play, then it is very lidekly that the audio is not configured correctly. Go into Settings -> Audio. Make sure that there are no errors by the master output. Try changing the channels to 1 & 2.
2. Look at the VU meter next to the master fader (in MASTER VOL area). If it is not moving then it likely means one or more of the following:
   1. Deck is not playing (check that the turntable is moving)
   2. deck volume is off (check deck volume slider)
   3. Master fader is off (check master fader in MASTER VOL area)
3. If the VU meter is moving but no sound is coming out, then it is likely one the following.
   1. Your computer is muted or at low volume. Check your computer volume. Suggested volume for good gain staging is somewhere around 80%.
   2. Something downstream of your computer is not turned on and configured properly. Check that your DAC, Mixer, and speaker are all turned on and plugged in.

## Headphone Prelisting is not working?
1. First check your audio settings that your system is configured to both main and headphones.
2. Check that the headphone output is properly routed to your headphones.
3. Next check that the PFL (prefade listen) is turned on for the deck you are listening to. This is the light below the headphones icon. If it is not turned on then press the button. Clicking the preklisten button (headphone icon) should also automatically turn on PFL.
4. Check that your headphones are plugged in.

## Using Automix
When using automix, there are two main recommendations to avoid issues.
1. **Don't reach the end of your automix.** Automix tends to work best when it knows what song is coming next.
2. **Add tracks to the playlist, not directly to the deck.** Automix may not always no where to play next if it plays a track from the deck which is not added to the automix. This can lead to unexpected behavior. It is recommended to add songs to the playlist and let automix load them to the deck.

## Skin Flickering
If you happen to notice the skin flickering then you will want to change the following setting
* Settings -> Options -> experimentalSkinEngine -> Off
The **experiementalSkinEngine** setting can reduce computer CPU usage but can coause flickering on some computers.

## Skin is Lagging
If the skin seems to be lagging, then try 

1. setting **skinUseLowPowerGPU** to **High Power**.
2. Close out other windows and programs
3. Check CPU and memory usage. Programs such as dropbox can have high memory use.  
