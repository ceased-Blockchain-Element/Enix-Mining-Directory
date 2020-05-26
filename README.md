# Enix-Mining-Directory

## Enix Mining Directory Guide

Pool Link: https://enix.work/

- Pending Blocks https://enix.work/#/blocks
- Recent Payouts https://enix.work/#/payments
- Miners Online https://enix.work/#/miners
- About https://enix.work/#/about

Claymore: -wd 1 -r 1 -epool stratum+tcp://enix.work:8002 -ewal (Address) -eworker (Rig Name) -esm 0 -epsw x -allcoins 1 -asm 1

Phoenix Miner: -coin eth -pool enix.work:8002 -wal (Address) -rmode 2 -worker (Rig Name)

2 Billion: Stratum - 8002 / Proxy - 8802
4 Billion: Stratum - 8004 / Proxy - 8804
9 Billion: Stratum - 8009 / Proxy - 8809
12 Billion (Nice Hash): Stratum - 8012 / Proxy - 8812

## Introduction:

This guide will cover how to mine ENIX on a windows based system through the Claymore miner program. This guide will detail both the installation and setup process of the miner. 

## Hardware Requirements

- GPU 2 GB
- 100-300GB HDD

## Installation:
You can download the latest version of Claymore miner [here](https://bitcointalk.org/index.php?topic=1433925.0). or here (updated 11/10/2019) https://github.com/Enix-Blockchain-Element/ClaymoresDualMiners

Once downloaded, extract the folder to a suitable location on your computer. (Such as a mining folder or onto the desktop.)

> Be sure to check back frequently to get the latest version of the miner, as updates often  increase your hash rate, as the miner becomes better optimised. 

## Miner Setup: 

Within the extracted folder, right click on the start.bat file and edit with notepad.  (If a start.bat file is not present in the miner folder, simple create one by creating a new text document, and renaming it appropriately, including the file extension.)

Within this batch file, you can set the various parameters which the miner uses, including:

> Wallet address.

> Worker Name.

> Worker Password.

> Pool URL / Port. 

Below there is an example batch file, for more arguments / detail on setting up a batch file, please reference the bitcoin talk thread. There are also a number of useful youtube tutorials on the subject. 

```
setx GPU_FORCE_64BIT_PTR 0
setx GPU_MAX_HEAP_SIZE 100
setx GPU_USE_SYNC_OBJECTS 1
setx GPU_MAX_ALLOC_PERCENT 100
setx GPU_SINGLE_ALLOC_PERCENT 100

EthDcrMiner64.exe -epool stratum+tcp://enix.arhash.xyz:8002 -ewal (Address) -eworker (Rig Name) -esm 0 -epsw x -allcoins 1 -asm 1

pause
```

**Remember to save the batch file before closing it down, or you will lose your configuration information.**

## Exceptions:

Before running the batch file, it is best to check that the program has the correct permissions to run.  To do this, click on the  ethdcrminer64.exe file, go to properties, and ensure the tick box to "run program as administrator" is enabled.

## Running the Miner:

Once you have downloaded and configured the batch file you are now ready to mine! Double click on the batch file and the miner should start running! 

## Enix News can be found here: https://t.me/ENIXchainnews
## Enix CMC (CoinMarketCap) here: https://coinmarketcap.com/currencies/enix/

## Enix on Exchanges

South Africa and World Wide: https://asymetrex.com/markets/enixbtc (Excluding USA)


Wish to list Enix? 

Enix can seamlessly be added to your application or exchange/tracking solution by using the following information to interact with the Enix Blockchain.
Node Name: ENIX
URL: https://rpc.enix.ai
[[txhash]]: https://explorer.enix.ai/tx/[[txHash]]
Chain ID: 418
[[address]]: https://explorer.enix.ai/address/[[address]]
Port: 443

