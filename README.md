External repository for ION Core related maintenance tools.

check-dnsseeds
---------------

Sanity-check the DNS seeds used by ION Core.

Usage:

```bash
check-dnsseeds.py
```

Example output:

```bash
* Mainnet
OK   main.seeder.baseserv.com (24 results)
FAIL main.seeder.uksafedns.net

* Testnet
OK   testnet-seed.ion.mitchellcash.com (4 results)
FAIL testnet.seeder.baseserv.com
FAIL testnet.seeder.uksafedns.net
```
