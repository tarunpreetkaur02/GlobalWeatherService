# GlobalWeatherExercise
GlobalWeatherExercise to wrap the SOAP service to REST API

This is the REST adapter for the Global Weather SOAP-based web-service:
It includes the technical specification document and the Mule code.
Instructions to run the project:

NODE
Clone the aforementioned repository
Go to weatherExcerciseDockerFile(Provided in the problem statement) folder and run npm install
Run node server.js to start the Weather SOAP WS
Check whether both the  operations are running on the localhost
http://localhost:8080/GlobalWeather

MULE EE RUNTIME
Go to https://www.mulesoft.com/lp/dl/mule-esb-enterprise and download the latest Mule ESB
Unzip the downloaded file to create the folder
MULE APPLICATION
Import the JAR file globalweatherproject.jar into the Anypoint Studio
Be sure to have JRE or JDK 8 installed

THE API
Open postman or simply go to Firefox and navigate to these URLs:
http://localhost:8081/api/v1/weather
http://localhost:8081/api/v1/cities?country=Australia

THE EXCEPTIONS
Error 400, 404 and 405 have been handled.
