# Scheduler Micro Service
Scheduler micro service for distributed systems.

Depends on two other micro services:

  * Logging
  * Blob storage

The scheduler recieves *jobs* for calculation from *customers*. *Workers* process these jobs.
The scheduler implemens fair queue for customers. Each worker process one single job at time.
  
Current OpenAPI specification is: ![Is spec valid](http://grechka.family/swagger_validator_content_type_proxy.php?url=https://raw.githubusercontent.com/dgrechka/SchedulerMicroService/master/API.yaml "spec status")  

[Explore the API](http://editor.swagger.io/#/?import=https://raw.githubusercontent.com/dgrechka/SchedulerMicroService/master/API.yaml)
