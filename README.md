physcomp-solidworks
===================

This repository provides SolidWorks CAD examples for courses in the
[IDeATe](http://ideate.cmu.edu) programs at
[Carnegie Mellon University](http://www.cmu.edu).  All materials are provided
under a BSD license unless otherwise specified.


Contents
--------

A few useful parts have been provided by the instructors.

      library_parts	        Simplified standard small parts (bearings, spacers, etc.)
      gear_library	        A few sample gears generated using an online tool.

The gear parts were generated using <http://hessmer.org/gears/InvoluteSpurGearBuilder.html>

The folders labeled 'example' are designed to highlight principles of mechanical
design for the course.  These are not necessarily fully realized designs ready
to fabricate, they are demonstrations and building blocks.

	  laser_test_example      Several test parts for demonstrating laser cutter kerf.
	  linkage_example	      Four-bar linkage to demonstrate underconstrained assemblies
	  pendulum_example	      Extrusion structure with ball-bearing clevis pin joint and a fixed T-joint.
	  spokes_example	      Laser-cuttable joining plates for building complext extrusion structures.
	  switch_trigger_example  Simple lever mechanism to extend microswitch travel and shape sensing region.
	  stepper_motor_example	  Stepper motors mounted on an extrusion structure.
	  turntable_example	      Motor and gear example using a ball-bearing supported shaft and parallel plate structure.
	  wedge_examples    	  Examples of laser-cuttable wedge-and-slot structures for creating rigid 3D structures from flat parts.

HSMWorks is a CAM tool for generating cutting plans for the CNC router from a SolidWorks model:

	  HSMWorks				Folder with tool library and post-processor script for the IDeATe CNC router.

A following open-source designs for OpenBeam and related components were
downloaded from thingiverse.com and are subject to the original licensing terms:

      OpenBeam_1515_Extrusion_V2
      OpenBeam_L_Bracket
      OpenBeam_T_Bracket

