+++
date = "2015-07-20T22:59:34-06:00"
title = "Ricochet"
+++

## Anonymous instant messaging for **real** privacy
Ricochet is a different approach to instant messaging that **doesn't trust anyone** in protecting your privacy.

* *Eliminate metadata*. Nobody should know who you talk to or what you say.
* *Stay anonymous*. Share what you want, without sharing your identity and location.
* *Nobody in the middle*. There are no central servers to monitor, censor, or compromise.
* *Safe by default*. Security isn't secure until it's automatic and easy to use.

### Get started

<div>
<a id="download-btn" href="/releases/1.1.0/Ricochet-1.1.0.exe"><i class="icon-download"></i> Windows</a>
<a id="download-btn" href="/releases/1.1.0/Ricochet-1.1.0.dmg"><i class="icon-download"></i> Mac</a>
<a id="download-btn" href="/releases/1.1.0/"><i class="icon-download"></i> Linux</a>
</div>

The latest version is **1.1.0** (April 10, 2015). You can also [build from source](https://github.com/ricochet-im/ricochet/blob/master/BUILDING.md).

### How it works

Ricochet is a peer-to-peer instant messaging system built on Tor [hidden services](https://www.torproject.org/docs/hidden-services.html.en).  Your login is your hidden service address, and contacts connect to you (not an intermediate server) through Tor. The rendezvous system makes it extremely hard for anyone to learn your identity from your address.

For more information, you can [read about Tor](https://www.torproject.org/about/overview.html.en) and [learn about Ricochet's design](https://github.com/ricochet-im/ricochet/blob/master/doc/design.md).

##### Metadata

Traditionally, instant messaging needs a server between you and and the people you talk to. That server is responsible for remembering your contacts, telling you when they're online, and forwarding your messages.

The server learns a lot about you - *who you are, who you talk to, when you're online*. We call this metadata. Without end-to-end encryption, it can also read content - *everything you say, and everything said to you*.

##### Anonymity


##### End-to-end


##### Usability

### How to help
Bugs and features should be discussed on the [issue tracker](https://github.com/ricochet-im/ricochet/issues). Translations can be contributed on [Transifex](https://www.transifex.com/projects/p/ricochet/). Patches are accepted and encouraged on GitHub or by email.

Ricochet is maintained by John Brooks, who can be reached at:

`ricochet:rs7ce36jsj24ogfw` or `john.brooks@dereferenced.net` (<a href="/john-brooks.asc">pgp</a>).

You should support [The Tor Project](https://www.torproject.org/donate/donate.html.en), [EFF](https://www.eff.org/), and [run a Tor relay](https://www.torproject.org/docs/tor-relay-debian.html.en).
