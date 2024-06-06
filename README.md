# Reset-WireGuard-Peers-in-MikroTik
Mikrotik has a problem with Wireguard peers. Sometimes the peers don't connect to the server, but turning a peer off and on once solves the problem. In this script, according to the last handshake of the peer, if more than 10 minutes have passed, the peer will be turned off and on once.
