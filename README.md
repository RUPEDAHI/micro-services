# micro-services
Micro service with .Net Core and Docker

WHAT IS THE SOFTWARE REQUIRED FOR WINDOWS?
Windows 10 is required for Docker installation.
Visual Studio 2017 has built-in support for Docker, so this is highly recommended.
.NET Core SDK
Docker for Windows
Docker Tools

WHY SHOULD WE USE MICROSERVICES INSTEAD OF A MONOLITHIC APPROACH?
Microservices is an approach to develop small services that each run in its own process. We should develop microservices instead of one service (a monolithic approach) for a multitude of benefits, including:

Microservices are smaller in size
Microservices are easier to develop, deploy, and debug, because a fix only needs to be deployed onto the microservice with the bug, instead of across the board
Microservices can be scaled quickly and can be reused among different projects
Microservices work well with containers like Docker
Microservices are independent of each other, meaning that if one of the microservices goes down, there is little risk of the full application shutting down

WHY SHOULD WE USE .NET CORE?
.NET Core is a great development tool for many reasons, including that it’s open source and is very helpful in developing high-performance and scalable systems. It supports cross-platform runtime, so if you create a service using .NET Core, it can be run on any platform. .NET Core is also helpful for faster development, as well as supporting built-in dependency injection and a cloud-based environment configuration. .NET Core also has Docker support, though it’s important to note that it does not support SQL Server Version 2005.


WHY SHOULD WE USE DOCKER?
Docker is a tool that makes it easier to create, deploy, and run applications by using a containerization approach. These containers are lightweight and take less time to start than traditional servers. These containers also increase performance and lower cost, while offering proper resource management. Another benefit to using Docker is that you no longer need to pre-allocate RAM to each container.
