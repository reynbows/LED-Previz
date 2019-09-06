# WhiteVoidApplication

reyjarrell@gmail.com
@rey.nbows
reyjarrell.myportfolio.com

Greetings!

This system attempts to pre-visualize (previz) DMX control for a 32x32 RGB LED panel, using a sequence of rendered frames of geometry that itself is running in realtime.

Pulsing the "Record" parameter on the "Geo" component will begin capture of 900 frames (30 frames per second for 30 seconds) of the animated geometry, which will then be saved in the 'Playback' file. It will also automatically disable the Realtime flag to ensure each frame captured is fully rendered, but never fear! The Realtime flag will be re-engaged once the recording is finished.

Once you've saved your 900 images, a the TOP in the "Geo" component, "Recorded_File" will automatically begin to replay your stored frames over a previz of a 32*32 LED panel.

On the "Panel" component, you have the option of viewing either the file you've already recorded (by selecting "Recorded_File" from the menu), or the live geometry itself (by selecting "Live_Geo" from the same menu).

The idea behind this is that, while we want our Geo to look SUPER COOL in the render, we also need to keep in mind that its ultimate destination is a 32x32 LED panel, which looks SUPER COOL under different circumstances than our render. For this reason, we want the option of previzualising the geometry on the panel before we actually make the recording.

Enjoy exploring! Feel free to reach out with any questions/comments/additions/improvments!

All the very best,
Rey 

