<div align="center">

## Inter\-Process Communications


</div>

### Description

OK, we've all been in the situation where you want a multi tread application but since VB is single threaded it is difficult to do, so you create a second vb app and line the two together using winsock .... this is slow and you my be woring in a machine that does not have IP installed .... what choices do you have ..... well you can use pipes, winsock as i've already mentioned and you can also use Read/WriteProcess memory, these are time consuming and difficult to understand and write ..... but hey, what about SendMessage.... yep that good old API call. it allows you to send a data structure to an other process ..... which is fast and the message will always get there .... this code gives you a quick example of how to do this..... hope you fins this code useful ....

You may find that quitting the Client Application after you have sent the message wil cause your VB IDE to crash with a Memory exception .... if you click the control box on this form it might not crash the IDE ... this does not happen as an EXE
 
### More Info
 
You just need to enter your own text into the string variable that will be sent to the other process.

Assumes you are comfortable with the API (CopyMemory, SendMessage, FindWindow)

Sends a COPYDATASTRUCT to the target process

You may find that quitting the Client Application after you have sent the message wil cause your VB IDE to crash with a Memory exception .... if you click the control box on this form it might not crash the IDE ... this does not happen as an EXE


<span>             |<span>
---                |---
**Submitted On**   |2000-06-13 07:19:02
**By**             |[Roger D Taylor](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/roger-d-taylor.md)
**Level**          |Advanced
**User Rating**    |4.9 (79 globes from 16 users)
**Compatibility**  |VB 5\.0, VB 6\.0
**Category**       |[Windows API Call/ Explanation](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/windows-api-call-explanation__1-39.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[CODE\_UPLOAD67486132000\.zip](https://github.com/Planet-Source-Code/roger-d-taylor-inter-process-communications__1-8899/archive/master.zip)








