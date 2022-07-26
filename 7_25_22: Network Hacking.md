

### Network hacking

First let's talk about programming languages. One of the most important languages (maybe the best) for network hacking is Python. A lot of Network tools are written in Python and there is for beginner network hacking no way around learning it. Python has a lot of network libraries and you don't have to code everything on your own. Python is a very popular language and there are so many free courses. Just google for "learning python". When you've learned the basics you should focus on these libraries: requests, urllib, urllib2 ,socket, twisted and asyncore. For getting into these libraries you can try programming a small chat program between 2 computers via sockets, but still learn the basics first.

Here are some projects for beginners:

    Cracking Wifi: Have a look at aircrack-ng (https://github.com/aircrack-ng/aircrack-ng). It's a tool to crack wifi passwords via bruteforce (also have a look at F. (Offline) cracking / bruteforce). Follow this official tutorial to crack WPA / WPA2: https://www.aircrack-ng.org/doku.php?id=cracking_wpa
    Man in the middle: This attack is kind of ruined, because of encrypted traffic, but it's still useful to know it. Read about it: https://en.wikipedia.org/wiki/Man-in-the-middle_attack.
    nmap: nmap (https://nmap.org/) is a great network scanning tool and indispensable. You can e.g. scan ports of a server or just list all devices in your current network. But it's still just a scanning tool.
    Jammer / Fake AP: A jammer is something you can write on your own with just a little knowledge of python. This is a tutorial what it is and how to code one: https://www.shellvoide.com/python/how-to...am-python/ . But just jamming isn't very useful, maybe for fun, but you need a sence. Fluxion (https://github.com/FluxionNetwork/fluxion) is a tool to get the wifi password of wifis with a lot of users. It's a jammer, but after starting it, fluxion creates another wifi with the same name. 
    
    At e.g. a big motel some users will try your fake wifi, because youre jamming the real wifi, and you get the real password 
