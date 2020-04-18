# popi_mechanics

<img align="center" src="https://i.imgur.com/ONQVNOU.png" width="100%"/>
<br>
<br>

<em>POPI is an entirely open-source quadruped robot. You will find here everything you need for [machining] and [assembly] as well as the [mechanical drawings] of this 71kg and 1 meter long robot. These docs unfortunately are in French for now, but the drawings should still speak to anyone. Let us know if you ever need a translation and we'll do our best !
<br> For more information about the mechanical principle, please read the following information. <em/>
<br>

:heavy_check_mark: Design made with [CATIA].  
:heavy_check_mark: First estimates of forces and torques on [SimDesigner]
:heavy_check_mark: Mechanical simulation and actuator's choice on [SolidWorks] Motion and [SolidWorks] Simulation.
:heavy_check_mark: Machining with CNC milling and turning machines, water jet cutting and 3D printing.
:heavy_check_mark: Rendering with [SolidWorks] Motion and [SolidWorks] PhotoView 360
<br>
<br>

<p align="center">
  <a href="#general-description">General description</a> •
  <a href="#how-it-works">How it works</a> •
  <a href="#lets-look-further">Let's look further</a> •
  <a href="#publications">Publications</a> •
  <a href="#team">Meet the team</a> •
  <a href="#acknowledgments">Acknowledgments</a>
</p>

<p align="center">
	<img src="https://i.imgur.com/44D5gbH.gif" />
</p>
<br>
<br>

## <a name="general-description"></a> General description
  

POPI, in nominal position, has the following general dimensions: 1017mm x 662mm x 620mm (DxLxH). The general assembly is available in [3D folder]. With CATIA V5 software, download all the folder and open the top assembly "ALL10-FinalVersion.CATProduct".
<p align="center">
	<img src="https://i.imgur.com/vjhk1Fi.png" />
</p>

As shown below, some accessories are necessary for the proper handling of the robot, such as a base and handles. Available in [3D folder] with the respective names ["Socle"] and ["Poignee"].

<p align="center">
	<img src="https://i.imgur.com/C2iJyDn.png" /> 
</p>
<br>
<br>

## <a name="how-it-works"></a> How it works

POPI has a longitudinal axis of symmetry. It has 4 legs, identical 2 to 2.

<p align="center">
	<img src="https://i.imgur.com/YOD6UjQ.jpg" /> 
</p>

POPI is composed of 12 actuators, 3 per leg.

The combination of the "pitching hip joint" and "knee joint" actuators allows the robot to operate linearly. The action of the "rolling hip joint" allows the robot to turn and rebalance hitself.

<p align="center">
	<img src="https://i.imgur.com/Mb8C8Sg.png" /> 
</p>

Zoom on a leg and its actuators without the body ;
<p align="center">
	<img src="https://i.imgur.com/m2J5HHf.png" /> 
</p>

You will find all the actuators data [here].
<br>
<br>

## <a name="lets-look-further"></a> Let's look further

This design remains a proof of concept, designed and built in a few months by novice students in this field. Optimizing the existing and taking into account the problems encountered will allow us to achieve a truly functional V2.  
  
<h4>Thoughts for a future version;  </h4>

<ul>
<li>
Do not make legs too heavy compared to the body and think in advance of the robot's balance. We currently have too much weight on the back compared to the front, so the rear feet are struggling to get off the ground.
</li><li>
Think about the programming in parallel of mechanics, test all possible approaches in a physical simulation of walking before machining the robot. SolidWorks Motion does this perfectly. 
</li><li>
Our robot can move all of its joints independently, it's cool, but think about whether this is really useful. Maybe moving the robot's pitch hip just proportional to the knee is enough.
</li><li>
Our robot is built in a simple way, that's the goal, but a slightly more complex arrangement that would allow the knee to move without a cylinder can be more efficient. A motor, which could be integrated into the body and act on the knee by chain/pulley might be a better solution.
</li>
</ul>
<br>
<br>

## Contribute
The whole point of making this project fully open-source is to have anyone who is interested contribute to POPI ! Whether it includes documentation translations, new functionalities, bug fixes or code improvements, we'll be glad to receive your pull request !  
We're fully aware we still have a long road to go before POPI becomes an impressive robot, and we'll be happy to take anyone with us onboard.  
You can see here the list of [contributors](https://github.com/popi-mkx3/popi_ros/graphs/contributors) who participated in this project.
<br>
<br>

## <a name="team"></a> Meet the team !

<p align="center"><b> Project Leader </b></p>
<p align="center">
  <a target="_blank" rel="noopener noreferrer" href="https://www.linkedin.com/in/clément-thomaso-6b9ab910b/"><img src="https://i.imgur.com/3dUgaow.png" width="10%" alt="Clément Thomaso"/></a>
</p>

<p align="center"><b> Mechanics </b> &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; <b> Electronics </b> &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; <b> Programming </b></p>

<p align="center">
  <a target="_blank" rel="noopener noreferrer" href="https://www.linkedin.com/in/rémi-combacal-16032214a/"><img src="https://i.imgur.com/ZVTtgik.png" width="10%" alt="Rémi Combacal"/></a>
  <a target="_blank" rel="noopener noreferrer" href="https://www.linkedin.com/in/anaïs-gutton-655383a6/"><img src="https://i.imgur.com/ff2XJUW.png" width="10%" alt="Anaïs Aharram-Gutton"/></a>
  <a target="_blank" rel="noopener noreferrer" href="https://www.linkedin.com/in/olivier-peres/"><img src="https://i.imgur.com/SLJLxvD.png" width="10%" alt="Olivier Peres"/></a>
  <a target="_blank" rel="noopener noreferrer" href="https://www.linkedin.com/in/guillaume-rougé-913a10108/"><img src="https://i.imgur.com/kFxLFVK.png" width="10%" alt="Guillaume Rougé"/></a>
  <a target="_blank" rel="noopener noreferrer" href="https://www.linkedin.com/in/clémence-graton-a02200174/"><img src="https://i.imgur.com/OOfYG0X.png" width="10%" alt="Clémence Graton"/></a>
  <a target="_blank" rel="noopener noreferrer" href="https://www.linkedin.com/in/jean-pelloux-prayer-b38a32143/"><img src="https://i.imgur.com/4oOODpr.png" width="10%" alt="Jean Pelloux-Prayer"/></a>
  <a target="_blank" rel="noopener noreferrer" href="https://www.linkedin.com/in/yannis-oddon-442717128/"><img src="https://i.imgur.com/YUDleYD.png" width="10%" alt="Yannis Oddon"/></a>
  <a target="_blank" rel="noopener noreferrer" href="https://www.linkedin.com/in/karla-brottet-69440/"><img src="https://i.imgur.com/4GvkygH.png" width="10%" alt="Karla Brottet"/></a>
  <a target="_blank" rel="noopener noreferrer" href="https://www.linkedin.com/in/lucas-labarussiat/"><img src="https://i.imgur.com/eMQNCa7.png" width="10%" alt="Lucas Labarussiat"/></a>
</p>

<br>
<br>



<img src="https://i.imgur.com/Qv3iWwq.jpg" height="151"/> &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; <img src="https://i.imgur.com/5oggd8Z.png" height="151"/> &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; <img src="https://i.imgur.com/TJwQi9n.jpg" height="151"/>

[mechanical drawings]: https://github.com/popi-mkx3/popi_project/tree/master/popi_mechanics/mechanical_drawings
[machining]: https://github.com/popi-mkx3/popi_project/blob/master/popi_mechanics/mechanical_drawings/POPI_PlanMeca_Usinage.pdf
[assembly]: https://github.com/popi-mkx3/popi_project/blob/master/popi_mechanics/mechanical_drawings/POPI_PlanMeca_Notice_de_montage.pdf
[CATIA]: https://i.imgur.com/riZaPoB.png
[SimDesigner]: https://i.imgur.com/Nx55Sqr.png
[SolidWorks]: https://i.imgur.com/M5bYSk7.png

[3D folder]: https://github.com/popi-mkx3/popi_project/tree/master/popi_mechanics/CATIA
["Socle"]: https://github.com/popi-mkx3/popi_project/blob/master/popi_mechanics/CATIA/Socle.CATPart
["Poignee"]: https://github.com/popi-mkx3/popi_project/blob/master/popi_mechanics/CATIA/Poignee.CATPart

[here]: https://github.com/popi-mkx3/popi_project/blob/master/popi_mechanics/POPI_actuators_data.xlsx

[popi_docs]: https://github.com/popi-mkx3/popi_docs
[ROS]: https://www.ros.org/
[Towr]: https://github.com/ethz-adrl/towr
[rqt_bag]: http://wiki.ros.org/rqt_bag
[xpp]: http://wiki.ros.org/xpp
[RViz]: http://wiki.ros.org/rviz
[URDF]: http://wiki.ros.org/urdf
[Gazebo]: http://gazebosim.org/
[rqt_gui]: http://wiki.ros.org/rqt_gui
[ROS Melodic]: http://wiki.ros.org/melodic/Installation/Ubuntu

[BalenaEtcher]: https://www.minimachines.net/tutos/etcher-flasher-image-usb-50144
[ROS control boilerplate]: https://github.com/PickNikRobotics/ros_control_boilerplate

[Alexander W. Winkler]: https://www.alex-winkler.com
[Dave Coleman]: http://dav.ee/
[TiMOTION]: https://www.timotion.com/fr
[IMT Mines d'Alès]: https://www.mines-ales.fr/

[Clément]: https://www.linkedin.com/in/clément-thomaso-6b9ab910b/
[Rémi]: https://www.linkedin.com/in/rémi-combacal-16032214a/
[Anaïs]: https://www.linkedin.com/in/anaïs-gutton-655383a6/
[Olivier]: https://www.linkedin.com/in/olivier-peres/
[Guillaume]: https://www.linkedin.com/in/guillaume-rougé-913a10108/
[Clémence]: https://www.linkedin.com/in/clémence-graton-a02200174/
[Jean]: https://www.linkedin.com/in/jean-pelloux-prayer-b38a32143/
[Yannis]: https://www.linkedin.com/in/yannis-oddon-442717128/
[Karla]: https://www.linkedin.com/in/karla-brottet-69440/
[Lucas]: https://www.linkedin.com/in/lucas-labarussiat/