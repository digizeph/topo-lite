topo-lite
=========

extract AS topology from BGP view projects
- BGP view projects:
     - RouteViews
     - RIPE RIS
     - PCH

- MRT to plain txt
     - a modified bgpdump: hg clone https://bitbucket.org/dkhenry/bgpdump (the original bgpdump has bugs)
     - don't need unzip as bgpdump can handle uncompressed, gzip, and bz2 files
     - don't warry about 32bit ASN. bgpdump and perl can handle it.

- extractor
     - bogus ASN list from http://www.iana.org/assignments/as-numbers/as-numbers.txt retrived on 2013-05-24
