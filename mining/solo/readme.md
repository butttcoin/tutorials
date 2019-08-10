## How to solo-mine 0xBUTT (ButtCoin) ?

This is a quick tutorial on how to mine 0xBUTT. Please be aware that 0xBUTT difficulty gets rapidly increased and it does not decrease in 3 years after the last mining award, or until 95% of the tokens are burned. If you find this how-to difficult to follow, chances are that you will get it wrong. Please DO NOT contact if something is not working. Instead, try figuring out why it didn’t work, since it is a straight-forward procedure.

1. You will need your graphic card installed for the GPU processing. If you don’t have it installed, please search for another tutorial, since it is beyond the scope of this how-to.

2. Go to SoliditySHA3Miner GitHub page, and locate the Latest Public Release (and click on it):
https://github.com/lwYeo/SoliditySHA3Miner

![Alt text](https://raw.githubusercontent.com/butttcoin/tutorials/master/mining/solo/1.png?raw=true "SoliditySha3Miner")


3. Scroll down, and download the tar or zip file (tar if Linux-based, zip if Windows-based)

![Alt text](https://raw.githubusercontent.com/butttcoin/tutorials/master/mining/solo/2.png?raw=true "SoliditySha3Miner")


4. Extract the file to a folder of your choice.

5. If on Windows, edit “0xbtcSolo.bat” with your text-editor. With Linux, edit the “0xbtcSolo.sh”.

6.Change:

contract=0xB6eD7644C69416d67B522e20bC294A9a9B405B31
to
contract=0x7C1056ac0F7D223C4297e0c683453EE625011B1f

![Alt text](https://raw.githubusercontent.com/butttcoin/tutorials/master/mining/solo/3.png?raw=true "Config") 



7. You will also need to extract your private key of the ETH address from your wallet. To do that, simply search for another tutorials, depending on the wallet that you use.
Change:
privateKey=YOUR_ETH_PRIVATE_KEY
to
privateKey=WHATEVER_YOUR_PRIVATE_KEY_IS

8. At this point, you may want to save the file as 0xBUTTSolo.bat or .sh  However, if you can’t run, the common cause is that you need to go to infura.io, and register for an API address (for free). Furthermore, you may have to include ONLY the api key in the URL and not the other things such as “/v3/” you may need to change:
web3api=https://mainnet.infura.io/ANueYSYQTstCr2mFJjPE
to
web3api=https://mainnet.infura.io/SOME_OTHER_API_KEY

You can also try this key: 41c60ef6e74645238ca6aca9f99e9fc3 

9. Go to a command-line (or a shell) and go to a SoliditySHA3Miner’s root folder where all the .sh and .bat files are (including the one you saved, using a “cd” command). Then, for Windows, just type the 0xBUTTSolo and press enter. For Linux, simply type sh 0xBUTTSolo.sh and press enter.

10. If it doesn’t work, then some step was not done properly, or there is something else that is beyond the scope of this how-to.

11. You should also learn how to add 0xBUTT to your wallet, and if you can’t, simply search https://etherscan.io/  for your ETH address.

12. Depending on a difficulty, you will be given an estimate telling you how long until the right solution is found.  When solution is found, you will need to spend some Ethereum for a transaction of 0xBUTT to be processed. After that, you will be able to see the 0xBUTT in your wallet.

