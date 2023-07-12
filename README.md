![Logo](https://cdn.discordapp.com/attachments/806974540139200623/1125722075206783078/image.png)
<br/>
*This project was completed under XROS Fellowship 2023.

## Table of Contents
- [How to start](#how-to-start)
- [Background](#background)
- [Technologies Used](#technologies-used)
- [Glimpse](#glimpse)
- [Features](#features)
- [Workflow](#workflow)
- [Research](#research)
- [Different Blockchains Available](#what-different-blockchains-are-available-for-minting)
- [NFT Minting](#nft-minting)
- [Augmented Reality](#integrating-with-ar)
- [Business Models]()
- [Challenges we faced](#challenges-we-ran-into)
- [Accomplisments](#accomplisments-we-are-proud-of)
- [What we learned](#what-we-learnt)
- [Contributors](#contributors)

## How to Start
1. Replace the metadata_urls.csv file by the file you minted.
2. In Index.html at Line 40, replace the link of the collection by your own.
![Html](https://cdn.discordapp.com/attachments/1105526288552296629/1128685106656182363/image.png)
3. There are two ways to start the project:
- Either go with Live Server
[Here is the link](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
- Use the following commands:
```
npm i serve
```
```
npx serve
```
## Background
**NFTs**
NFT stands for Non-Fungible Tokens. Non-Fungible stands for the uniqueness of these digital assets. Physical currency or even cryptocurrency is fungible but NFTs are not. They can neither be interchanged nor replaced. 
Here is an example of World's First NFT:
<br/>

![NFT](https://cdn.discordapp.com/attachments/806974540139200623/1125723640848195665/image.png)

**AR**
AR stands for Augmented reality.
It is an interactive experience that combines the real world and computer-generated content.
Here is an example of one of the world's first and most popular Augmented Reality Game,Pokemon Go:
<br/>

![AR](https://cdn.discordapp.com/attachments/806974540139200623/1125724124367560786/image.png)

## Technologies Used
Javascript and Solidity helping in mintings of NFTs on a blockchain. With Unity, we build a captivating augmented reality (AR) environment where users can interact with NFTs as if they were part of their real world. By integrating WebXR, users can easily access and enjoy the AR experience directly from their web browsers. Additionally, the NFTs featured in this project were minted on the Polygon Mumbai testnet, providing a reliable and efficient testing environment for our users

<p align="left">
<a href="https://nodejs.org/en" target="_blank" rel="noreferrer">
<img src="https://img.shields.io/badge/JavaScript-F7DF1E.svg?style=for-the-badge&logo=JavaScript&logoColor=black">
</a>
<a href="https://soliditylang.org/" target="_blank" rel="noreferrer">
<img src="https://img.shields.io/badge/Solidity-363636.svg?style=for-the-badge&logo=Solidity&logoColor=white">
</a>
<a href="https://threejs.org/" target="_blank" rel="noreferrer">
<img src="https://img.shields.io/badge/Three.js-000000.svg?style=for-the-badge&logo=threedotjs&logoColor=white">
</a>
<a href="https://unity.com/" target="_blank" rel="noreferrer">
<img src="https://img.shields.io/badge/Unity-FFFFFF.svg?style=for-the-badge&logo=Unity&logoColor=black">
</a>
<a href="https://aframe.io/ " target="_blank" rel="noreferrer">
<img src="https://img.shields.io/badge/AFrame-EF2D5E.svg?style=for-the-badge&logo=A-Frame&logoColor=white">
</a>
</p>

## Glimpse
![Screenshot1](https://cdn.discordapp.com/attachments/1105526288552296629/1128681253235855480/image.png)
![Screenshot2](https://cdn.discordapp.com/attachments/1105526288552296629/1128681305371062393/image.png)
## Features
- Real Time Display of NFTs in Augmented Reality
- Users can go through their collection without leaving augmented reality
- Users can buy/purchase/exchange NFTs in application.
- Application tracks the plane surface and then presents the NFT.

## Workflow
Here is the user's perspective of the product:
![Workflow](https://cdn.discordapp.com/attachments/1105526288552296629/1128679991899607050/Blank_diagram_34.png)

## Research 
**How did NFTs come into existence?**
In 2014, A guy’s wife made a video clip, he registered the video on a blockchain(Namecoin) and sold it to Dash for $4. They called it Monetized Graphics at that time.
In October 2015, the first NFT Project, Etheria was launched at Ethereum’s first developer conference, just 3 months after the launch of Ethereum. Soon ERC-721 was also proposed in 2017.
Later on, in early 2020, NFT Market saw rapid growth and wider usage.

**How do NFTs work?**
NFTs are individual tokens with valuable information in them, they reside on any blockchain. ( A Blockchain is nothing but a public ledger that holds information about transactions.) Their unique data makes it easier to verify, validate or transfer ownership. When anyone purchases an NFT, they buy a piece of data that points to a server that hosts that image or digital asset.

NFTs are created by a process called minting, which basically involves the creation of a block, validating the information, recording it on blockchain and closing the block.As tokens are minted, they are assigned a unique identifier address that is linked to exactly one blockchain address. Each token has an owner and a unique identifier through which it can be distinguished from others.

**What is the easiest way to create an NFT?**
As tokens are minted, they are assigned a unique identifier address that is linked to exactly one blockchain address. Each token has an owner and a unique identifier through which it can be distinguished from others.

**How an NFT becomes valuable/ why would you buy an NFT**
Most people who buy NFT’s see them as collectables in the investment category.
An NFT generally becomes valuable in the following cases

- First Effect: Just as bitcoin is so popular because it was the first cryptocurrency, the first NFT’s of certain creators or businesses hold a value. E.g. The pokemon cards created in the first edition are much more valuable than any other cards.
- Utility: When an NFT provides real world benefit, it becomes valuable for example the most recent case of Starbucks Odyssey where its users are getting special benefits from Starbucks.
- Uniqueness and Rarity: Let's take the example of Mona Lisa. Anybody can own a copy of Mona Lisa but only one person or museum can hang up the real painting. We can say the same for the original constitution of India or a bat signed by Mahendra Dhoni. Imagine if Stepen Hawking minted only three NFT’s. Those would be very valuable because they are the limited originals.
- Ownership History: When a mere gum chewed by Robert Downey Jr. can be auctioned for over 40,000$ , why can’t a simple NFT owned by a celebrity previously become valuable.
- Memes: Memes have brought a huge impact in the cryptocurrency world. From dogecoin to the newest Pepe coin, they have disrupted the market. Similar things have happened with NFT’s of famous memes.

**How to buy an NFT**
There are some key items that we need to acquire before starting our own NFT collection.

First, we need a digital wallet(like Metamask, AlphaWallet tc.) that allows us to store NFTs and cryptocurrency. Then we need to purchase some cryptocurrency, like Ether or Sol, depending on the currency our NFT provider accepts. This can be done using a crest card on platforms like CoinBase, Kraken and even PayPal now.

**What are Popular NFT Marketplaces**
Once we get our wallet setup and funded, there are tonnes of NFT sites to choose from.
Currently the largest NFT marketplaces are:

- OpenSea
- Rarible
- Foundation
- NFTically

**Are there any rules governing the sale and purchase of NFTs**
Currently there are no rules specifically governing the commercial trading in NFTs in India.The only statutory reference is the updated version of Income Tax Act,1961, which now includes NFTs as virtual digital assets(VDAs) under its definition. As a result, 30% tax is applied to income from trading NFTs

**What is Augmented Reality and How can we use AR in our Project ?**
AR or Augmented Reality is a technology that overlays digital information on the physical world, enhancing our perception of reality. This digital information can take many forms, such as text, images, 3D models, or animations. AR has many applications, including gaming, education, marketing, and more. In this project, we aim to combine NFTs and AR to create an immersive experience for users to view and interact with their digital assets in a virtual space.

AR NFTs allow users to view their 3D NFTs in the form of augmented reality, which means that the digital asset can be superimposed on the real world through a mobile device's camera or other AR-enabled devices.

By using AR technology, the NFT can be viewed as a 3D object that can be explored from different angles and interacted with in various ways. This provides a more immersive and engaging experience for the user, as they can see the NFT in the context of their physical environment.

For example, if you own an AR NFT of a sculpture, you can use your mobile device's camera to scan a specific area in your home, and the NFT will appear as a 3D object in that space. You can then move around the object to view it from different angles and even take photos or videos of it in the real world.

AR NFTs enable users to experience their digital assets in a more interactive and engaging way, blurring the lines between the digital and physical worlds.

**What are AR NFTs?**
AR NFTs are digital assets that use AR technology to create an interactive experience for the viewer. Unlike traditional NFTs, AR NFTs can be experienced in a physical space, making them more immersive and valuable.

**Why AR NFTs are the next big thing?**
AR NFTs offer several advantages over traditional NFTs, such as:

- Enhanced interactivity: AR NFTs allow viewers to interact with the artwork, creating a more engaging experience.

- Increased value: AR NFTs can be experienced in the physical world, making them more valuable than traditional NFTs.

- Novelty: AR NFTs are still a relatively new concept, which makes them more appealing to collectors and investors.

**Purpose of Augmented Reality NFT’s**
- Augmented reality NFTs are a new type of digital collectibles that use augmented reality technology to create unique and interactive experiences for users.
- Traditional NFTs are static digital assets, while AR NFTs offer added value through their interactive and immersive nature.
- Augmented reality technology enhances the value and user experience of digital collectibles by enabling users to interact with them in a more engaging and dynamic way.
- Augmented reality NFTs have the potential to revolutionize the way we think about digital art and collectibles by creating new opportunities for artists and collectors alike.
- The popularity of NFTs is growing rapidly, and augmented reality NFTs are expected to become increasingly popular in the future.
- The development of augmented reality NFTs is an exciting new area of innovation in the digital collectibles space.
- Augmented reality NFTs may also have applications beyond the realm of art and collectibles, such as in the gaming and entertainment industries.
- The possibilities for augmented reality NFTs are virtually limitless, and their potential for creating new and exciting experiences for users is significant.



**What are the examples of popular AR NFTs?**
Examples of AR NFTs that have gained popularity, such as:

- The Bored Ape Yacht Club: A collection of 10,000 unique Bored Ape NFTs that can be displayed in AR using the Metaverse app.
- Rarible's AR NFT Marketplace: A marketplace that allows creators to sell AR NFTs that can be experienced through a mobile device.
- SuperRare's AR Gallery: An AR gallery that allows collectors to view and interact with SuperRare NFTs in a physical space.

**What are the challenges to adoption?**
Some challenges that AR NFTs face in terms of adoption, such as:

- Limited technology: AR technology is still developing, and not everyone has access to AR-enabled devices.
- Cost: Creating AR NFTs can be expensive, which may limit the number of creators who can afford to make them.
- Regulation: There is currently a lack of regulation around AR NFTs, which may create legal issues for creators and investors.

## What different blockchains are available for minting?
**Ethereum Blockchain**
Ethereum launched the first NFT Project, E+theria and soon created ERC-721.

ERC-721(Ethereum Request for Comments 721)  is a standard for representing ownership of NFT’s. It is more complex than other standards(such as ERC20) and is split across many smart contracts. (Smart Contracts are basically programs stored on a blockchain, they run automatically when their predefined conditions are met.)
ERC-721 differentiates different NFTs even from the same Smart Contract on the basis of time, rarity and  visuals. Woah  Visuals? 
All NFTs have a uint256 variable called TokenID. 
For any ERC-721 Contract, the pair contract address and TokenID must be unique globally.
Now Dapps have converters that take TokenID as an input and output the visuals of the beautiful NFTs.
ERC-721 also provides other functionalities such as transferring tokens, getting current token balance and also to search for the owner of a specific token and obviously, total supply of the token available on any network. Third Parties can even add some other functionalities such as approve an amount of a token from an account.
Once the ERC-721 Non-Fungible Token Contract is deployed it will keep track of the tokens created on Ethereum.

ERC-1155 was introduced by Ethereum in 2017, as an official smart contract standard for wide scale NFT adoption. The older token standards(ERC-721 or ERC20) require creation of new smart contracts for each new token, even if you want to transfer an existing token. ERC-1155 is a multi token standard that introduced multiple token transferring at once and saved tons on transaction costs. 
- Advantages:
Ethereum is one of the oldest and most established blockchain networks, and it has a robust and secure infrastructure that can support the creation and trading of NFTs.
Ethereum has a large and active user base, which can make it easier for NFT creators to reach a wide audience and find buyers for their NFTs.
Ethereum's support for smart contracts enables NFT creators to create complex and customizable NFTs that can include various features like royalties, unlockable content, and more.
Ethereum is a decentralized network, which means that NFT creators can create and trade NFTs without relying on a centralized intermediary like a marketplace or auction house.

- Disadvantages:
High transaction fees, which can make it expensive for NFT creators and buyers to create and trade NFTs on the network.
Ethereum's current infrastructure can only handle a limited number of transactions per second, which can lead to congestion and delays on the network during times of high traffic.
Ethereum's blockchain is transparent, which means that all transactions and data on the network are visible to anyone.
Creating and minting NFTs on Ethereum requires technical expertise and knowledge of the Solidity programming language, which can be a barrier to entry for some creators.

**Solana Blockchain**
Solana NFT’s differentiate from others as they use Rust for programming language(Not Solidity) and it has different token standard. 
In Solana, a ‘program’ (equivalent to Smart Contract in Ethereum) interacts with Accounts that are stored outside of the program. In other words, Data in Solana is stored outside of programs, in reusable and scalable models called ‘Accounts’. 
Solana uses a model of Mint Accounts and Token Accounts. Mint Account defines each type of token and Token Accounts store the number of tokens owned by individual accounts. The public key of each wallet points to an account in Solana that stores the amount of tokens owned by the wallet. An analogy with money printing machine to understand it in a better way:
<br/>
![Solana](https://cdn.discordapp.com/attachments/806974540139200623/1125770676813430798/image.png)

Solana has a token metadata program that attaches additional data to NFT’s. It achieves this using Program Derived Addresses that are derived from addresses of Mint Accounts. Program Derived Addresses are basically public keys that are derived from other public keys using some special algorithm.
- Gas Fees of Solana:
Solana is one of the cheapest and most efficient cryptocurrency networks on the market – for a single transaction on the Solana network, you can expect to pay about $0.000125. Since launch, Solana has had a fixed approach to transaction fees, with SOL gas fees per single transaction amounting to 0.000005 SOL.


- Advantages: 
High transaction speeds and low fees
Solana supports a large number of transactions, which can be important for NFT creators who want to reach a wide audience and handle high levels of demand.
Solana is compatible with the Ethereum Virtual Machine (EVM), which can make it easier for NFT creators to integrate with other blockchain networks.

- Disadvantages: 
Solana's consensus mechanism is based on Proof of History (PoH) and Proof of Stake (PoS), which rely on a set of validators to secure the network. If the validators were to act maliciously, it could potentially compromise the security of the network.
It may not have the same level of tooling and support as more established blockchain networks like Ethereum.
Solana does not have the same level of adoption or market reach as other blockchain networks like Ethereum. This could impact the perceived value or marketability of NFTs created on Solana.

**Polygon Blockchain**
Polygon is a Layer 2 scaling solution for the Ethereum network. It was designed to improve the scalability and usability of Ethereum by creating a more efficient and cost-effective infrastructure. It achieves this by utilizing a combination of Plasma chains and Ethereum sidechains.

- Advantages:
The ability of Polygon to handle a high volume of transactions while keeping fees low.
Polygon's Proof of Stake (PoS) consensus mechanism allows for faster and more cost-efficient transactions than Ethereum's Proof of Work (PoW) mechanism(before the merge).
Its compatibility with the Ethereum Virtual Machine (EVM)  allows developers to easily port their existing Ethereum-based applications to the Polygon network. This means that NFTs and other Ethereum-based assets can be easily migrated to Polygon, allowing creators to take advantage of its faster transaction times and lower fees.
Polygon supports some popular wallets and marketplaces which includes MetaMask, OpenSea, and Rarible.
Polygon has the potential to handle up to 65,000 transactions per second, whereas Ethereum can process only up to roughly 17 transactions per second.

- Disadvantages:
Polygon is a Layer 2 scaling solution that relies on a set of trusted validators to secure its network. While this approach offers faster transaction times and lower fees, if the validators were to collude or act maliciously, it could potentially compromise the security of the network.
High Demand can lead to slower transaction times and higher gas fees, which can impact the overall user experience for NFT creators and buyers.
Polygon is only compatible with the Ethereum Virtual Machine (EVM), it may not be as interoperable with other blockchain networks or systems.


## NFT Minting
**Pre-requisites**
- Download and Install Node.js.
- Download and Install Metamask.
- Receive Matic Tokens using Faucet.
- Copy your Private Key from your Metamask wallet.
- Install an IDE like Visual Studio Code with Solidity Extension enabled.

**Getting an API Key from NFT.Storage**
Hop on to NFT.Storage and login with your e-mail id. It will send a magic link to login and use it. After that go on to API-Keys on the navbar and create one for yourself.

**Setting up Workspace**
Installing Node.js Dependencies:
```
npm install hardhat @openzeppelin/contracts nft.storage dotenv @nomiclabs/hardhat-ethers
```
Initialising Hardhat:
```
npx hardhat
```
When it will prompt, choose Create an Empty hardhat.config.js

Now create a file .env and store your API-Key(from NFT-Storage) and Private Key(from Wallet) in the following format:
```
PRIVATE_KEY=”Your private key”. 
NFT_STORAGE_API_KEY="Your api key"
```

**Modify the Hardhat-config file to support Mumbai Testnet**
Import Modules for Hardhat integration with Ether.js Library and dotenv to retrieve data from the .env file(where we can store our API key and our private key).

Retrieve the private key from the environment using const{PRIVATE_KEY}=process.end;

Then in exports, we are specifying our network and its configurations, i.e. Configuring it to support Polygon Mumbai Testnet. Then some info for the solidity compiler.
```
/**
* @type import('hardhat/config').HardhatUserConfig
*/
require("@nomiclabs/hardhat-ethers");
require('dotenv').config();
const { PRIVATE_KEY } = process.env;
module.exports = {
  defaultNetwork: "PolygonMumbai",
  networks: {
    hardhat: {
    },
     PolygonMumbai: {
      url: "https://rpc-mumbai.maticvigil.com",
      accounts: [PRIVATE_KEY]
    }
  },
  solidity: {
    version: "0.8.12",
    settings: {
      optimizer: {
        enabled: true,
        runs: 200
      }
    }
  },
}
```
**Create Folders using mkdir command for keeping track of all files**
Try to create them using mkdir only, not manually. You can dodge a few errors just because of this change.
```
mkdir contracts assets scripts
```
The directory structure will look like this:
<br/>
![Directory](https://cdn.discordapp.com/attachments/806974540139200623/1125766718095110225/1jWFJIsHcA-EkokW-9bXWCA.png)

**Create a script: store-content.mjs in Scripts Directory.**
Import Required Modules: NFT-Storage, File and dotenv

Retrieve the value of API-KEY from .env.

Create an async function named store-asset, and inside it, create a new client to store NFT and its metadata.

Read the images using File and parse through our CSV files, and store them as attributes on IPFS.
```
dotenv.config()
import { NFTStorage, File } from "nft.storage"
import fs from 'fs'
import dotenv from 'dotenv'
import { parse } from 'csv-parse';
const API_KEY = process.env.NFT_STORAGE_API_KEY
const POKEMON_CSV_PATH = 'assets/pokemon_metadata.csv'
const POKEMON_PHOTO_PATH = 'assets/original_150_pokemon_photos/'

// Process CSV file
var parser = await parse({columns: true}, async function (err, records) {
    for (let index = 0; index < 50; index++) {
        var element = records[index]
        // Each row of the CSV represents a single Pokemon extract the
        // name, description, type, attack, defense, speed, and number.
        var name = element['Pokemon']
        var description = element['Description']
        var type = element['Type 1']
        var hp = element['HP']
        var attack = element['Attack']
        var defense = element['Defense']
        var speed = element['Speed']
        var number = element['Number']
        var picture = `${POKEMON_PHOTO_PATH}${number}.PNG`

        var attributes = createAttributes(type, hp, attack, defense, speed)
        // store the metadata for this Pokemon
        await storeAsset(name, description, attributes, picture)
    }
});

fs.createReadStream(POKEMON_CSV_PATH).pipe(parser);

function createAttributes(type, hp, attack, defense, speed){
    let type_attr = JSON.parse(`{ "trait_type": "Type", "value": "${type}" }`)
    let hp_attr = JSON.parse(`{ "trait_type": "HP", "value": ${hp} }`)
    let attack_attr = JSON.parse(`{ "trait_type": "Attack", "value": ${attack} }`)
    let defense_attr = JSON.parse(`{ "trait_type": "Defense", "value": ${defense} }`)
    let speed_attr = JSON.parse(`{ "trait_type": "Speed", "value": ${speed} }`)
    return [type_attr, hp_attr, attack_attr, defense_attr, speed_attr]
}

// Store metadata for one Pokemon on IPFS
async function storeAsset(name, description, attributes, picture_path) {
   const client = new NFTStorage({ token: API_KEY })
   const metadata = await client.store({
       name: `BlockchainBob ${name}`,
       description: description,
       attributes: attributes,
       image: new File(
           [await fs.promises.readFile(picture_path)],
           `${name}Photo.png`,
           { type: 'image/png' }
       ),
   })
   console.log(`${name}: ${metadata.url}`)
}
```
When we run it, we would be able to see its URL on the console. Run it using:
```
Node scripts/store-content.mjs
```
**Verify your NFTs**
Go to Opensea Testnets and connect your wallet. Bingo! You will find all your NFTs there.

## Integrating with AR
Integrating NFTs in AR involved overlaying digital assets onto the real world through an AR application. Users can select NFTs from their collection and view them as virtual objects in a real-world environment using their device's camera. We researched a lot about the tech stack involved for creating the AR web app and integrating NFTs to them. Finally, we came to a conclusion of using Three.js for 3D graphics, WebXR for AR experiences, JavaScript for logic, HTML/CSS for structure and styling, and potentially NFT APIs for metadata retrieval. This combination enabled a seamless and interactive integration of NFTs into augmented reality.


## Business Models
**Auctions**
Auctions are a popular business model for traditional NFTs, and they can also be used for AR NFTs. In an auction, collectors bid on AR NFTs, and the highest bidder gets to own the NFT.

To provide an example, let's say an artist creates an AR NFT of a digital artwork. They can then put the AR NFT up for auction on a platform that supports NFTs. Collectors who are interested in owning the AR NFT can place bids on the NFT, with the highest bidder winning the auction and becoming the new owner of the AR NFT.

The auction model can drive up the value of the AR NFT, as collectors compete to own a unique and valuable digital asset. Additionally, the auction model can provide an opportunity for the artist to earn a significant amount of money if the AR NFT sells for a high price.

**Limited editions**
Similar to traditional collectibles, AR NFTs can be sold as limited editions. This means that only a certain number of copies of the NFT will be sold, making them more valuable and exclusive.

For example, an artist might create an AR NFT of a digital artwork and decide to only sell 100 copies of the NFT. Once those 100 copies are sold, the AR NFT will no longer be available for purchase, making it a limited edition. Collectors who own one of the limited edition AR NFTs have a unique and valuable digital asset that only a select few can own.

The limited edition business model can create a sense of scarcity and exclusivity, which can drive up the value of the AR NFTs. Additionally, the limited edition business model can provide an opportunity for artists to earn a significant amount of money if the AR NFTs sell out.

**Subscription Services**
AR NFTs can be sold as part of a subscription service, where collectors pay a monthly fee to access a curated collection of AR NFTs.

For example, a company could create a service that offers subscribers a new AR NFT every month. The subscribers would pay a monthly fee, and in return, they would receive a new and unique AR NFT each month.

The subscription business model can provide a steady source of income for the company offering the service while providing collectors with a regular supply of new and exciting AR NFTs. Additionally, the subscription model can help build a community around the AR NFTs, as subscribers can connect and engage with each other around their shared love of the NFTs.

**Royalties**
Creators of AR NFTs can earn royalties every time their NFT is resold on a secondary market, providing a long-term revenue stream for the creator.

For example, an artist creates an AR NFT of a digital artwork and sells it for $100. If the collector who purchased the NFT decides to sell it for $1000 in the future, the artist could receive a percentage of the sale as a royalty fee. This means that the artist can continue to earn money from the sale of the NFT each time it changes hands.

The royalty business model can provide artists with a steady source of income from their digital assets, even after the initial sale. Additionally, the royalty business model can provide an incentive for artists to create high-quality and valuable AR NFTs, as they can continue to earn money from the NFTs' future sales.

**Sponsorship and Advertising**
Brands and businesses can sponsor or advertise within AR NFT experiences, providing a new way to reach audiences and generate revenue.

For example, a game developer could create a game that allows players to purchase AR NFTs that provide them with unique abilities or advantages. These NFTs could be sold for real money, with the game developer earning a profit from each sale.

The pay-to-win business model can provide a way for game developers to earn money from their games while providing players with a way to enhance their gameplay experience. However, this business model can also be controversial, as some players may feel that it is unfair to allow players to purchase advantages with real money.

**Gamification**
Game developers and publishers can create games that feature AR NFTs as collectibles that players can acquire and use within the game.

For example, a game might have a feature where players can collect unique weapons or characters in the form of AR NFTs. These NFTs could have different abilities or attributes that make them more valuable than other NFTs in the game. Players can trade or sell these NFTs on a secondary market, providing a new way to monetize the game.

In addition, game developers can also sell AR NFTs directly to players as a way to generate revenue. For instance, a game developer could sell exclusive AR NFTs through an in-game store, providing an opportunity for players to acquire rare and valuable items.

**Partnerships and Collaboration**
Creators can collaborate with other artists or brands to create unique AR NFT experiences, which can help to increase visibility and generate revenue.

For example, a company could create an AR NFT that features their logo or a 3D model of one of their products. This NFT could be distributed for free or sold for a low price, and when collectors view the NFT through an augmented reality app, they would see the company's logo or product appear in a 3D space.

The advertising business model can provide companies with a unique and engaging way to promote their products or services while also providing collectors with a valuable and interactive digital asset. Additionally, the advertising business model can provide a way for companies to reach new audiences and connect with customers in a more engaging way than traditional advertising methods.

## Challenges we ran into
In the beginning, we had no idea about NFTs. We had to do intensive research about the topic. We even discussed these issues with our mentor, and he guided us on where we should start and topics we should research about.
Secondly, we faced alot of issues while implementing the NFTs in AR. There were no tutorials available for WebXR, we had to solve those on our own, and gladly, we were able to do so.
## Accomplishments we are proud of
WE MINTED OUR FIRST NFT!!!
Then we minted it again in another format.
Then we minted it again on another platform.
Then we minted it again on a testnet.
Then we minted those in bulk.
Then we implemented those in AR.

## What we learnt
We learned so much about NFTs, Blockchain, ThreeJS, WebXR and AFrame.
We started our journey by learning ThreeJS and Aframe. We even created small projects to showcase what we learnt. Then we moved on to research on NFTs and Blockchain for our project. Soon we implemented it and integrated it with AR. 
The whole journey was a learning process.

## Contributors

**Mentor**
[Sarath Kumar Sir](https://www.linkedin.com/in/sarathkkumar-skr/)
<br/>
<div align="center">
<a href="https://github.com/deecodess" target="_blank" rel="noreferrer">
    <img src="https://cdn.discordapp.com/attachments/806974540139200623/1125774320405323786/1647243311230.png" width="161" height="185"/>
</a>
<a href="https://github.com/chiragsingh1711" target="_blank" rel="noreferrer">
    <img src="https://media.discordapp.net/attachments/806974540139200623/1125774247709659247/1674244759977.png?width=468&height=468" width="161" height="185"/>
</a>
<br/>
<p align="center">Deepanshi Sharma and  Chirag Singh </p>
</div>


