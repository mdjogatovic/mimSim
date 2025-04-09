# mimSim Simulation Software (2024.11-1)

mimSim Simulation Software (2024.11-1) is a graphical application software designed for creating and simulating models of discrete events systems. The script language of the software is the Python programming language, and the software itself is developed in the Python programming language.

The model consists of blocks that are interconnected by connections. The connection is established between the output and input ports of the two blocks. A block performs certain operations on model entities and objects. Entities are dynamic objects that are created and destroyed during simulation execution and move through model blocks. Static objects (we will call them only objects) are created at the beginning of the simulation execution and serve to limit the movement of entities through the model, collect statistics, generate times according to a certain distribution and perform certain operations on the model. Objects are graphically displayed as blocks without ports. In addition to blocks, entities and objects in the model, there is another unique object that serves to plan the execution of the simulation model and is called experiment. After the execution of the simulation model, the simulation results are displayed in a consolidated report. Figure 1 shows the graphical interface with the loaded model.

The software is characterized by the so-called drag&drop interface by which blocks and objects, which are on the palette (picture 1), are dragged onto the model sheet. After dragging, blocks and objects can be arranged on the model list as desired. Also, by clicking on the input or output port of the block and dragging it is possible to connect two different blocks. The model sheet is of infinite size and can be moved, enlarged and reduced as desired. Blocks and objects of the model can be selected, their properties can be changed, deleted and copied.

![mimSim Simulation Software screenshot](https://github.com/user-attachments/assets/d874068a-c851-460f-bd7b-92addb8619e7)

Licence: [CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/)
Copyright © 2024-2025 Marko Đogatović, mimsimsoft@gmail.com. All rights reserved.
