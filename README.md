
SOCKET.IO

socket io is a Bidirectional and low-latency communication for every platform

Today we know about intresting function and evnent on socket.io 

First need to know why we need socket.io is a open source for all we can use easliy and implemnt . socket io is more easyer then websocket

Why socket.io ? 
1.Real-Time communacation
2.Chat featurs 
3.Customerr support


let go deeep in to socket.io 


# First we need to know about emit,and on this is most use function or method in socket.io

when and why we use it 

# emit need to pass data front-end to backend or backend to front-end 

#Example in backend we pass welcome message 
  socket.emit("welcome" , " hello user ");

  # we recive this on front-end 
  #Example
   socket.on("welcome", (msg)=>{
   console.log(msg)
   }














