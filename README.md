# Introduction 
### You can edit the pool for IGO through edit the information in poolconfig.json. The information in this file will only change the data on the website but not change that of the contract, so you can edit many times.
# sample config

    {
           "poolContractAddress": "0xd6afb9afeeb10a5ac3b0015335e7d1f20c711979", (we will inform you in the group once the contract address is built,different pool has different contract addresses)
           "projectName": "Test Project", (project name)
           "logoUrl": "https://i.postimg.cc/MGt1ZcmM/melandai-1.jpg", 
           "poolName": "Guaranteed Pool", (It depends. It can be "Open to all" or "staker FCFS pool" etc.)
    
           "salePrice": "1MMETA = 0.5BUSD",
           "IGOStarts": "February 18th,2PM UTC", (UTC time)
           "IGOEnds": "February 18th,5PM UTC", (UTC time)
           "ClaimStarts": "February 22th,15:30PM UTC", (If we do airdrop then "TBA" here)
           "minPricePerToken": "3",  // (This line is only added for NFT project.This priceshould be divisible into hardcap and total supply. Once we add this line, users can only invest integer multiples for this price.Usually this line should be deleted.)
     
           "network": "BSC",  (fixed value)
           "stakeTokenName": "BUSD", (fixed value)
           "stakeTokenAddress": "0xe9e7cea3dedca5984780bafc599bd69add087d56",(fixed value)
           "earnTokenName": "DXS", (Project's token symbol)
           "earnTokenAddress": "0xbBBcB350C64Fe974e5C42A55c7070644191823f3", (If they do not have their token address then you write "TBA")
           "totalSupply": "100000000", (If the project hasn't decided we will write 100000000)
           "decimals": "18", (If the project hasn't decided we will write 18)
     
           "website": "https://duckie.land/", (Please do not omit the https://)
           "twitter": "https://twitter.com/duckienft",
           "telegram": "https://t.me/duckienft_global",
           "medium": "https://medium.com/@duckienft", (If they don't have medium this line can be delete or I will fill in the search result link)
     
           "isDisplayClaim": true, (if we take airdrop method, then here should be false)
           "isDisplayRefund": false, (fixed value since we delete this function)
           "tokenDistribution": "Claim", (if we take airdrop method,then here should be Airdrop)
           "hardCap": "50000", (It means the pool size)
           "accessType": "Whitelist", (Whitelist/Open to all)
     
           "earnTokenIntroduce": "Dx Spot is an application based crypto trading bot platform that can place trades 24",
           "earnTokenDetailText": "Dx Spot is an artificial intelligence (AI) trading platform for cryptocurrency exchanges, on the Playstore, it’s now possible to use and download.Dx Spot creates DXS Tokens for its ecosystem’s tools.In the metaverse, Dx Spot will also work on DeFi, NFT, Gamefi, and AI initiatives.DXS tokens can be used for membership fees, fuel gas top-ups, game character purchases, and staking in the Dx Spot application ecosystem.", 
           (pay attention that we should not make new line by ourselves for the description no matter how long it is. It will make new line automatically if it is too long.)
           "vestingSchedule": "20% at TGE, then unlock monthly for 4 months."
    }

# How to add a pool
![](https://cheersland.s3.ap-southeast-1.amazonaws.com/docs/cheersland+pic/cheersland.png)
Copy the text in the red box in the above picture and paste them to new line. Then make sure there is no "," at the end of "}". But don't forget to add a "," at the end of "}" of the previous pool every time you add a new one.
# How to edit/delete a pool
### 1. edit a pool: You can edit the information you want to edit under any title except for those fixed value.
### 2. delete pool: delete all the above information(Like the blue part from the pic above) of the pool you want to delete. 
# Some problems you may meet
### 1. Cannot see the new information after your edit: 
1. please wait for at least 2 minutes, and refresh the website.
2. Please make sure the pool contract address is correct.
3. please go to jsonlint.com to check whether the form of your added information is correct.
4. If still cannot solve the problem, please let us know.
### 2. Cannot see the new pool after you add a new pool:
1. please wait for at least 2 minutes, and refresh the website.
2. Please make sure the pool contract address is correct.
4. please go to jsonlint.com to check whether the form of your added information is correct.
5. If still cannot solve the problem, please let us know.
### 3. Still can see the pool after you delete the pool information
1. Make sure you have deleted the right information. And wait for at least 2minutes and refresh it.
2. If you made mistakes and want to find the previous information you can click the history button on the right corner to see your edit histroy.
3. If still cannot solve the problem, please let us know.
