# raspberry-shake-mini-project
analysis on Raspberry shake

# college shake IP:
http://10.70.12.119/heli/
the data is being sent to port 8888
tasks required is to debug the script to figure out why the graph is not being plotted
# accessing shake
http://localhost:8000/tree/shake-UDP-live

# UDP reference:
https://manual.raspberryshake.org/udp.html#udp

# Script for initial graph view:
https://github.com/iannesbitt/shake-UDP-live
Need to debug the code for ligh, so that the graph is being displayed

# way to connect to shake:
ssh -L8000:Localhost:8888 myshake@10.70.12.119
then in the browser http://localhost:8000/tree/shake-UDP-live
