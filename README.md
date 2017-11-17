# README

Based on Matt's work here: https://github.com/psychosophonis/truffledapps

This is just a repo to commit these dApp node JS projects in a complete format

First launch your local rinkeby node with something like:

`geth --networkid=4 --datadir=$HOME/.rinkeby --cache=512 --ethstats='yournode:Respect my authoritah!@stats.rinkeby.io' --rpc --unlock="YOUR_ACCOUNT_HASH_HERE" --bootnodes=enode://a24ac7c5484ef4ed0c5eb2d36620ba4e4aa13b8c84684e1b4aab0cebea2ae45cb4d375b77eab56516d34bfbd3c1a833fc51296ff084b770b94fb9028c4d25ccf@52.169.42.101:30303`

then cd into the project folder and `npm run dev` or on OSX double click the `run_node_app.command` file

then visit [http://localhost:8080](http://localhost:8080)
