# demoprojects
Sample demo projects

**SWAGGERJERSEY [Swagger Integration with Java REST API]** 

swaggerjersey is the sample project for someone who wishes to configure swagger with embedded Jetty. 
The REST framework used here is Java Jersey, and Jackson annotations for serialization and deserialization.

To Build the project run the following

`mvn clean install`

You can then run the Main class (Main.java)
The server should be accessible at http://localhost:50001/ping -> this should return ALIVE.
http://localhost:50001/api/swagger should render the REST API description
http://localhost:50001/docs should render the API page with the api specs.
