# Charity NFT

This repo contains a code of a contract that was created to help the victims of Russia-Ukraine conflict in 2022. We collect donations and deliver the funds to a Czech organization that covers the needs of those who suffered in the event.

## Details

We allow anyone to deposit the funds to the contract. The contract records donation and creates an NFT that keeps the details of the donation. To donate funds and receive the NFT send funds to [0x305FD7d0c0Df39c2eaFf6bbfe5f1652A11CB9412](https://explorer.callisto.network/address/0x305FD7d0c0Df39c2eaFf6bbfe5f1652A11CB9412/transactions) address and make sure to provide 400,000 GAS for the transaction.

Contract will accept any amount of CLO. The amount of donated funds will be recorded to `property 1` slot of the NFT:

![CharityNFT_amount](https://user-images.githubusercontent.com/26142412/156876934-77263e1b-51ca-456d-84a3-96a0aeeaa098.png)

The description will be recorded to `property 2` slot of the NFT:

![CharityNFT_text](https://user-images.githubusercontent.com/26142412/156876939-958a34fc-32fe-459d-910a-6edbf4063a02.png)

(`property 0` slot is allocated for user-generated content by standard. You can record your own data onto this NFTs.)

## Technical

Auction contract: 0x305FD7d0c0Df39c2eaFf6bbfe5f1652A11CB9412

NFT contract: 0x5bb63e6dd5106502f33ef24a871b7443b9705d94
