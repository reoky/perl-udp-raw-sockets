# Perl UDP Raw Socket Example

The purpose of this repository is to provide a good starting point for Perl programmers who want to learn about the networking stack or raw socket programming in Perl. Hopefully this code will be helpful to you and your projects.

## Usefull Reasources

I found this PDF pocket guide that I found to be a valuable reference:
www.utdallas.edu/~cantrell/ee6345/pocketguide.pdf

A Perl TCP raw socket example by cleen (Perl Monks):
http://www.perlmonks.org/index.pl?node_id=17576

The IP and UDP fields (With detailed descriptions):
http://www.networksorcery.com/enp/protocol/ip.htm
http://www.networksorcery.com/enp/protocol/udp.htm


## Note about Checksums

There is currently a stub for the checksum sub, but something lower level seems to fill in the checksums for me. I'm not sure if it's the library, my kernel, or something else.