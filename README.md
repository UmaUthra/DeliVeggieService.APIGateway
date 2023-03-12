# DeliVeggieService.APIGateway
This API Gateway transforms the Incoming HTTP Request from the client and forward it to our appropriate Deliveggie Microservice. <br/><br/>
This is implemented using Ocelot and it has a JSON configuration file that states the upstream and downstream routes.<br/><br/>
Base URL of gateway upstream BaseUrl: "http://localhost:5004/gateway/product". <br/><br/>
Deliveggie Microservice's downstream URL: "http://localhost:7164/v1/product"<br/><br/><br/>

Downstreamed data from the Deliveggie Microservice on the gateway can be visualised below:<br/><br/>
![image](https://user-images.githubusercontent.com/127690033/224571438-370ea3dd-3f89-47ba-90d3-38b599074922.png)
