A Hat Brim Designed to fit V0.2 using V0.1 Top Hat, R-pi Camera and Adafruit Neopixel  

If you don't love the brutalist asthetic or acquisition challenges of the T-slot extrusion top hat that goes with V0.2, I set out with a couple goals. First to adapt the V0.1 Top Hat which feels more aligned with the Voron Design mission and asthetic, and to bring in a cost effective lighting and camera support solution to the V0 family.    
  

![V0 2 TOP HAT ADAPTER](https://user-images.githubusercontent.com/31577989/224580250-63d08338-e02c-4e56-9af7-112308c472f9.JPG)
![PXL_20230313_020947419](https://user-images.githubusercontent.com/31577989/224592383-39dfa19e-88da-4e6e-84b2-5ff147b145c1.jpg)
![PXL_20230313_152843230](https://user-images.githubusercontent.com/31577989/224749343-f5ba98da-c8aa-4b79-bd83-ac9af2667891.jpg)




Step 1: Print Your Parts.  

Notes:  
  + The lights and camera parts are in green in the BOM. All else are optional.  
  + Parts are designed for printing on a V0.  
  + I'm not afraid of using support. I used it to make some better parts in a couple cases.   
  ++They are used on the Front Logo to prevent curling.  
  ++They are used on the Camera Back so that 3 parts can be combined into 1.  
  + Front Logo, you need two, I made a varient for holding the ribbon cable of an Rpi Camera.
  + The color of the camera pad is optional, my reccomendation is match the color of the mounting surface.
  + The STLS should be ready to go but if you are one to tinker.  
  ++  More hexes are low.  
  ++  Support goes down  
  ++  Words are right side up  
  ++  Camera mounts high  
  


       
    

![Print Orientation](https://user-images.githubusercontent.com/31577989/224581959-1ec1201a-59e8-43a5-8621-93710022df84.JPG)

  
  Step 2: Ready your parts  
    
  At a minimum, the Front Logo should be tidied and lightly sanded to remove any excess support material.  
  Sand the back of the logo along the yellow edges. The parts should slip easily inside each other.  
  Install Heat Inserts on the corners and sides. On the corner pieces get x2 and the Side Panel 1 gets x1  
   
  ![InkedPXL_20230313_000504970 MP](https://user-images.githubusercontent.com/31577989/224583871-f3a978ce-3f40-4d1c-af14-98718496dc3c.jpg)

    
  
![Heat Set Insert Sides](https://user-images.githubusercontent.com/31577989/224583727-c10b0482-0217-4656-926b-c8e7452da013.JPG)

  
![Heat Set Insert Corner](https://user-images.githubusercontent.com/31577989/224583601-d69f53cf-17a7-4794-b07a-d63792f81797.JPG)


  
  Step 3: Assemble Brim  
    
  Connect the brim using M3 x 20 SHSCS fasteners and M3 Nuts  
  
  
  ![Bolting](https://user-images.githubusercontent.com/31577989/224584118-b3d7039d-36dd-4d33-b6a7-b9c161e862fa.JPG)
  
  Attach Hinges: Reference the V0.2 Manual for mounting the hinge pieces.  
  
  
  ![Using Existing](https://user-images.githubusercontent.com/31577989/224584331-b5d00781-4d82-4dbb-83ba-b8590ec9755a.JPG)

  Step 4: Install Camera and Lights  
  At this point in time the camera can be assembled and installed with the NEOPIXEL LED strip.  
  Reference Raspberrypi.org or raspberrypi.com for instructions on connecting the camera to your raspberry pi. I purchases a set of ribbon cables and selected the 50cm as a just right length. 
  Solder 3 or 4 wires to the Neopixel Strip and route with the camera ribbon to the rear. Reference your MCU controller's pinout for the neopixel connection. 
  
  ![Camera Mount](https://user-images.githubusercontent.com/31577989/224584793-53a5cbfa-87fb-4127-b63c-480597ef71fb.JPG)
  
  ![PXL_20230313_000551334](https://user-images.githubusercontent.com/31577989/224584823-c019401d-34a9-4220-8f10-b54b39486107.jpg)

![PXL_20230313_000544694](https://user-images.githubusercontent.com/31577989/224584878-b2475e07-2af2-4348-b805-7480f2bf5f81.jpg)

  
  Step 5: Install Top Hat to Brim per V0.1 Manual. This should be use the same hardware.  
  Step 6: Install Top Hat Assembly per V0.2 Manual.  
  Step 7: Include the file TopHat_leds.cfg in your print.cfg file. Reference Stealth Burner information on Voron Design.  
    
  This is blaitantly ripped off verion of the Stealth Burner configuration file. Those authors deserve all the credit for the heavy lifting. 
  My adaptations only was to address the 8 LEDS, thus you should use it as a starting point. I've left the hooks in place for those with a white pixel and a future second led set. I haven't tested every permutation of this Adafruit light bar.
  
  Final Thought on the Camera  
  
  As of publishing, Octoprint 1.0 is the current release on Bullseye and has spotty support for webcameras including the raspberry pi cam. Release candidates seem to be addressing this issue, but getting the raspbarry pi camera up and running took googling steps though it does works. After the next Octoprint release, I intend to link to supporting information.  
    
    
The mounting bracket for the camera can be mounted in either accessory point or any of the 4 the middle points on the V0.1 top hat.

