+++
date = "2015-07-20T22:59:34-06:00"
title = "Ricochet"
+++

## Anonymous instant messaging for **real** privacy
Ricochet is a different approach to instant messaging that **doesn't trust anyone** in protecting your privacy.

* *Eliminate metadata*. Nobody knows who you are, who you talk to, or what you say.
* *Stay anonymous*. Share what you want, without sharing your identity and location.
* *Nobody in the middle*. There are no servers to monitor, censor, or hack.
* *Safe by default*. Security isn't secure until it's automatic and easy to use.


### Get started

<div>
<a id="download-btn" href="/releases/1.1.1/Ricochet-1.1.1.exe"><i class="icon-download"></i> Windows</a>
<a id="download-btn" href="/releases/1.1.1/Ricochet-1.1.1.dmg"><i class="icon-download"></i> Mac</a>
<a id="download-btn" href="/releases/1.1.1/"><i class="icon-download"></i> Linux</a>
</div>

The latest version is **1.1.1** (September 9, 2015). You can also [build from source](https://github.com/ricochet-im/ricochet/blob/master/BUILDING.md).

### How it works

Ricochet uses the [Tor network](https://www.torproject.org/about/overview.html.en) to reach your contacts without relying on messaging servers. It creates a [hidden service](https://www.torproject.org/docs/hidden-services.html.en), which is used to rendezvous with your contacts without revealing your location or IP address.

Instead of a username, you get a unique address that looks like `ricochet:rs7ce36jsj24ogfw`. <br>
Other Ricochet users can use this address to send a *contact request* - asking to be added to your contacts list.

You can see when your contacts are online, and send them messages (and soon, files!). Your list of contacts is only known to your computer - never exposed to servers or network traffic monitoring.

Everything is encrypted *end-to-end*, so only the intended recipient can decrypt it, and anonymized, so nobody knows where it's going and where it came from.

For more information, you can [read about Tor](https://www.torproject.org/about/overview.html.en) and learn more about [Ricochet's design](https://github.com/ricochet-im/ricochet/blob/master/doc/design.md).

### Be careful

Ricochet is an experiment. Security and anonymity are difficult topics, and you should carefully evaluate your risks and exposure with any software.

We're working on auditing, reviewing, and always improving Ricochet (and we'd love more help). There will be problems. We hope to do better than most, but please, *don't risk your safety* any more than necessary.

### How to help
Bugs and features should be discussed on the [issue tracker](https://github.com/ricochet-im/ricochet/issues). Translations can be contributed on [Transifex](https://www.transifex.com/projects/p/ricochet/). Patches are accepted and encouraged on GitHub or by email.

Ricochet is maintained by John Brooks, who can be reached at:

`ricochet:rs7ce36jsj24ogfw` or `john.brooks@dereferenced.net` ([pgp](/john-brooks.asc)).

You should support [The Tor Project](https://www.torproject.org/donate/donate.html.en), [EFF](https://www.eff.org/), and [run a Tor relay](https://www.torproject.org/docs/tor-relay-debian.html.en).
