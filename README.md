## Auction House private testing phase
First I'd like to thank the artists who agreed to help us with testing. The first phase of testing will be on tesnet. This allows you to create as many artworks and collections that you wish without worrying about duplicates or fees.

## What you get out of this
We really appreciate you testing the platform. You'll get a chance to familiarize yourself with the platform before others. Also in the next phase, you'll get a chance to test the verification process and get verified before others.

## Features to test
- Create artworks
  - You can mint as many artworks as you wish but please avoid minting more than 30 in one go
- One of the main features to test is collections. Here are a few notes:
  - Collections you see on other marketplaces such as SkyHarbor, are not actually collections but rather a centralized database of related artworks.
  - Collections you create here, on the other hand, are on-chain (decentralized) and are actually tokens. Once you create your collection, you will receive its token in your wallet.
  - In order to mint artworks in your collection, you will need to have the collection token in your wallet. 
- Collection page
  - You can navigate to the collection page through the artwork page or the explore collecton page and see related information about that collection such as its artworks, auctions, etc. You can filter traits in the the collection page.
- Traits
  - When you are minting your artwork, you can add traits to it. There are a few types types of traits. Play with them and see how they work.
- Activitis
  - We have an activity page. You can see everything that is happening on the platform.
- Notifications
  - You'll receive notifications for anything that is related to your artworks.
- Artist page
  - You can navigate to the artist page through the artwork page and see related information about that artist such as their auctions, artworks, collections, etc.
- Auctions
  - We have a few types of listings. You should already be familiar with timed auctions. In addition to that, we have fixed price (just like SkyHarbor), and declining price auctions. In the declining price auctions, you set an initial price and a final price. The price will start at the initial price and will decline in the period of your auction until it reaches the final price.
  - You can start auctions for multiple artworks at once. Just select the artworks you want to list in your profile, and fill the information for the auction form. You can use the information you have entered for other artworks to fill the form for the next artwork. Just try it and you'll see.
- Explore Auction page
    - We have different sorting and filteres. Check them out.
- Artwork page:
  - You can see all information about the artwork, including its traits, creator, collection, history, etc.
- Search
  - You can search for artworks, collections, artists, etc.
- Others
  - There are a lot more details. Just play around and see what you can find. It's important to test all the features and see if they work as expected. If you find any bugs, please [report them](#report-bugs).

## Features not to test
There are a few things we can't test in this phase. Such as verification. We will test these in the next phase on the mainnet.

Overall, please note that you will find bugs and issues and things that don't work as expected. Please report them. We will fix them and test them again. We will keep doing this until we are sure that everything is working as expected.

## How to test
- You need the Nautilus wallet for testnet. This is different from the mainnet wallet you have.
- You may need another browser for that to avoid both of these wallets interfering with each other.
- Download the testnet version from [here](https://github.com/capt-nemo429/nautilus-wallet/releases/tag/v0.7.2)
- Then you can load it into your browser. You can find instructions [here](https://www.cnet.com/tech/services-and-software/how-to-install-chrome-extensions-manually/)
- Once you have the extension installed, create a new wallet and you are good to login to the platform.
- Start using the platform: https://auctionhouse-testnet-qa78f.ondigitalocean.app

## What kind of bugs to report
Anything! Including texts that can be improved. Things being slow. Things not working. Things that are confusing. Anything! At the same time, please avoid requesting new features for now. The goal is to get everything we have working properly.

## Report bugs
Here are some notes on how to report bugs:
- Create a new issue in the github repo
- Please include screenshots (or videos if needed and possible)
- Explain how the issue you encountered happened, the steps you took to get to that point and what you expected to happen.
- Our devs may ask you some clarifying questions. Please keep track of them and answer them.