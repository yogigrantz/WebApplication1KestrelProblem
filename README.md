# WebApplication1KestrelProblem

This is an out-of-the box Web application created with Visual zstudio 2019 - for .net core 3.0 Web application

When publishing this solution and try to run the executable, it raised a Kestrel error:

System.Net.Sockets.SocketException (10013): An attempt was made to access a socket in a way forbidden by its access permissions.
    at System.Net.Sockets.Socket.UpdateStatusAfterSocketErrorAndThrowException(SocketError error, String callerName) 
    at System.Net.Sockets.Socket.DoBind(EndPoint endPointSnapShot, SocketAddress socketAddress)
    at System.Net.Sockets.Socket.Bind(EndPoint localEP)
    at Microsoft.AspnetCore ..... ..... 
    
  This error screen came up really really fast, and then disappeared. I had to take a picture of it with my phone, and then retype here
