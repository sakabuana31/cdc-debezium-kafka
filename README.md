# kafka-stream-stock-market

<div id="header" align="center">
  <img src="https://media.giphy.com/media/Q2sOgtEhhUlxX4w6Ui/giphy.gif" width="200"/>
</div>

<div id="badges" align="center">
  <a href="https://www.linkedin.com/in/sakabuana31/">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" height="25px" alt="LinkedIn Badge"/>
  </a>
  <a href="mailto:sakabuana.pa@gmail.com">
  <img src="https://img.shields.io/badge/-Email-c14438?style=flat-square&logo=Gmail&logoColor=white" height="25px" alt="Email Badge">
  </a>
</div>

<h1 align="center">
  hey there
  <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="30px"/>
</h1>

### :dart: Goals :
> Using docker to running kafka stream stock market producer and consumer

### :newspaper: Documentation :
1. run `docker-compose up -d` kafka and zookeeper image container
2. create env and install requirements
3. use the first terminal and run `python3 producer-consumer/kafka_producer.py` python producer script to produces the message to the Kafka topic every 1 minutes
4. open second terminal and run `python3 producer-consumer/kafka_consumer.py` consumer producer script is subscribed to the topic and using a for loop we print details of the message
5. this image below is the output of both of producer and consumer terminal show kafka streaming data

    ![kafka-stream-stock-market.png](output/kafka-stream-stock-market.png)
