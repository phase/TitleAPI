TitleAPI
========

A TitleAPI for Spigot, using 1.8 packets.

Using this API, you will be able to send the new titles, that were added to 1.8, to players.

How it might look:
```java
Title t = new Title("Title", "Optional Subtitle");
t.setTitle("A Different Title");
t.send(player);
```
