----------------------------------------------------------
# !!Major update has been released!!
---------------------------------------------------------
# bitminer
Automated mining of proof of work coins to gain Bitcoin rewards. As new blockchains emerge we see new ways to mine crypto. Our goal is to optimize the mining process using the highest mining yield for distribution to our miners. We have just recently added collision mining for solving puzzle transactions. We are currently working on Puzzle 120 and you can choose to enable collision mining. 

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
    
    
# Payments
To check the balance of your mining rewards you can visit this link  https://keymaker.cc/pool/?address. You can also see overall stats and further updates. 

 

![MiningPool](https://user-images.githubusercontent.com/13451926/153525311-82897f37-4e26-4793-af67-ff9a7a591eec.png)

