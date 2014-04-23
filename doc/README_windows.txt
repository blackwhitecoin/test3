
Copyright (c) 2013-2014 Blackwhitecoin Developers


Blackwhitecoin 0.3.0 BETA

Copyright (c) 2013-2014 Blackwhitecoin Developers
Copyright (c) 2013 NovaCoin Developers
Copyright (c) 2011-2012 Bitcoin Developers
Distributed under the MIT/X11 software license, see the accompanying
file license.txt or http://www.opensource.org/licenses/mit-license.php.
This product includes software developed by the OpenSSL Project for use in
the OpenSSL Toolkit (http://www.openssl.org/).  This product includes
cryptographic software written by Eric Young (eay@cryptsoft.com).


Intro
-----
Blackwhitecoin is a free open source project derived from NovaCoin, with
the goal of providing a long-term energy-efficient scrypt-based crypto-currency.
Built on the foundation of Bitcoin and NovaCoin, innovations such as proof-of-stake
help further advance the field of crypto-currency.

Setup
-----
After completing windows setup then run windows command line (cmd)
  cd daemon
  blackwhitecoind
You would need to create a configuration file blackwhitecoin.conf in the default
wallet directory. Grant access to blackwhitecoind.exe in anti-virus and firewall
applications if necessary.

The software automatically finds other nodes to connect to.  You can
enable Universal Plug and Play (UPnP) with your router/firewall
or forward port 

15814 (TCP) to your computer so you can receive
incoming connections.  Blackwhitecoin works without incoming connections,
but allowing incoming connections helps the Blackwhitecoin network.

Upgrade
-------
All you existing coins/transactions should be intact with the upgrade.
To upgrade first backup wallet
blackwhitecoind backupwallet <destination_backup_file>
Then shutdown blackwhitecoind by
blackwhitecoind stop
Start up the new blackwhitecoind.


See the documentation/wiki at the Blackwhitecoin site:
  http://blackwhitecoin.cc/
for help and more information.

