# RTL_433-console-table-view
I wrote a small script for the rtl_433 output on Linux that displays all received values in a table on the console. It can also create a logfile. New sensors appear at the top, older ones move downward, and if no packet has been received for a longer period, the color changes to grey.


Before running it, you need to install:

sudo apt install rtl-433 jq

simple copy the file

sudo chmod +x RTL433-view



be shure rtl_433 is installed an works :) 

<img width="1872" height="990" alt="Bildschirmfoto 2026-08-25 um 18 43 15" src="https://github.com/user-attachments/assets/b9e88193-5889-4146-bcb8-b5149dd4e37c" />
