# SoulBound-Token -Sahil Pachlore


Step 1: Upload image/file on Pinata or nft.storage or any ipfs storage provider.

Step 2: Copy IPFS CID(contain identifier) will be generated for image/file , which is a unique value used to identify files stored on the IPFS network.

Step 3: Add MetaData, create a file with extension " .json" and add info related to NFts.

For Example : 

```
{
    "image": "https://ipfs.io/ipfs/your-ipfs-cid-id",
    "description":"Sahil Pachlore has sucessfully completed MBA Degree with 3 GPA",
    "attributes":[
        {
            "trait_type":"GPA",
            "value":3,
            "max_value":4
        },
        {
            "trait_type":"Major",
            "value":"MBA"


        }
    ]
}
```
Step 4: Repeat same Step 1 for MetaData file.

Step 5: Copy IPFS CID(contain identifier) will be generated for MetaData JSON file, which is a unique value used to identify files stored on the IPFS network.

Step 6: Open "https://remix.ethereum.org/"

Step 7: Create File name with extension " .sol" and use the above solidity Code.

Step 8: Deploy Contract from "Deploy and run transaction" section. Select the correct Wallet address.

Step 9: Use ```safeMint``` and enter the beneficiar wallet address and paste CID URI in ```uri``` part with following format ```ipfs/your-metadata-cid```. You will see your NFT to your OpenSea Account which will be Non-Transferable.

Step 10: Only thing can be done with NFT is To Burn it. To do this : In ```burn``` selection put value ```0``` and transact it, NFT will be burn.




