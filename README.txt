files included:
	
	defs.h - definitions 
	Date.h/.cc - Entity obj, stores date info
	Part.h/.cc - Virtual base class of all Parts:
		LT_Part - Entity obj, parts that must be inspected after a certain # of launchs
		TT_Part - Entity, parts that require inspection after a specific period
		LT_TT_Part - Entity, parts require inspection after meeting launch and (or) time thresholds 
	Array.h - Container obj, templated data structure
	Rocket.h/.cc - Entity/Container obj, rocket data as well as a container for installed parts
	SpaceW.h/.cc - Contorl obj, tracks parts, rockets, installation, lauches, inspections, etc..
	
	Testing:
		TestControl.h/.cc
		View.h/.cc		
		main.cc

To compile:
	
	open a terminal in the assignment folder & enter the command: make

To execute: 

	follow that by entrig the command: ./a4
	