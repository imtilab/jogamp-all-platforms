# jogamp-all-platforms

Configure JOGL in Eclipse for Graphics projects
----------------------------------------------
1. Download and copy "jogamp-all-platforms" to your machine's any folder.
2. Make sure you have JAVA installed in your machine.
3. Open eclipse IDE.
4. Goto Window-> Preferences-> Java-> Build Path-> User Libraries.
5. Click on New and create a new user library name it JOGL (or something else) and click OK.
6. Click on Add External JARs (easier) or Add JARs and then add the following jars to it 
   (you can find these jars in jogamp-all-platforms -> jar).

	(if you are using linux, add below 4)
	1. gluegen-rt.jar
	2. gluegen-rt-native-linux-amd64.jar
	3. jogl-all.jar
	4. jogl-all-native-linux-amd64.jar
	
	or, (if you are using windows, add below 4)
	
	1. gluegen-rt.jar
	2. gluegen-rt-native-windows-amd64.jar
	3. jogl-all.jar
	4. jogl-all-native-windows-amd64.jar
   
   Now click OK.
	
N.B. if you are on a 32 bit machine use jars like "gluegen-rt-native-linux-i586.jar"
	or, for windows 32 use jars like "gluegen-rt-native-windows-i586.jar".


From now on for every project you create,

1. Right click on project-> Properties-> Java Build Path-> Libraries-> Add Library->
2. Select User Library and click Next.
3. Select the the library you just created, click Finish and then OK.


You are ready to start your Graphics project.
