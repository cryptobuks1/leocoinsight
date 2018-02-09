



## Prerequisites

* **Node.js v0.10.x** - Download and Install [Node.js](http://www.nodejs.org/download/).

* **NPM** - Node.js package manager, should be automatically installed when you get Node.js.


## Quick Install
  Check the Prerequisites section above before installing.

  To install LEOcoinsight, clone the main repository:

    $ git clone https:/github.com/newmight2015/leocoinsight.git && cd leocoinsight

  Install dependencies:

    $ npm install
    
  Run the main application:

    $ INSIGHT_NETWORK=livenet BITCOIND_USER=user BITCOIND_PASS=pass INSIGHT_PUBLIC_PATH=public  npm start
    
  Then open a browser and go to:

    http://localhost:3030
