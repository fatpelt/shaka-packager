UDP file options
^^^^^^^^^^^^^^^^

UDP file is of the form udp://ip:port[?options]. Here is the list of supported
options:

:reuse=0|1:

    Allow or disallow reusing UDP sockets.

:interface=<addr>:

    Multicast group interface address. Only the packets sent to this address are
    received. Default to "0.0.0.0" if not specified.

:source=<addr>:

    Multicast source ip address. Only the packets sent from this source address
    are received. Defaults to "0.0.0.0" if not specified.

:timeout=<microseconds>:

    UDP timeout in microseconds.
