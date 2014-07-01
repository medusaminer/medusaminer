Medusa Miner 0.1.0

======================
About Medusa Miner
======================
Medusa Miner is a lightweight multi-algorithm crypto coin miner, it has been designed to be an 'all in one' that supports GPU's and ASICS alike. 
This takes the confusion out of choosing a miner when you are new to the crypto currency world.

We are trying to make a full featured miner with your help and suggestions. If you have any suggestions please contact Archiwall on litecointalk.org or email medusaminer@gmx.co.uk

Open Source - This project will be going open source once we have reached version 1.0.0, the reason behind this is plagiarism, We have made software before and had it re-released under a different name at the early stages of development.
we want this miner to be complete before we release the source. I hope you can all understand this.

======================
Changes in 0.1.0
======================
+ Complete Rewrite of program for speed and stability.
+ 64-Bit Compatability
+ Support for medusa's own style config file. INI style - Recommended Use
+ Support for SGMiner/medusaminer Configs
+ More documentation (This has been lacking, sorry)
+ Full API
+ Support for Growl/Prowl/WSM/email to receive messages if hardware failure (Looking to add SMS to that list)

======================
Notes
======================
- Config File is pretty self explanatory, if you have any questions contact Archiwall on litecointalk.org or email medusaminer@gmx.co.uk

======================
API - Not Finished
======================

All API Requests are to be sent to the listening port using a GET request, an will be displayed in what format you chose in the config file

All Stats: http://127.0.0.1:7788/api/all
Temperature: http://127.0.0.1:7788/api/temperature
Hashrate: http://127.0.0.1:7788/api/hashrate
Shares: http://127.0.0.1:7788/api/shares
Settings: http://127.0.0.1:7788/api/settings
Messages: http://127.0.0.1:7788/api/messages
