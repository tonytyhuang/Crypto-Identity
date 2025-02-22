# Crypto Identity

Crypto Identity allows a user to create a digital identity that they can use whenever they need to provide identification. You first register for an account using an email and password and are then prompted to take some pictures of yourself doing various facial expressions. We used a facial recognition API that can detect various emotions, which allows us to verify the user is actually trying to sign up for an ID and not just using someone else's picture. From there, the user is prompted to fill out a form that contains all the information that will be on their ids such as their date of birth and gender. We made a conscious decision to make certain fields optional to accommodate people from all socio-economic backgrounds such as a phone number and mailing address. Our project is meant to be used in a sort of office setting where you would set up your account with the help of an employee in case you don't have access to the internet or a computer at home. 

Once all this information is gathered, the user receives a prompt from their digital crypto wallet that their identification is being minted as an NFT. Their personal NFT stores their first name. and an encrypted version of all the private information they filled out in the form. This encrypted data can only be decrypted on our specific platform, ensuring the user's information is secure. Since our NFT's are stored on a blockchain, the IDs would be widely available for employers, financial institutions, and government agencies to verify a user's information. It also reduces the likelihood of theft or forgery due to the secure nature of NFT's as well as the lack of a physical ID.



```
git clone https://github.com/YiJie-Zhu/IDs-as-NFT.git

//go to a general directory (not this folder's)]
npm install -g truffle

//go to folder directory
npm install

//After npm finish installing
truffle test

//if all test passes
truffle console

contract = await PersonId.deployed()

await contract.mint("Name1")

await contract.mint("Name2")

//ctlr-c 2 times

//get API key from fb chat and put in .env.local file in name directory

npm start


```
