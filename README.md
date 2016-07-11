# Elevator-Simulation

The elevator simulator was developed using SWING, Which serves as the client for the elevator Web API.When the client simulator is run, 2 post request is send to the server in the text field. By Default the URL http://localhost:8080/elevator/webapi/elevators. It can be changed to any location where the application is deployed. For instance http://elevator-env.ap-southeast-2.elasticbeanstalk.com/webapi/elevators. Two elevator objects are created and each elevator is assigned an ID, which is an auto generated sequence of alphanumeric characters(for example, ABCD1234) and the current floor of the lift is set to 0. When the numbers in the respective lifts are pressed in the client simulator, put request are send to the server updating the current floors of the lift and the webpage can be refreshed so that the page indicates which floor exactly the lift is in.

The client can be run using the ElevatorSimulator.java file.
