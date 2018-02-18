# Client-Server-communication-with-real-time-direction
Project that communicates between a server and a client by taking destination address from a client and sends it to the server to create a communication (mapping) route. It uses Google Maps direction API. This project was built for a direction both IEEE-Hardware Hackathon -2018 for a communicating bot


To run the project, please follow the following set of instructions:

1) Run the planner.py file. This file contains a server. As soon as you run the file, it will create a server on port 1. 

  `python planner.py`
  
2) Add the client to the program and connect to it. Send the client destination. The server will receive it and prompt you to enter the source.

3) Using Google maps API, this will find an optimal route/

4) The output is dumped into a .json file (sample.json) and then parsed into a different file `dank.txt` (I apologize for the naming convention.

5) Use that output however it is necessary 
