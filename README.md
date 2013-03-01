#
# The NodeInfo hypehost command!
# Prereqs: IO::Socket::INET6
# apt-get install libio-socket-inet6-perl
# 

To use NodeInfo nameservers on the Hyperboria Network, simply add the 
following line to the top of your /etc/resolv.conf file:

nameserver fc5d:baa5:61fc:6ffd:9554:67f0:e290:7535

Provided perl is set with the above modules and doesn't throw an error,
from your cjdroute connected host.  So to get the hypehost name of your
currently running node, simply run:

hypehost

Conversely, to set your host (in most settings), you can run the command
like this:

hypehost some.host

If you have an advanced setup where you have multiple cjdroute nodes
running on the same machine, you might want to set the hypehost foreach of
your IP addresses.  hypehost allows you to set the hypehost for all of
your interfaces.

hypehost fc5d:baa5:61fc:6ffd:9554:67f0:e290:7535 some.host
hypehost fcd5:c432:affb:7e77:a754:74e0:5e98:12d3 some.other.host

Will set your hostname to "some.host". It also works in a way 

If you have any further questions, I'm in #cjdns on EFnet as Mikey_

