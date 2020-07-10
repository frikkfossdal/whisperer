# whisperer
Cabinet enclosed motion platform for at-home fab experiments

![Overview axis and enclosure](https://github.com/frikkfossdal/whisperer/raw/master/doc/img/illustration-01.png)

[Fusion360 file](https://a360.co/3fltCU0)

## The why 
I have a bunch of spare parts lying around that I want to combine into a machine. As for the machine itself, I want a general motion platform for experimenting with how to interact with toolpaths. Ive been on a spiral lately were I am deeply motivated by how synthesizers are used to create beats and sound patterns. I want something similar for toolpaths, and explore how this can be used to create different textures and surfaces on a milling machine without ever touching any CAM systems. 

## Machine design 

### Motion 
For motion I will be using a custom branch from the [Fabricatable Machines project](https://github.com/fellesverkstedet/fabricatable-machines). The axis plates themselves will be made out POM, and will rely on material flexures for alignment and thighness. Precision-wise this is a gamble, especially for milling harder stuff, but in the name of exploration I will give it a go. For the rails, I will use some alu-extrusions I had lying around. For actuation, I will use NEMA23s driving lead screws. This is defenately a deviation from some of the Fabricatable philosophy, but Im excited to give it a go. This is always something I can come back to at a later point.

### Software & Control 

First go on the [Duet](https://www.duet3d.com). Future here I come! 

