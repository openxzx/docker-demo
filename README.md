# docker-demo

Docker learning. 

## Software Architecture Diagram

	((( Y )))
	    |
	    |
	+- -|- - - - - - - - - - - - -+        xxxxxxxxxxxx          +--------+
	|+--+-----------+     +------+|       xx x  x     xxx        |        |
	||              | USB |      ||      xx  Internet  xx        |        |
	|| Concentrator |<----+ Host |<------xx     or    xx-------->|        |
	||              | SPI |      ||      xx  Intranet  xx        | Server |
	|+--------------+     +------+|       xxxx   x   xxxx        |        |
	|   ^                    ^    |           xxxxxxxx           |        |
	|   | PPS  +-----+  NMEA |    |                              |        |
	|   +------| GPS |-------+    |                              +--------+
	|          +-----+            |
	|                             |
	|            Gateway          |
	+- - - - - - - - - - - - - - -+
