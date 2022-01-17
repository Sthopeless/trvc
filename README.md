# trvc

```
Backlog Rule1 1; 
Rule1 
 ON system#boot DO Baudrate 115200 ENDON
 ON TuyaReceived#Cmnd=43 DO SerialSend5 55aa002b0001042f ENDON
```
