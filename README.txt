Installation is very simple.
1) Copy the files from the computer and turtle directories to the correct directories.
( ComputerCraft/lua/rom/programs/ )
2) Either add this to the end of the ComputerCraft/lua/rom/startup file
if os.computerID() == serverID then shell.run("XoXOSLS") elseif os.computerID() == ChatServerID then shell.run("XoXOSCS") else while true do shell.run("XoXOS") end end
or 
replace it with the included file.
3) you must edit your computercraft setting and edit the range of modems to go pretty much anywhere.
Find this line in the settings:
modem_range=64
and change it to something high like
modem_range=6400000

same goes for 
modem_rangeDuringStorm=16


4) you want to set up the login server.
Set up a computer somewhere with a modem, and probably close to spawn so it is always loaded.
Now get the computers ID and in the XoXOS file, change the first line (serverID = ) accordingly
then do "edit XoXUsers" and add users to be devs, one per line.
after you saved this file, do "edit XoXPasss"
here you will the passwords for the users, the first user uses the 1st password, 2nd user 2nd pass, etc.

Once you have all your users set up, you are done, come back here any time to edit the users.


5) In the top of XoXOS change the value and the serverID's to the approriate ID's ( open PC and if "id" )
Same goes for the startup file if you didn't choose the one included with this.


If I forgot something in here please let me know.