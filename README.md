# Welcome to AptoStake validator profiles.
If you are an operator of a dPOS staking pool in Aptos network and want your details to be shown at [AptoStake staking portal](https://aptostake.guru/), please follow instrustions below to submit your data.

### How to add your validator info:
 - Create a `.json` file with name `$YOUR_POOL_ADDRESS.json` in `mainnet` or `testnet` folder according to where you want to setup your pool
 - Fill it out according to the [example.json](https://github.com/NodesGuru/aptos-validator-profiles/blob/main/mainnet/example.json):
 > :warning: **If you are prefer to use aptos.names - leave the `name` field empty!**
 ```
 {
   "name":"Nodes.Guru",
   "description":"ENTERPRISE SECURITY NON-CUSTODIAL STAKING\nStake your assets with the most reliable node runners! Nodes.Guru Staking offers high-uptime, secure staking, monitoringwith our own software, support & expertise",
   "icon":"https://s3.amazonaws.com/keybase_processed_uploads/25738b36b7972b94112bc8dc0df13b05_360_360.jpg",
   "socials": {
      "website":"https://stake.nodes.guru/",
      "github": "https://github.com/nodesguru",
      "twitter": "https://twitter.com/NodesGuru",
      "telegram": "https://t.me/NodesGuruStake",
      "discord": ""
   }
}
 ```
 - Create a pull request with your data

After that we will be able to verify your submission and approve it to be shown at the [staking portal](https://aptostake.guru/).
