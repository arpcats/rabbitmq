# rabbitmq
Project Testing

Tools need to Install
1. Erlang/OTP - otp_win64_25.0.4
2. RabbitMQ - rabbitmq-server-3.10.7

##### For .NET/C# client
###### Create Project Send
``````````````````````````````````````````
> dotnet new console --name Send
> mv Send/Program.cs Send/Send.cs
``````````````````````````````````````````
###### Create Project Receive
``````````````````````````````````````````
> dotnet new console --name Receive
> mv Receive/Program.cs Receive/Receive.cs
````````````````````````````````````````````````
###### Add the client dependency.
````````````````````````````````````````````````
> cd Send
> dotnet add package RabbitMQ.Client
> cd ../Receive
> dotnet add package RabbitMQ.Client
