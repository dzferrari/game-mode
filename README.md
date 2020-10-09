# game-mode
Set Digital Vibrance and Mouse Acceleration

IMPORTANT: Remember that the main thing people may want to change in this code is the Mouse_Name term. It is possible to find one's mouse name with @$ xinput --list .

If you run this script without arguments, it will toggle between the Game Mode Default and Default functions, 
which are: switching Nvidia Digital Vibrance to 405 and Mouse Acceleration to -1, and both to 0.

**UPDATE**: In order to keep my accel always constant at -1, I decided to not let it normally switch back to 0, only if requested.

Syntax: game-mode [OPTION] (VALUE)

OPTIONS:
-a			Acceleration. Set Mouse Acceleration manually. Insert value after this flag.
-c  | --check		Check current Digital Vibrance and Mouse Accel.
-d  | --default		Default. Reset configs to default. Vibrance and Mouse Accel will be set to 0.
-g			Game Mode Default. Digital Vibrance set to 405 and Mouse Accel set to -1.
-h  | --help		Help. See the Help Message.
-nd | --new-default	New Default. Set configs to new default, being Vibrance 405 and Accel -1.
-v			Vibrance. Set the Digital Vibrance manually. Insert Value after this flag.


--dpi			DPI. Set Mouse DPI manually. Insert value. ATTENTION: changing this DPI value 
    			will affect the preset resolutions of your mouse.

