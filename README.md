* First Docker build ````docker-compose build````
* Start container `````docker-compose up -d`````
* Open your OBS for transmit stream, in Settings / Stream, chose Custom put ```rtmp://localhost/show```, and in key put ````test````

Click in start streaming, fine, your OBS rightnow begin transmit, you can test via VLC open your rtmp, or http://localhost:8080/hls/test.m3u8

* Now for better, open in http://localhost and enjoy