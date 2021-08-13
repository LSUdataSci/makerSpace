## Circuit Playground Express setup


Below are instructions based on [these _adafruit_ guidelines](https://learn.adafruit.com/adafruit-circuit-playground-express/circuitpython-quickstart) for setting up CircuitPython on your Circuit Playground. The instructions are pretty independent of your operating system (OS). Do not hesitate to reach out with questions. 


### steps for setup

+ [Download the CircuitPython library](https://circuitpython.org/board/circuitplayground_express/). If you do not have Python installed, you will also need to install [Python](https://www.python.org/downloads/) on your machine. 

+ Plug a micro-usb cable into your Circuit Playground Express, and connect the other end to your computer. _Be sure that this USB cable is not just for charging, but is also capable of transmitting data_ 


+ Press the `reset` button twice on your Circuit Playground Express. The reset button is a small button in the center of the Circuit Playground. This should mount the drive and it will likely be called "CPLAYBOOT". Drag the downloaded `.uf2` file that you downloaded in step 1 onto this drive. This should cause the drive to disappear for a moment, and then re-mount as "CIRCUITPY". The resulting directory will contain 3 files. The `code.py` file (create this file if it is not present) will be where you programmatically interact with the Circuit Playground. 




### further reading

+ [more detailed instructions available here](https://learn.adafruit.com/welcome-to-circuitpython/installing-circuitpython)

+ the _adafruit_ folks recommend using [mu editor](https://codewith.mu/) as a development environment. 




### initial project ideas

All code will be written in the `code.py` file created during the setup steps above. You can edit this file to program whatever input/output you would like. 


![circuitPlayground](https://cdn-learn.adafruit.com/assets/assets/000/046/973/medium800/circuit_playground_express-labeled.jpg?1507155485)

As you can see, there are a number of things which can be controlled via the Python code in `code.py`. 


**Some good next steps for learning how to control the different outputs**

+ [circuitPython help page](https://learn.adafruit.com/welcome-to-circuitpython/creating-and-editing-code) 

+ [starter code](https://github.com/adafruit/PyCon2019/tree/master/Circuit_Playground_Express_Examples) 



