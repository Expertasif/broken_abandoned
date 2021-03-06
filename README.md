#Broken, Abandoned, and Forgotten Code

##Introduction

Check out http://shadow-file.blogspot.com for a  detailed series of articles on reverse engineering and exploiting Netgear SOHO routers.

This series of posts describes how abandoned, partially implemented functionality can be exploited to gain complete, persistent control of Netgear wireless routers.

In this series, I'll describe the process of specially crafting a malicious firmware image and a SOAP request in order to route around the many artifacts of incomplete implementation in order to gain persistent control of the router. I'll discuss reverse engineering the proper firmware header format, as well as the the improper one that will work with the broken code.


##What's this repository for?

Many of the installments in this series will feature code that aids in the various stages of reverse engineering and exploiting the target device. Each part of the series featuring new or updated code will have a corresponding folder here. If you clone this repo, you should be able to get the latest updates whenever a new part goes up on the blog just by doing a pull.

The directory for each part will contain everything that came before it. So, for example part\_12 is a superset of part\_11.

Here are the parts of the series published so far (not all installments have updated source code).

[part 1](http://shadow-file.blogspot.com/2015/04/abandoned-part-01.html)  
[part 2](http://shadow-file.blogspot.com/2015/04/abandoned-part-02.html)  
[part 3](http://shadow-file.blogspot.com/2015/05/abandoned-part-03.html)  
[part 4](http://shadow-file.blogspot.com/2015/05/abandoned-part-04.html)  
[part 5](http://shadow-file.blogspot.com/2015/05/abandoned-part-05.html)  
[part 6](http://shadow-file.blogspot.com/2015/05/abandoned-part-06.html)  
[part 7](http://shadow-file.blogspot.com/2015/06/abandoned-part-07.html)  
[part 8](http://shadow-file.blogspot.com/2015/06/abandoned-part-08.html)  
[part 9](http://shadow-file.blogspot.com/2015/06/abandoned-part-09.html)  
[part 10](http://shadow-file.blogspot.com/2015/07/abandoned-part-10.html)  
[part 11](http://shadow-file.blogspot.com/2015/07/abandoned-part-11.html)  
[part 12](http://shadow-file.blogspot.com/2015/09/abandoned-part-12.html)  
[part 13](http://shadow-file.blogspot.com/2015/10/abandoned-part-13.html)  
[part 14](http://shadow-file.blogspot.com/2015/11/abandoned-part-14.html)  


Note: you will require Bowcaster, which you can get [here](https://github.com/zcutlip/bowcaster).

