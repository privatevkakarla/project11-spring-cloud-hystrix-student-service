## Hystrix Circuit Breaker Pattern – Spring Cloud

* Learn to leverage the one of the Spring cloud Netflix stack component called Hystrix to implement circuit breaker while invoking underlying microservice. It is generally required to enable fault tolerance in the application where some underlying service is down/throwing error permanently, we need to fall back to different path of program execution automatically. This is related to distributed computing style of Eco system using lots of underlying Microservices. This is where circuit breaker pattern helps and Hystrix is an tool to build this circuit breaker.


* **Opening browser and type** http://localhost:9098/getSchoolDetails/abcschool

* Now we already know that School service is calling student service internally, and it is getting student details from that service. So if both the services are running, school service is displaying the data returned by student service as we have seen in the school service browser output above. This is CIRCUIT CLOSED State.


