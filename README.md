Welcome to the 2D-Heat transfer inside a pipe of circular cross-section module:

	-This Module is designed to capture the 2D-Temperature distribution inside a Circular pipe due Conduction Convection heat transfer modes.
	- It uses Cylindrical Co-ordinate system
	- Velocity profile is assumed Parabolic using 
		U = 2*U_in*(1- (r/a)^2)
	- Laminar flow is considered throughout the domain.
	- 
	- The solving Modules are designed using two different coding languages.
  	     1)The Console based module that is built completely using Python ( Less user friendly but runs on a open source platform)
  	     2)The GUI integrated module is built completely using MATLAB(user friendly and most Preferable)
		[Note: both the modules are designed to gives result with close accuracy.]

List of Files:

1. Matlab_GUI_code:

	- full_screen_gui_responsive.m -> run code block - GUI module pops up - Enter all the input parameters - press the run simulation button - check on the progress bar - simulation completed pop up opens - a short video of the transient simulation will be displayed.
	- wait till the simulation is completed to run a different simulation.
	-  To interrupt the simulation in between press the end simulation button - simulation ended pop up opens- close the GUI and repeat the above steps.
	Note: * To use CFL value less than 0.5 if initial and inlet temperatures are different for stable results
	      * To use CFL value less than 1 if initial and inlet temperature are same.
	
	- Con_con_HT.m -> run the code block - same as full_screen_gui_responsive.m but without the GUI. The values has to be changed in the code and gives the same result

2.Python_console_code:

	- Con_Cov_HT.py -> Run the code block - Input the required parameters in the Console in SI units - plots will be plotted for skipped time steps 
	- Stability _final.py -> Run the code block - This code block allows to see the stability region and gives the CFL values of stable margin

3. Exe file
	- an standalone application named LD_MODULE is created to execute this problem. It can be installed in windows and can be used using a interactive GUI interface.


	
