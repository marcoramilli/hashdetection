Hash Detection Tool Set
=====================

### Original Post
[Original Blog Post on the topic](http://marcoramilli.blogspot.it/search?q=hash+detector)

### Description
 Since 2009 when I wrote: "The string Decoding Process" (published by hakin9 magazine) I use crafted tools to automatically decode strings (some of them have been published on this blog). Decoding strings results pretty hard especially nowadays where many encoding algorithms are commonly used over planty "daily life tools". Understanding what encoding we are facing becomes really important if we are analyzing Hashing. Let's assume we 've just got a file including hundreds of different hash strings, how to identify what kind of hashing algorithm have been used ? Having a list o hashes, that potentially could "hide" passwords or important data, having  the power of a bruteforce machine and the right tools to attack the hash list without knowing what algorithm have been used could be pretty nesty for attackers. Indeed attackers might have difficult time in attacking hashes without knowing what is the generation algorithm. 

Surfing on this "painful wave" I decided to share a pretty python code that helped me out in solving this specific problem. The script can be downloaded here (pastebin). The following image shows how simple the script is, and how could be really easy to update it within new hashing algorithms. If you are planning to add new features to the script, please give me the diff file, so that we can create a more generic tool able to detect as many different hashing algorithms as possible.

![alt text](http://1.bp.blogspot.com/-Kmdb-9ewB3g/UcggFkaQLpI/AAAAAAAALZs/-_klPEWtV5I/s1600/Screen+Shot+2013-06-24+at+12.29.29+PM.png "Hashing functions")

Esaple python functions

![alt text]( http://4.bp.blogspot.com/-6wqJL6EL04E/UcgfQ-TET_I/AAAAAAAALZk/rSKTyeJwXqg/s1600/Screen+Shot+2013-06-24+at+12.27.25+PM.png "Example For extensions")

