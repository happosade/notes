# AWS and IPv6

We ended up in a situation where we were limited by the IP allocations provided to us previously.
Running out of usable IPv4 addresses was a pain and something needed to be done.

We bounced back and forth between different kind of solutions, like using GCNAT, having overlapping networks and not care at all about connectivity on IP level but with load balancers and whatnots.

All that time there was this mythical thing called IPv6, looming in the background, solving all the problems with addressing and connectivity. The only thing was that documentation was (and still is) quite poor on that. Rumors in back alleys tells me that ISPs are actually using it, but in devops-cloud-world this is more or less unheard of. Everything and everyone assuems `there is no place like 127.0.0.1` is a nice thing to print on your shirt.

This meme I stole from internet sums up how I feel about this now, though I still think we made right call on this one.
![We do this not because it is easy, but because we thought it would be easy](./resources/we-do-this.jpg)
