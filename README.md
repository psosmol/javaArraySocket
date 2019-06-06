# javaArraySocket
sending an array through a socket
I try to do a pong game to play in network. Two applications one client an another server. The server commands the ball and send the coordinates of the ball and the position of the racquet to the client in an array by mean of an array. And the problem is that the array values don't refresh, the values are the same always. I use the method writeObject(int[] m) and readObject()

I try to use ArrayList instead of an array, and Integer, but does't change the result. Aswell try to use a new class Message with variable members the coordinates of the ball and racquet, but is the same problem 
