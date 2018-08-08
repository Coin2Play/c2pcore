Coin2Play Core
=====================

Setup
---------------------
[Coin2Play Core](http://coin2play.org/wallet) is the original Coin2Play client and it builds the backbone of the network. However, it downloads and stores the entire history of Coin2Play transactions; depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more. Thankfully you only have to do this once.

Running
---------------------
The following are some helpful notes on how to run Coin2Play on your native platform.

### Unix

Unpack the files into a directory and run:

- bin/32/coin2play-qt (GUI, 32-bit) or bin/32/coin2playd (headless, 32-bit)
- bin/64/coin2play-qt (GUI, 64-bit) or bin/64/coin2playd (headless, 64-bit)

### Windows

Unpack the files into a directory, and then run coin2play-qt.exe.

### OSX

Drag Coin2Play-Qt to your applications folder, and then run Coin2Play-Qt.

### Need Help?

* See the documentation at the [Coin2Play Wiki](https://en.bitcoin.it/wiki/Main_Page) ***TODO***
for help and more information.
* Ask for help on [BitcoinTalk](https://bitcointalk.org/index.php?topic=1262920.0) or on the [Coin2Play Forum](http://forum.coin2play.org/).
* Join one of our Slack groups [Coin2Play Slack Groups](https://coin2play.org/slack-logins/).

Building
---------------------
The following are developer notes on how to build Coin2Play on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [OSX Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The Coin2Play repo's [root README](https://github.com/Coin2Play-Project/Coin2Play/blob/master/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Multiwallet Qt Development](multiwallet-qt.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Source Code Documentation (External Link)](https://dev.visucore.com/bitcoin/doxygen/) ***TODO***
- [Translation Process](translation_process.md)
- [Unit Tests](unit-tests.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Dnsseed Policy](dnsseed-policy.md)

### Resources

* Discuss on the [BitcoinTalk](https://bitcointalk.org/index.php?topic=1262920.0) or the [Coin2Play](http://forum.coin2play.org/) forum.
* Join the [Coin2Play-Dev](https://coin2play-dev.slack.com/) Slack group ([Sign-Up](https://coin2play-dev.herokuapp.com/)).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)

License
---------------------
Distributed under the [MIT/X11 software license](http://www.opensource.org/licenses/mit-license.php).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
