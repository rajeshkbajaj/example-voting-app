# Set up docker voting application using docker-compose

For Task 1: 
Created a Docker Compose file with one replica of all services 
vote :
![image](https://user-images.githubusercontent.com/98638681/208871820-6d0b2f18-2591-46c2-b7e5-17b71cf6938e.png)
result:
![image](https://user-images.githubusercontent.com/98638681/208871967-75de64dc-a46d-46d9-b94f-6167caf3fdfa.png)

For Task2 and Task 3: Created a 2 forntend vote service vote 1 and vote 2 which is running at port 5000 and 5002 then added a nginx round robin loadbalancer so that it forward the request to one of the containers using the round-robin method of load balancing (which is a default method in case of Nginx).
nginx Dockerfile and conf files are in nginx folder
![image](https://user-images.githubusercontent.com/98638681/208872716-fab2c662-9263-4c28-9cb9-d970d709191b.png)

Deploy voting application using docker swarm under placement constraints.
check docker-stck.yml file
