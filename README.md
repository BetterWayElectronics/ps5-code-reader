# BwE PS5 Code Reader

![BwE](https://i.imgur.com/oQi5lHU.png)

I am BwE of betterwayelectronics.com.au and I have been creating software to validate the PlayStation's flash since 2008 with the help of psdevwiki.com :)
I also repair consoles locally in Australia and have been doing that since 2008 also. I am only recently slowing that down due to commitments with a PhD I am undertaking. 

## FAQ ##

### What is this for? ###
	It is designed for BLOD PS5 consoles.

### What do I need to get going? ###
	A USB TTL device and the pinout for the PS4 southbridge for your model!

### Instructions? ###
	Wire up your USB TTL device (RX->RX, TX->TX, GND->GND) to the UART points (See attached diagrams!) then run the program. 
	The program will then search for the PS5. Plug AC power into the PS5 (or turn it on), so long as the southbridge works it will prompt that its been detected.
	From here you can get the code results! I recommend clearing logs and attempting to boot the console to understand your current issue better.

### Why isn't it free? ###
	This program is targeted towards businesses with bulk amounts of PS5s to repair. My products also come with support and continued development.
	
### Will you add more diagnostic codes? ###
	So long as people buy this program, yes.

### I get GDDR6 error top and bottom and a bank number, what does that mean? ###
	With the board positioned up and the RAM facing you the top row is the top 4 RAM chips and the bottom row is the bottom 4.
	Top row from left to right is 1, 2, 3 ,4 - Bottom row from left to right is 8, 7, 6, 5.
	See attached diagram!
	
### I am getting "Unknown Error Code (N/A)" ###
	Your PS5 is not getting a proper reply from the error code commands. No ground wire or loose wiring on USB TTL.
	Another possibility is that you're sending commands too quickly. Unplug everything and try later.
	

### TLDR; Will this fix my BLOD? No, that's your job using the information this program has given you! ###
### TLDR; Will this prove my BLOD is XYZ? Kinda yes, thats the idea. It will show you what has failed. ###

		
## Menu: ##
    
    1 - Read Current Error Code
    
    	Displays the active/current error code that the PS5 has!
    		
    2 - Read Last 10 Codes
    	
    	Displays the last 10 error codes that the PS5 has!
    
    3 - Clear Error Codes
    
    	Clears the entire log. I recommend this as your first step, then rebooting or unplugging and re-plugging AC.
    
    Q - Quit
    
    	Quits

## File Info ##
    
    File MD5: 92D969AC53DC843182BEE18725E98299
    Technical Support: bweps5codezz@betterwayelectronics.com.au
    
    System Requirements:
    	Minimum 4 CPU Threads
    	Windows XP, 7-11 (64bit) 
    	100mb+ Storage Space
    
    Archive Password:
    BwE

## Versions ##

	1.1.2 (14/12/23) Finally Fixed Error 36
	1.1.1 (13/12/23) Better UART Handling, Last Minute Bug Fixes (Annoying)
	1.1.0 (12/12/23) Code Improvement, Better Handling of Southbridge Errors, Bug Fixes (Again)
	1.0.9 (9/12/23) Code Improvement, Bug Fixes, Holiday Theme
	1.0.8 (28/11/23) Better Bug Fix For Connection Issues
	1.0.7 (27/11/23) Bug Fixes, Allows Extra Error Code Handling, Updated Errors
	1.0.6 (26/11/23) Added Error Code Auto-Updater (Will Grab New Codes Automatically!), Adjusted Communication W/ PS5, Updated Errors
	1.0.5 (24/11/23) Significantly Updated Errors, Small Output Changes, Officially Out of Beta (v1 Added)
	0.0.4 (11/11/23) Updated Errors, Added 'Known Unknown' Temporary Errors, Updated/Fixed Unique Error Handling
	0.0.3 (10/11/23) Updated Errors, Bug Fix for SAM_IPL Error, Better Unknown Error Handling, Updated HWID Generator
	0.0.2 (8/11/23) Completely Re-Written RAM Diagnosis, Added Support for 400+ More Errors, Added Unknown Error Auto-Uploading, Fixed Some Errors, Other Mild Edits
	0.0.1 (7/11/23) First Release! Public Beta

## Greetz ##
		
  	Thailand (Xohke!)
  	DarkNESMonk
  	omgitsben
  	PS3/PS4 Dev Wiki (+ Its Contributors)
  	3absiso
  	Totte
  	Palestine!
  	Hoea
  	DigiMod 
  	johnnydebt
  	SCE
  	You! 

  Proudly made in Perl with Notepad++ by BwE, alone </3

## Links ##
  
    Support/Donate:
    	https://www.buymeacoffee.com/BwE
    
    Console Repair Discord:
    	https://discord.com/servers/console-repair-discord-754165317961383997
    	https://discord.gg/pXeUHMy
    
    Videos Featuring My Program:
    	https://www.youtube.com/watch?v=B7mX7zPG5uc <--- PS5 Code Reader Video!
    	https://www.youtube.com/watch?v=hcmMSYmwSUQ <--- My Video!
    	https://www.youtube.com/watch?v=noS8wfZA99g <--- My Other Video!
    	https://www.youtube.com/watch?v=NDNld92tsZc <--- My PS5 Video
     	https://www.youtube.com/watch?v=cegGCQwKTtU <--- PS5 NOR Tools & Code Reader Video!
    	https://www.youtube.com/watch?v=fE4qGHJyX8E
    	https://www.youtube.com/watch?v=q1F0AL3ttjY
    	https://www.youtube.com/watch?v=W7RpkG5hiA0
    	https://www.youtube.com/watch?v=2hXO60rUt40
    	https://www.youtube.com/watch?v=D8-AMvsfadM (Uncredited)
    	https://www.youtube.com/watch?v=syfiph70reQ
    	https://www.youtube.com/watch?v=NBktKSx4FzQ
    	https://www.youtube.com/watch?v=LCOUepj5_8o
    	https://www.youtube.com/watch?v=GXOBX6BDg0I
    	https://www.youtube.com/watch?v=p8DyudhA7ME
    	https://www.youtube.com/watch?v=1gk7HtYih84
    	https://www.youtube.com/watch?v=m3wgiudcTEA
    	https://www.youtube.com/watch?v=EISO-t2fnMw
    	https://www.youtube.com/watch?v=Yal7cwdIKCg
    	https://www.youtube.com/watch?v=m5ZUEyya82g
    	https://www.youtube.com/watch?v=gHifHpquN6E
    	https://www.youtube.com/watch?v=laxB_D80nJE
    	https://www.youtube.com/watch?v=7D4Zte3vzvg 
    	https://www.youtube.com/watch?v=35DFGCim_WY
    	https://www.youtube.com/watch?v=m9nopeQw6dI (Uncredited)
    	https://www.youtube.com/watch?v=G7Vboawafc4 (Uncredited)
    	https://www.youtube.com/watch?v=5q0WWyYNsTs (Uncredited)
    	https://www.youtube.com/watch?v=AH-9jE1uDPk
    	https://www.youtube.com/watch?v=iSOWV-r_0J4 (Uncredited)
    	https://www.youtube.com/watch?v=kol1Zy9xc8I
    	https://www.youtube.com/watch?v=AH-9jE1uDPk
    	https://www.youtube.com/watch?v=E-ukC-Jjwfg
    	https://www.youtube.com/watch?v=QjkbB3lnRLw (Weird)
    	https://www.youtube.com/watch?v=A2c2UeM9V3A (Uhhh)
    	https://www.youtube.com/watch?v=FAk2oF0cByg
    	https://www.youtube.com/watch?v=PLrudwJHycU (Kinda Uncredited)
    	https://www.youtube.com/watch?v=bGnEu4UwsU4
    	https://www.youtube.com/watch?v=5q0WWyYNsTs (Uncredited)
    	https://www.youtube.com/watch?v=ZEwgtvKcB58 (Uncredited)
    
    Websites Featuring My Program:
    	https://repair.wiki/w/PS4_UART_Guide
    	https://wololo.net/tag/bwe/
    	http://www.logic-sunrise.com/recherche/bwe/
    	https://www.biteyourconsole.net/?s=bwe
    	https://psdevwiki.com/ps4/
    	https://psx-core.ru/forum/48-3196-3
    	https://consolefix.ru/aktivaciya-uart-dlya-diagnostiki-blod/
    	https://vlab.su/
    	https://gbatemp.net/search/3666652/?q=bwe&o=relevance
    	https://gamegaz.com/2022122937784/
    	https://www.psxhax.com/threads/release-bwe-ps4-nor-validator.6139/
    	https://www.playstationhax.xyz/forums/topic/5259-release-bwe-ps4-nor-validator/
    	https://www.psx-place.com/threads/tutorial-how-to-take-a-nor-backup-on-every-ps4.28070/
    	https://tieba.baidu.com/p/8196671153
    	https://yoschi.cc/gaming/es-ist-anscheinend-moeglich-ihre-ps4-ohne-backup/
    	https://psx-core.ru/forum/48-3196-5
    
    My Websites:
    	https://www.betterwayelectronics.com.au/
    	https://instagram.com/betterwayelectronics
    	https://github.com/BetterWayElectronics/
    	https://twitter.com/BwE_Dev
    	https://facebook.com/betterwayelectronics/
    	https://www.ps5repair.com.au/
  	
## Purchase ##

  If you are a commercial user, I highly suggest you buy the software here: https://betterwayelectronics.com.au/ps5codereader
  
  After purchase, provide your HWID via the provided application to obtain your license key.
