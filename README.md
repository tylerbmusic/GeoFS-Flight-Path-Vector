Installation process:  
Step 1: Copy the contents of 'userscript.js' into your clipboard  
Step 2: If you haven't already, download tapermonkey (https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo//Open)  
Step 3: Press the Extensions icon on the toolbar at the top of your browser and click on the icon that looks like a rounded square with two eyes at the bottom, and press "Dashboard"  
Step 4: Press the little "+" tab, and paste your clipboard contents into the big text box, and click "install".  
Step 5: Open GeoFS, and it should work!  
  
If you _want_ to make your life _harder_, instead of following the installation process, bookmark the userscript.js file and each time you refresh or visit GeoFS, open the bookmark, copy the code, go to the GeoFS tab, press f12, Ctrl+Shift+I, or Cmd+Shift+I, and paste the code into the console.  


Note: Pressing 'l' will hide the FPV.
Another note: The FPV is calculated based on the camera's position. This means that the FPV shows where the camera would hit the ground if it were to keep going in the same direction, and not the aircraft.
Also note: the glideslope indication on the bottom right only works if you are tuned into an ILS, and depending on the length of the runway, it can be a bit inaccurate. (It's still much more accurate than the default glideslope deviation indicator).
Finally note: the FPV is a point in 3D space, and is updated about once every frame. However, since it can't update every frame reliably, it needs to be farther away from the camera. This can lead to flickering behind and in front of objects. In addition, the FPV will stop working when the aircraft is on the ground.

If you are experiencing any issues, or have any suggestions, put them in the Issues tab of this page (you can find it near the top, right next to <> Code). I will probably respond within 24 hours, but I make no promises.
