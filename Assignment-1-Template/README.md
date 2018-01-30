# Install maven - compile 
To compile the project and create a single jar file with all dependencies: 
	
	mvn clean compile assembly:single
	
This maven command will generate a jar file with all of dependencies and put that in the target folder. 

	
# Run Experiments 

You can run the Main class of this project by using the following command:

	java -cp target/java-8-example-0.1-SNAPSHOT-jar-with-dependencies.jar edu.bu.cs755.Main
	

17
        
Java JDK 8 is required for this project. 

You can find examples of S3 AWS SDK here https://docs.aws.amazon.com/sdk-for-java/v1/developer-guide/examples-s3.html 


