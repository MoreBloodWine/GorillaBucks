
GorillaBucks development tree

GorillaBucks is a PoS-based cryptocurrency.

GorillaBucks is dependent upon libsecp256k1.

Dynamic rewards
Block Spacing: 79 Seconds
Stake Minimum Age: 5 Hours

Port: 36480
RPC Port: 36482

GorillaBucks includes an Address Index feature, based on the address index API (searchrawtransactions RPC command) implemented in Bitcoin Core but modified implementation to work with the GorillaBucks codebase (PoS coins maintain a txindex by default for instance).

Initialize the Address Index By Running with -reindexaddr Command Line Argument.  It may take 10-15 minutes to build the initial index.


