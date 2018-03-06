# ptremote
Telegram remote for Profit Trailer

## Description
This is a simple remote to be used with Profit Trailer, through Telegram. It is still under development, so please let me know of additional requests. 
Current features:
    - Pairs: It will show your current open pairs in PT with respective profit/loss
    - DCA: It will show your current DCA pairs in PT with respective profit/loss
    - Profit: It will give you both your total and daily profits in BTC (Note: due to PT limitations, the total profit is currently capped in days. A new version of PT Remote will fix this by storing the data locally.)


## Install instructions
1. Make sure you have python 2.7 installed
2. Install the requests module in python: Open a terminal, and type 'sudo easy_install -U requests'
3. Download ptremote
4. Open ptremote.properties and setup the following:
   - PTDIR - This  is the path to Profit Trailer. For example, if you put ptremote inside Profit Trailer, then define the path as ./
   - TOKEN and CHATID - these are the same telegram variables that you configured in Profit Trailer (if you didn't, please do so before using this)
      

## Running instructions
1. Open a terminal, go to ptremote directory and run it with 'python ptremote.pyc'
2. You will see a message popping up in your Telegram chat, with a set of buttons you can use
3. Press any of the buttons to remotely get the information from Profit Trailer
4. Enjoy!


## Contact and donations
Feel free to message me on Discord: @divmang

PT Remote is totally free to use, but if you like please consider donating:                                 
BTC - 3BLLiMwJ8eGTPGFAmuBEvpVNenqgrvctsJ                                                              
ETH - 0x77e7837a2463b2b76943e0cbe885c7cb3ce2b8a1                                                
LTC - MJdBKvH8RCwgsCo49468uvpKZsNNnwVLy8                                 
