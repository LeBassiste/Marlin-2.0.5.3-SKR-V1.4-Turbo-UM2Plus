# Marlin-2.0.5.3-SKR-V1.4-Turbo-UM2Plus
Marlin 2.0.5.3 Settings for BIGTREE SKR 1.4_Turbo, TMC5160 to drive Ultimaker UM2+ 3D Printer

1.Required Hardware					
  a.  1	 BTT SKR 1.4 Turbo				
  b.  4	TMC5160 Stepper drivers				
  c.  1	BTT DCDC Power Module for SKR 1.4				
  d.  1	 PT100 Pre-Amplifier (Ultimaker Style), 3 channel, must use VDD = 3.3 VDC (DIY), see KICAD files			
  e.  1	MOSFET Adapter Board to run Hotend Fan off of SERVO connector (DIY)				

2. What will these Mods do?					
	a.  Enable flicker-free dimmable Case Lighting, using the original Ultimaker Case LEDs @ 24 VDC and high frequency PWM dimming		
	b.  enable PWM-controlled Parts Fan				
	c.  enable PWM-controlled 5VDC for use with Hotend Fan	(needs extra MOSFET and Diode, driven from SERVO connector)			
	d.  increase Bed-Heater and Hotend-Heater PWM to 60 Hz to smoothen power consumption (note: you must use PID for Bed Heater). 
      This improves print quality!				
	e.  enable ulticontroller display and Clickwheel+LEDs as published by Anthrix https://community.ultimaker.com/topic/30786-ultimaker-with-skr-14/
