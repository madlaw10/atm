Setting up a new Java project!

INTIALIZATION:
A. How to build a gradle in GitBash without curling the same gradle link in the slides:
	1. gradle init --type jave-application // Initializes a gradle build as a Java file called "java-application"
	2. add id "eclipse" to the plugins block of build.gradle
	3. gradle eclipse in GitBash

B. Import into Eclipse

DEVELOPMENT
A. Initialize git repo with git init
B. Make develop branch with checout -b

TOP DOWN DEV APPROACH
A. Begin the user interface
B. Create first method test, driven by UI creation
C. Get rid of all compilation errors in test suite
D. Continue creating tests & methods, refactor after each passing test
