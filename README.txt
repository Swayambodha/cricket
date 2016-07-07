The code, written in pure Java, implements an AI engine for the game of Cricket based on Monte Carlo Tree Search. 

For more details, see this blog post: 

	http://resonantai.blogspot.com/2016/07/designing-ai-for-cricket.html


*** REQUIREMENTS ***

The code uses JFreeChart (v1.0.19) to display graphs for game statistics. 

Download it here: 

	https://sourceforge.net/projects/jfreechart/files/1.%20JFreeChart/1.0.19/

Then, create a "lib" folder in the root project ("cricket") and copy these 2 jars inside the lib directory:
1. jcommon-1.0.23.jar
2. jfreechart-1.0.19.jar

*** USAGE ***

To run the code, use TestAIEngine.java (in the package test.cricket.aiengine). 

See usage options inside the class. 

The default run configuration (i.e. with no arguments specified) simulates one T20 match between India and Australia and displays graphs with stats at the end.

