---

title: 🌉 fBOMB
grand_parent:
parent: 🌉 ElitenessOFT
has_children: false
nav_order:

---

# 🌉 $fBOMB token

{: .highlight }
fBOMB is not based on ElitenessOFT standard, but is deployed on newer chains as a clone of existing fBOMB v3 contracts written by MaxFlowO2. Despite the difference, fBOMB is still compatible through a custom adaptor with ElitenessOFT Bridge.

{: .highlight }
fBOMB has undergone 3 token migrations since its launch in January 2021. The rest of this article deals with the current (3rd) version only which is built on LayerZero based OFT infrastructure.

## Vital information

Key | Value
---- | ----
Name | fBOMB
Symbol | Fantom Bomb
Decimals | 18
Links | https://mclb.org


## Deployments

Chain               | EVM ID | LZ ID | Contract Address (Proxy)                  | Contract Address (Implementation)
------------------- | ------ | ---- | ------------------------------------------ | ------------------------------------------
Fantom Opera        |    250 |  112 | 0x74ccbe53f77b08632ce0cb91d3a545bf6b8e0979 |
Binance Smart Chain |     56 |  102 | 0x74ccbe53f77b08632ce0cb91d3a545bf6b8e0979 |
Optimism            |     10 |  111 | 0x74ccbe53f77b08632ce0cb91d3a545bf6b8e0979 |
Ethereum Mainnet    |      1 |  101 | 0x74ccbe53f77b08632ce0cb91d3a545bf6b8e0979 |
Arbitrum One        |  42161 |  110 | 0x74ccbe53f77b08632ce0cb91d3a545bf6b8e0979 |
Polygon Matic       |    137 |  109 | 0x74ccbe53f77b08632ce0cb91d3a545bf6b8e0979 |
Base                |   8453 |  184 | 0x74ccbe53f77b08632ce0cb91d3a545bf6b8e0979 |
Mantle              |   5000 |  181 | 0x74ccbe53f77b08632ce0cb91d3a545bf6b8e0979 |
Canto               |        |      | 0x74ccbe53f77b08632ce0cb91d3a545bf6b8e0979 |
Fantom Opera        |    250 |  112 | 0x74ccbe53f77b08632ce0cb91d3a545bf6b8e0979 |
Sonic               |    146 |  332 | 0xedf8b632b537d5993adb5e2e15882cd791c284cb | 0x807c19badabc848336fe0379bd659e4e4608542d
Avalanche C-chain   |  43114 |  106 | 0x5C09A9cE08C4B332Ef1CC5f7caDB1158C32767Ce |
HyperEVM            |    999 |  367 | 0xe1fb1bc7a6d1b067defe7f9ce01ab4b5c931803f | 0x06319b9fee9994d0ca6624146eaef3dfa6faa508
Berachain           |  80094 |  362 | 0xdf486980df72446a5eff76263efb2fa9391be136 | 0xFAB311FE3E3be4bB3fEd77257EE294Fb22Fa888b
Plasma              |   9745 |  383 | 0x19d0480022eaf3e4E25472efEA9eeba372c9F35f |
Abstract            |   2741 |  324 | 0x19d0480022eaf3e4E25472efEA9eeba372c9F35f |
MegaETH             |   4326 |  398 | 0x19d0480022eaf3e4e25472efea9eeba372c9f35f | 0x5c652a94c672f8f6d021417bb5ee75c322ecf1fc
Rise Mainnet        |   4153 |  401 | 0x | 0x
Robinhood           |   4663 |  416 | 0x19d0480022eaf3e4E25472efEA9eeba372c9F35f | 0x832497895f05100E53f42DFA8fC758B4866B183a



## Adding Robinhood

## 7 txs
do the function: `addTrustedRemote` on these chains:
- ethereum
- bsc
- poly
- arbi
- op
- fantom
- base
use these arguments on above 7 chains:
chainId = 416
remote = 0x19D0480022EAF3E4E25472EFEA9EEBA372C9F35F74CCBE53F77B08632CE0CB91D3A545BF6B8E0979

## 1 tx
do the function: `addTrustedRemote` on these chains:
- sonic
use these arguments on above chains:
chainId = 416
remote = 0x19D0480022EAF3E4E25472EFEA9EEBA372C9F35FEDF8B632B537D5993ADB5E2E15882CD791C284CB

## 3 txs
do the function: `acceptDeveloper` on these chains:
- robinhood

## 3 txs
do the function: `acceptOwner` on these chains:
- robinhood