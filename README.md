##########################################################
- Welcome to  "async-scope"
- This API is to learn about Async scope
	- We get the flight details from Flights API which is provided in training classes by mulesoft
	- In between getting the data and prinnting out, I used a async scope which have Flights http request which sending the data to active MQ
	- Before going forward, please learnn about async (processing strategies)
		# https://www.youtube.com/watch?v=7nEn9h57dlE&t=459s
		# https://dzone.com/articles/async-scope-with-mule-esb#:~:text=The%20Async%20scope%20is%20a,processed%20without%20stopping%20the%20flow.
##########################################################
- This API is implemented by using below
	* Mule4
	* Runtime version 4.2.2
	* HTTP Listener
	* HTTP Requester
	* Async scope
	* JMS
##########################################################
- Getting started
	1) clone project 
	2) Import jar into anypoint studio 7 (mule 4)
	3) Make sure you'll get all files 
	4) Please install active mq and run (download: ActiveMQ 5 "Classic": https://activemq.apache.org/) 
	5) Start the active mq server in local and open it in browser by using: http://localhost:8161/ --> username and password is admin
	6) Right click the application and RUN in anypoint studio
	7) To execute the application: http://localhost:8081/flights/async
##########################################################

	- NOTE: If yoy don't have activemq, please use flie conenctor or you can delete jms



