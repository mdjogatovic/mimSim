# mimSim Simulation Software (2024.11-1) 🕜 📈

__mimSim Simulation Software (2024.11-1)__ is a graphical application software designed for creating and simulating models of discrete events systems. The script language of the software is the Python programming language, and the software itself is developed in the Python programming language.

## How mimSim works

The model consists of blocks that are interconnected by connections. The connection is established between the output and input ports of the two blocks. A block performs certain operations on model entities and objects. Entities are dynamic objects that are created and destroyed during simulation execution and move through model blocks. Static objects (we will call them only objects) are created at the beginning of the simulation execution and serve to limit the movement of entities through the model, collect statistics, generate times according to a certain distribution and perform certain operations on the model. Objects are graphically displayed as blocks without ports. In addition to blocks, entities and objects in the model, there is another unique object that serves to plan the execution of the simulation model and is called experiment. After the execution of the simulation model, the simulation results are displayed in a consolidated report. Figure 1 shows the graphical interface with the loaded model.

## Features

The software is characterized by the so-called drag&drop interface by which blocks and objects, which are on the palette (Figure 1), are dragged onto the model sheet. After dragging, blocks and objects can be arranged on the model list as desired. Also, by clicking on the input or output port of the block and dragging it is possible to connect two different blocks. The model sheet is of infinite size and can be moved, enlarged and reduced as desired. Blocks and objects of the model can be selected, their properties can be changed, deleted and copied.

## Reports

In the mimSim simulation software, there are two types of reports and one output. The first report shows the simulation results and can be generated and displayed after completing a simulation experiment (Figure 2). The second report can be generated at any point in time, and its purpose is to provide a detailed and clear description of the model. The output is used to show intermediate results and messages during the execution of the simulation model.

## Screenshot

![mimSim Simulation Software screenshot](https://github.com/user-attachments/assets/d874068a-c851-460f-bd7b-92addb8619e7)

![mimSim Simulation Software report screenshot](https://github.com/user-attachments/assets/2129f330-ecca-47ba-84cb-ef0832a4a214)

<p xmlns:cc="http://creativecommons.org/ns#" >This software is licensed under <a href="https://creativecommons.org/licenses/by-nc-nd/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;"> CC BY-NC-ND 4.0 </a>&nbsp; &nbsp; <img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nd.svg?ref=chooser-v1" alt=""></p>

Copyright © 2024-2025 Marko Đogatović, mimsimsoft at gmail.com. All rights reserved.
