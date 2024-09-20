# springboot-rabbitmq-microservices

## Run RabbitMQ Docker Image: 
docker run --rm -it -p 15672:15672 -p 5672:5672 rabbitmq:3.13.7-management

## Apache Kafka Vs RabbitMQ
#### When to use Kafka, and when to use RabbitMQ?
Well, both RabbitMQ and Apache Kafka are popular message brokers that can handle long-running tasks, 
but they have different design philosophies and use cases.

RabbitMQ is a traditional message broker that is optimized for reliability and ease of use. It supports multiple 
messaging protocols and provides features like message queuing, routing, and delivery guarantees. RabbitMQ is commonly 
used in enterprise environments for mission-critical applications that require high availability and fault tolerance.

Apache Kafka, on the other hand, is a distributed streaming platform that is optimized for scalability and high 
throughput. It is designed to handle large volumes of data in real time and supports features like event streaming, 
message replay, and distributed processing. Apache Kafka is commonly used for big data applications, IoT, 
and real-time analytics.

If your application requires high reliability and ease of use, RabbitMQ may be a better choice. 
If your application requires high scalability and real-time processing of large volumes of data, Apache Kafka may be 
a better choice.

It's also worth noting that there are other message brokers and streaming platforms available that may be better 
suited for your specific use case. It's important to evaluate your options carefully and choose the one that best meets 
your requirements.

![](/home/erick/Documents/Cursos/Udemy/SpringBoot3_Microservices/my_code/springboot-rabbitmq-microservices/order-service/src/main/resources/templates/Screenshot%20from%202024-09-20%2013-28-32.png)

