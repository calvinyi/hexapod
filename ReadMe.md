# Warning 

******************************************************************************************
*** This branch is a real WIP to try to add some Quad support        *
* into the library.  I will upload things in this branch that are not working...  Also   *
* at times, some changes may be due to trying to get this to compile on an Arduino Due   *
******************************************************************************************

Warning, this is a Work In Progress!  There are no warrantees or Guarantees
of any type that this code is useable for anything.  But I hope it is�

This set of directories are my latest attempt of breaking up the Phoenix code
base for the Arduino, into libraries that you can use to build different builds
for many different hexapods�  Most of the code in these libraries are in header
files, which allows them to be compiled specifically for each project.   

Hopefully soon, I will update this readme with more instructions on how to configure
these to do different things.  To use this code you need to copy each of the included
directories into your Arduino Library directory.  I personally use the User library
directory, which is located some place like: <Your User>\My Documents\Arduino\libraries.

In the Phoenix library there are several examples of configurations.  Once these
directories are installed, you can simply go to the file menu, look in the Examples
menu item, and hopefully in this list will be Phoenix and under this are
several configrations�


Note: I think this last check in should match the functionality of the changes
made by Jeroen (Xan) for the code up on the Lynxmotion gethub code... 

In addition I also made the changes where you can choose which servos need to be
reversed in the hex config file, also not specific to quads.  This required changes
to all of the _Driver_ files

Good Luck
Kurt