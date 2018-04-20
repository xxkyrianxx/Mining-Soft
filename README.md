# Auto_Mining_Script
Altcoin Auto_Mining_Script for Nvidia - Linux 

Welcome to the Auto-Mining-Script wiki!
Im not a programmer, just a blockchain lover, 
learning some programming.
I did this script to give my mining automation. Its works simple, atm its compare difficulty 7 days with difficulty 24 hours, if this is lower, the coins can be mined.

· Script Supports Linux - Nvidia (1050, 1060, 1070 and 1080 models)

· Coins Supported : ETH, ETC, XVG, ZEC, BTG, MUSIC

· Mining start can be Manual (you select the coin and just start mining it) or Auto ( you add coins by preference and script test difficulties and select which currency to mine. Script does this check every 8 hours.

· Script have added an Overclock script, Its support up to 12 GPUs, overclock values can be added manually or Auto. Values in Auto have been described at the beginning of the scrip.

· Miners : 

        Ethash - Claymore

        Equihash - Bminer and ZM Miner

        Others - Ccminer

        (You can use any Miner, just copy it to corresponding folder, and modify your "start" file to launch it.

· Tested in ubuntu 16.04

Requirements : 

        · Console Terminator
        
        · Jq package

Install : 

        · Download last Version.
        · Extract package
        · ./install

The Scripts are installed at /opt/Mining. Download you Miners, compile if needed and copy files to /opt/Mining/Miners/<ETH>(select the coin). Each coin have a executable file called "start", modify it with your address.. values.. workers.. etc.

To run the Script just write in console : "Mining" (for english version) or "Minar" (for spanish version) and enjoy it.



Working on :
      
        · Log to save starts and endings of each mined coin

        · Adds more coins, thinking about BSD and ZEN

        · Save the coin configuration in automatic mode and use it in later
        
        · Learning Python to port it to windows.

        · More improvements....
