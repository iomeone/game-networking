# game-networking

A simple game-like networking program that uses client-side prediction and entity interpolation. The project is based on Valves description of basic networking for the Source engine, read [here](https://developer.valvesoftware.com/wiki/Source_Multiplayer_Networking).

Watch demo:
[http://youtu.be/52AQqD_kKPY](http://youtu.be/52AQqD_kKPY)

### Start server
Run in terminal:
```
./server 1024
```
### Start client(s)
Run in terminal:
```
./client localhost 1024 3d
```
### Controls
##### 3d-controls:
* W: Move forward
* S: Move backward
* A: Step left
* D: Step right
* Space: Move up
* Left ctrl: Move down
* Mouse look

##### 2d-controls:
* Move around with the arrow keys

##### Other:
* F1: Toggle debug mode
* F2: Toggle prediction and interpolation
* Escape: Quit
