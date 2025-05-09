# Vespidae

[About](#about-vespidae) \
[Wiki](https://github.com/machineagency/Vespidae/wiki) \
[Installation](https://github.com/machineagency/Vespidae/wiki/Installation-Instructions) \
[Examples](https://github.com/machineagency/Vespidae/tree/main/examples) \
[Citing Vespidae](https://github.com/machineagency/Vespidae/wiki/Citing-Vespidae) 

***
## About Vespidae

Vespidae is a framework for prototyping and creating toolpaths for computer controlled motion systems (e.g 3D printers, laser cutters, CNC milling machines). At its core, Vespidae includes tools for manipulating and generating toolpaths as curves in Rhino, tools that tags these curves with process specific metadata, and finally tools that converts these actions to executable programs. Vespidae also includes tools for communitation between grasshopper and a machine controller. 

Vespidae is designed with an ethos to provide users with as much flexibility as possible when working with digital fabrication equipment. Modern CAM/slicing tools gives designers good means to create complex and efficient toolpaths, but this power comes at a cost of loosing flexibility and control. Full toolpath control can be particularly important for people who are either looking for specific aesthetics or for people who are building bespoke tools that does not necessarily fit into existing CAM tools. 

Vespidae was published in the [2023 Proceedings for the ACM Designing Interactive Systems Conference](https://dl.acm.org/doi/10.1145/3563657.3596106).

More information can be found in our [wiki](https://github.com/machineagency/Vespidae/wiki).

## Why does this exist? 

In the good ol' days CNC operators programmed their machines in raw "goto-position" commands (gcode). This took a fair amount of time to do and limited the complexity of what programs a machinist was able to make. However, it also kept the machinist close to what the machine was doing and gave the operator total control of each machine action. 

Todays CAM tools and slicer relieves the machinist/maker of this complexity by automating the generation of toolpaths and gcode. This is all great and in many cases efficient and useful, but there are edge-cases when you want to be more specific and have more control. In my world, where I build custom machines for different weird workflows, a proper CAM tool doesn't really exists. Vespidae positions itself as a sort of hybrid between these two workflows. 
