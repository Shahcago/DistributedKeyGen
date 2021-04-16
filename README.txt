Author: Shahrukh Zarir
Credits to https://github.com/venishjoe/utilities/blob/master/src/java/RegistrationAppSerialGenerationReversal.java
This resource provided me the algorithm for Generating an App Key

Purpose: Practice Client Server Interactions

This project contains 4 java files
	1.	Client.java
	2.	KeyGen.java --> (Remote interface)
	3.	KeyGenImpl.java
	4.	KeyServer.java

How to run the program:
	1.	Navigate to the project folder from command prompt
	2.	javac *.java
	3.	Run server:	Copy and paste the following command
		java -Djava.security.policy=policy.txt KeyServer

	4.	Open another terminal and run the client program as following
		java -Djava.security.policy=policy.txt Client