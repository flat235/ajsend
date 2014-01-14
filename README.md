ajsend
======

Platform independent network file sending (complete rewrite of jlansend)

Pronunciation: Like "adjacent" (yes, pun intended ;)

Motivation:
Sending files between windows, macos x and linux is a pain, so I wrote [JLanSend](https://github.com/flat235/JLanSend).
That was pretty much hacked together in a couple of nights for personal use and as a proof of concept. Unfortunately people started using it, so let's do this right without reinventing every kind wheel.

Status: planning phase

Language: Java for reference implementation, of course any other projects are welcome as soon as protocols are decided.

Protocols to use:
 - zeroconf (avahi) / bonjour for discovery of other clients
 - xmpp for sending files?

Crypto:
 - is there a pgp lib for java?
 - ssl with self signed certs and company mode?

TODO:
 - please make me aware of any protocols better suited for this purpose
 - actually start coding ;)
