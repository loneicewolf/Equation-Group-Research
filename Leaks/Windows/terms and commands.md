Terms:
 

 - OP = operations
 - target = attacked computer
 - LP = listening post C&C
 - Plugin = functionality
 - command = something running on the target
 - PSP = Antivirus/ Personal Protection Product
 - Safety Handler = what protects them from being caught
 - Implant = malicious code deployed on target
 - Instance = A specific instance of Killsuit (multiple can be installed)
 - Type = A specific kisu instance intended to support persistence for a complex implant
 - Launcher = The driver exploited to run Kernel Mode code
 - Module = Specific Implant / Code that is intended to be persistent
 - Module Store = Encrypted Virtual File System in registry

Commands:
 
While in Fuzzbunch Framework:
  

 - "frzlinks -list"												Shows all the links that can be enabled with friezeramp traffic injection 
 - "packetdirect"  				      		It is a tool that dropskernel level driver that goes  past the tcp/ip stack and allows for raw command injection
 - “flav_control  -ipconfig” 		Let's you config IPs, raw sockets (short for Flew Avenue)
 - “docsurvey"   					    					Identifies interesting documents and sharepoint sites
 - "sharepoint"  					    					Recursively pull interesting files (after finding them with  docsurvey)
 - “kisu_survey” 					    					Shows detailed information on target, such as OS, PsPs

 While in KillSuit Framework;
 
 - "kisu_install  -type moan"		Gives you MOAN, MABE, SOKN, DEWH
 - "doublefeature"  					    Tells you how killsuit and the instance is configured

