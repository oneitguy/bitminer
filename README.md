# bitminer
Automated mining of pow and pos coins to gain Bitcoin rewards. As new blockchains emerge we see new ways to mine crypto. Our goal is to optimize the mining process using the highest mining yeild for distrbution to our miners. 

# Install

You can run bitminer in Windows or Linux. In order to run using Linux you have to download dotnet core 5.0.  
    
## For Linux or Windows

    $ wget https://github.com/oneitguy/bitminer/releases/download/latest/bitminer.tar
    $ tar -xf bitminer.tar
    $ dotnet bitminer.dll
    

## For Linux GPU

    You will need to compile the following applications, delete the .exe files found in the mine subfolder and create a symbolic link to each file in the mine folder with complied linux binary files.
    
    LOLMiner - https://github.com/Lolliedieb/lolMiner-releases/releases
    xmrig - https://github.com/xmrig/xmrig/releases/tag/v6.16.2
    
    symbolic link example
    ln -s [Source_File_Path] [Symbolic_Link_Path]


# Configure

To configure Bitminer you will need to designate a wallet address. The uid and pool url is automatically generated.
Example

    "worker": "123E3b27807B13f1c6... 82C7094C.worker1",
    "uid": "123E02E9B2A148...D",
    "pool": "https://keymaker.cc/pool"
