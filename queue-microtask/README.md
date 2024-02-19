# [Test] Queue Microtask
Checks the time precision of queued Microtasks

## Prerequisites
1. Linux
1. Python 3

## How to run
1. Start python server on your PC with: python3 -m http.server 9000
1. Browse to: http://0.0.0.0:9000/
1. Run `ifconfig` and check your PC IP
   ![alt text](../docs/image.png)
1. On your smartphone connected to the same wifi network as your PC, browse to `http://TYPE_YOUR_PC_IP:9000/` (e.g. http://192.168.1.8:9000/)