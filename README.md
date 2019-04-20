# pretest-3
mqtt
```
npm install mqtt --save 
```

first create pubsub node.js

required for client 
```
var mqtt=require('mqtt');
```


Create conncetion broker
```
var client = mqtt.connect(url,options)
```

I use test.mosquitto.org for broker

client publish 
```
client.publish("testtopic", "test message")
```


for clien subscribe using  
```
client.subscribe((topic)
```


 create a listener 
 ```
 client.on('message')
 ```
 
