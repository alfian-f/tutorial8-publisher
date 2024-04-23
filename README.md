###  1. How many data your publlsher program will send to the message broker in one run?
the publisher program will send five pieces of data to the message broker in one run. 
1.  `UserCreatedEventMessage { user_id: "1", user_name: "2206821683-Amir" }`
2.  `UserCreatedEventMessage { user_id: "2", user_name: "2206821683-Budi" }`
3.  `UserCreatedEventMessage { user_id: "3", user_name: "2206821683-Cica" }`
4.  `UserCreatedEventMessage { user_id: "4", user_name: "2206821683-Dira" }`
5.  `UserCreatedEventMessage { user_id: "5", user_name: "2206821683-Emir" }`

### 2. The url of: “amqp://guest:guest@localhost:5672” is the same as in the subscriber program, what does it mean?
Both the publisher and the subscriber use the same message broker. This makes the messages sent by the publisher can be received by the subscriber because they are both connected to the same server.

## Screenshots
### Running RabbitMQ
![RabbitMQ page](assets/image1.png)

### Sending and processing event
![VSCode Terminal](assets/image2.png)

### Monitoring chart based on publisher
![VSCode Terminal](assets/image3.png)