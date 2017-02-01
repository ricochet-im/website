+++
date = "2017-01-31T18:14:16-06:00"
title = "How to Verify Your Download"

+++

Once you've downloaded Ricochet, it's a good idea to **verify** your download. Doing this ensures that the file you downloaded is exactly the same as the one the Ricochet's developer, John Brooks, signed and uploaded.

---

## Mac

First, head over to [Ricochet's latest releases page](https://ricochet.im/releases/latest/). If you haven't already, download the DMG file. It will be called something like `ricochet-1.1.4.1-macos.dmg`. While you're there, also download the corresponding `.asc` file. For v. 1.1.4.1, the `.asc` file is `ricochet-1.1.4.1-macos.dmg.asc`. This is the digital signature file that Ricochet's developer, John Brooks, created when he uploaded this particular release of Ricochet. 

Ensure that both the `dmg` file and the `asc` file are in the same folder, like your Downloads folder.

### Using a GUI Application

First, download and install [GPG Suite](https://gpgtools.org/). 

In the folder where you have the `dmg` and `asc` files, right-click the `.asc` file and go to `Services` and click on `OpenPGP: Validate`. If the resulting pop-up screen says `Signed by John Brooks <john.brooks@dereferenced.net> (183C045D) - undefined trust` that means your download has not been tampered with since John signed it with his GPG key. 

### Using the Terminal

Navigate to the directory with the `dmg` and `asc` files-- if it's in your Downloads directory, run `cd ~/Downloads`. Now run `gpg2 --verify ricochet-1.1.4.1-macos.dmg.asc`, filling in the appropriate version. If the resulting output is:

```
gpg: Good signature from "John Brooks <john.brooks@dereferenced.net>" [unknown]
gpg: WARNING: This key is not certified with a trusted signature!
gpg:          There is no indication that the signature belongs to the owner.
Primary key fingerprint: 9032 CAE4 CBFA 933A 5A21  45D5 FF97 C53F 183C 045D
```

you're on the right track. Now compare the "Primary key fingerprint" with the fingerprint displayed on the [Ricochet GitHub README page](https://github.com/ricochet-im/ricochet#downloads). If they match, your downloaded `dmg` file has not been tampered with.


## Ubuntu/Linux

We're going to be using the Terminal.

First, head over to [Ricochet's latest releases page](https://ricochet.im/releases/latest/). If you haven't already, download the appropriate `tar.bz2` file. If you're running Linux on a 64-bit machine, you'll want the `linux-x86_64.tar.bz2` file. If 32-bit, go for `linux-i686.tar.bz2`.

While you're there, also download the corresponding `.asc` file. It'll have the same file name as the `tar.bz2` file you downloaded, except with `.asc` at the end. This is the digital signature file that Ricochet's developer, John Brooks, created when he uploaded this particular release of Ricochet. 

Ensure that both the `tar.bz2` file and the `asc` file are in the same folder, like your Downloads folder. Navigate to this directory in your Terminal (if it's in your Downloads directory, run `cd ~/Downloads`). Now run `gpg2 --verify ricochet-1.X.X-linux-XXXXX.tar.bz2.asc`, filling in your version for the Xs. If the resulting output is:

```
gpg: Good signature from "John Brooks <john.brooks@dereferenced.net>" [unknown]
gpg: WARNING: This key is not certified with a trusted signature!
gpg:          There is no indication that the signature belongs to the owner.
Primary key fingerprint: 9032 CAE4 CBFA 933A 5A21  45D5 FF97 C53F 183C 045D
```

you're on the right track. Now compare the "Primary key fingerprint" with the fingerprint displayed on the [Ricochet GitHub README page](https://github.com/ricochet-im/ricochet#downloads). If they match, your downloaded `tar.bz2` file has not been tampered with.
