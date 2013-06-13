topo-lite
=========

Extract AS topology from BGP view projects

- Repositories of BGP view projects:
    - [University of Oregon Route Views](http://archive.routeviews.org)
    - [RIPE RIS Raw Data](http://data.ris.ripe.net)
    - [PCH Route-Server RIB Dumps](https://www.pch.net/resources/data.php)
    - [Internet2 NOC BGP RIB Dumps](http://ndb7.net.internet2.edu/bgp)

- Notes
    - *Install* [a modified bgpdump](https://github.com/YuZhang/bgpdump-zy) (which fixes bugs and improves the performance).
    - Bogus ASN list from [IANA's as-numbers.txt](http://www.iana.org/assignments/as-numbers/as-numbers.txt) retrieved on 2013-05-24.
    - Don't worry about 32bit ASN. bgpdump and perl can handle it.

- Checklist for future maintainers
    - Is any URL to the repositories changed? See [this list of repos](tfiles.txt).     

