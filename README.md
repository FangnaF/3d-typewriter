# 3D Typewriter
Making a typewriter with an old 3D printer!

![the typewriter](/images/typewriter.jpg)

## Special Thanks
OctoPrint: https://github.com/foosel/OctoPrint

hf2gcode: https://github.com/Andy1978/hf2gcode

## Demo Video

[![YouTube Demo Video](https://img.youtube.com/vi/keQaxa_vFdI/0.jpg)](https://www.youtube.com/watch?v=keQaxa_vFdI)

## Quick Guide
1. Setup 3D printer, Raspberry Pi and OctoPrint (https://github.com/foosel/OctoPrint). 
    * Enable CORS from the API setting page in OctoPrint
    * Connect a keyboard to Raspberry Pi
    * SSH to Raspberry Pi from a computer

2. Setup hf2gcode (https://github.com/Andy1978/hf2gcode) in the same Raspberry Pi
    * Should be able to run `./hf2gcode a`
  
3. Convert 3D printer to writing machine, watch the above video

4. Download this project, and **edit config.py**
    * HOME ALL
    * Move X and Y to the start point (top left) of the writing paper
    
![Demo paper](/images/demo_paper.jpg)
![Screenshot of the config.py](/images/screenshot_config.png)

5. Run `python3 3d-typewriter.py`
    * **The 3D printer HAS to be connected in OctoPrint first**
    * Press ESC to quit
