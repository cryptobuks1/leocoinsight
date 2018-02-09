



## Prerequisites

* **Node.js v0.10.45** - Download and Install [Node.js](http://www.nodejs.org/download/).

* **NPM** - Node.js package manager, should be automatically installed when you get Node.js.
## Change for your altcoin
   First:
   https://github.com/newmight2015/leocoinsight-api/commit/185e27a2c99175f43543567d29d7d20f36e0ff3b
   Then:
   https://github.com/newmight2015/leocoincore/commit/7bbbc174b6ca8a6110a1adddf566ef549e1e251d
   
   note: hex of hash and merkle_root convert for example on ubuntu cmd line:
   echo -n '00000b486d79051b82d3d843550fb893bf605005f098877c4a911f1f58dfd5ca' | dd conv=swab | rev
   out:
   cad5df581f1f914a7c8798f0055060bf93b80f5543d8d3821b05796d480b0000
   
## Quick Install
  Check the Prerequisites section above before installing.

  To install LEOcoinsight, clone the main repository:

    $ git clone https:/github.com/newmight2015/leocoinsight.git && cd leocoinsight

  Install dependencies:

    $ npm install
    
  Run the main application:

    $ INSIGHT_NETWORK=livenet BITCOIND_USER=user BITCOIND_PASS=pass INSIGHT_PUBLIC_PATH=public  npm start
  or use start.sh for start
    export INSIGHT_NETWORK=livenet
    export BITCOIND_USER=user
    export BITCOIND_PASS=123
    export BITCOIND_P2P_PORT=port
    export BITCOIND_DATADIR=~/.yourcoin
    export BITCOIND_PORT=rpcport
    export NODE_ENV=production
    export INSIGHT_PORT=3000
    export INSIGHT_PUBLIC_PATH=public
    export INSIGHT_FORCE_RPC_SYNC=1
  Then open a browser and go to:

    http://localhost:3030
