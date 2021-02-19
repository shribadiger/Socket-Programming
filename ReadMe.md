# Network Programming in C #
-----------------------------
1) Host: In which applicaiton will run 
2) Router: It will forward the packets and maintain the forward information.
3) Packets: It is sequence of bytes transmitted over the layer and contains the control informations
4) Protocol: Set of rules and framework to decide the data representation in Network. eg: HTTP TCP UDP etc

## PROTOCOL Families ##
TCP/IP provides end-to-end connectivity specify the how data should be 
  * formatted
  * addressed
  * transmitted
  * routed
  * received at the destination
```flow
+--------+    +--------+     +---------+    +--------+
| Host A | -->| Router | --->| Rounter |--->| Host B |
+--------+    +--------+     +---------+    +--------+
```

