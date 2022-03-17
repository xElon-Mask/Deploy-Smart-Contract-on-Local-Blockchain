# Deploy-Smart-Contract-on-Local-Blockchain


Here we use Ganache-cli to generate a local Ethereum blockchain; this will create several ETH accounts with 100 Ethers per account (unfortunately they are fake Ethers :o) )... Our blockchain is available on the localhost you see on the screenshot:

![ganache-cli_starter](https://user-images.githubusercontent.com/100287577/158903539-88c2c417-e9f7-463b-b7f7-4b3a527ac036.JPG)


With this, we will be able to deploy this smart contract on our local Ethereum blockchain; So we connect one of the previously generated accounts on our Metamask wallet :

![Metamask-connect-account-ganache-cli](https://user-images.githubusercontent.com/100287577/158903601-8e11e2d3-bfc3-431c-938a-961c505395b4.JPG)

All that remains is to deploy the contract from Remix, using Web3 injection to trigger the transaction on Metamask :

![deploy-depuis-remix](https://user-images.githubusercontent.com/100287577/158903888-2ff300b4-a680-4d07-b617-b01c107ae399.jpg)

Here the result, from Remix :

![deploy-termine](https://user-images.githubusercontent.com/100287577/158903905-25400dba-de7b-4aaf-bb6a-bbf340cadbfb.jpg)


and on Ganache-cli :



![SC-deploy-sur-mon-ganache-local](https://user-images.githubusercontent.com/100287577/158904056-43f95d40-8a55-422c-9bdd-16266941bc89.JPG)






