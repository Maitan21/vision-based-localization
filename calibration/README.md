
1. make ChArUco Board
<pre>
g++ -o charucoboard charucoboard.cpp $(pkg-config opencv4 --cflags --libs)  

./charucoboard
</pre>

created <code>board.jpg</code>


2. calibrate
