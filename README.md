# SoulBound-Token


Step 1: Upload image/file on Pinata or nft.storage or any ipfs storage provider.

Step 2: Copy IPFS CID(contain identifier) will be generated,which is a unique value used to identify files stored on the IPFS network.

Step 3: Add MetaData, create a file with extension " .json" and add info related to NFts.
For Example : 

```
{
    "image": "https://ipfs.io/ipfs/your-ipfs-cid-id",
    "description":"Image of the Legendary Person in entire Universe - The JETHA-Man",
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


