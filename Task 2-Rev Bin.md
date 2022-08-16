Task 2-Rev Bin
Initailly I used gidhra to see the C code from there I got to no about the function checkpassword check password function contained a checkRes function Which seems to contain password string of 30 charectors.
    I simply used gdb to disassemble checkres and if we observe our c code there we can see that a if statement checks whether number of veriables is less than 30 then it jumps to start again
      Means to get access granted result we just have to jump from there using jump in gdb and hence we get Access Granted!!!!!!
        (Finally)