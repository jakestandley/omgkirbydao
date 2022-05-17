# "don't let me down" airdrop

The DAO's first voted on collaboration song finally released last week - "don't let me down", with [sad alex](https://open.spotify.com/artist/3i8iJVU0mtgzbZsuF1AoJ3). First of all, the song itself is great, you can share it using [this link](https://omgkirby.lnk.to/sadalex) or stream it on Spotify below...

{% embed url="https://open.spotify.com/track/4vOFRTzty9ZNqq2YpIiClc?si=c2422a09f5d2443b" %}
Share "don't let me down" by omgkirby & sad alex!
{% endembed %}

In addition, the song has already broken 15,000 streams on Spotify alone - the DAOs biggest release so far on traditional DSPs! This is an **awesome** accomplishment that is just the start for 'decentralized' artists!

But the other important piece of this drop last week, was our free airdrop for all of the holders that joined our listening party on Twitter Spaces last Monday (May 9th, 2022)!  We had over **175 holders register for this free airdrop**, greater than 12% of our total unique holders! I think this is an awesome display of engagement for our community.

You can check out the listing for the token on [OpenSea here](https://opensea.io/collection/dont-let-me-down).&#x20;

The contract is: [0x249c052f0190f1e92b161c455843b26934bb04f2](https://etherscan.io/address/0x249c052f0190f1e92b161c455843b26934bb04f2).

#### How

* We hosted a listening party for "don't let me down" on Monday May 9th, 2022 on Twitter Spaces, and announced the airdrop during the broadcast
* We used an [irig](https://www.ikmultimedia.com/products/irigstreamsolo/) to play "don't let me down" during the Twitter Space
* We set up a premint that required the account to verify they held a Genesis omgkirby NFT, their Twitter username & their Discord username
* Created a test Manifold contract using [Manifold Studio](https://www.manifold.xyz/) and tested the airdrop on the [Rinkeby Testnet](https://medium.com/compound-finance/the-beginners-guide-to-using-an-ethereum-test-network-95bbbc85fc1d)
* Deployed the contract to Ethereum Mainnet
* We exported the csv of wallets from Premint on Wednesday May 11th, 2022 and [airdropped the token!](https://etherscan.io/address/0x249c052f0190f1e92b161c455843b26934bb04f2)

#### Why - Technical

* We used [Manifold Studio](https://www.manifold.xyz/) to deploy the contract, because it was my first time setting up a contract on the blockchain, and I wanted to ensure we didn't introduce any security issues
* [Manifold Studio](https://www.manifold.xyz/) was super easy to use, I can definitely recommend checking it out for simple drops, having now used it
* Manifold Studio currently offers two ERC token types you can use - ERC721 vs ERC1155
  * ERC721 is the more common token used for NFTs - these are easily queried on Etherscan, and show up as individual NFTs on storefronts such as OpenSea (ie: [the omgkirby Genesis Collection](https://opensea.io/collection/omgkirby-genesis)).
  * ERC1155 are the token typically used for 'editions.' Manifold Studio allows you to upload a CSV file with all of the addresses you would like to have the token airdropped to - making this the ideal format for our NFT.
  * An ERC721 airdrop/mint will also have a much higher gas fee than an ERC1155 from my research & testing.

#### Why - Functional

* We wanted to do something to commemorate the first omgkirbyDAO artist collab - and airdropping a full song felt fresh/new. Some projects mint full length songs ([Catalog](https://beta.catalog.works/), [Sound.xyz](https://www.sound.xyz/)), but we couldn't find a ton of examples of artists airdropping the full song prior to release.
* We used a premint signup to reduce the likelihood of community members feeling like they're spammed. By requiring Twitter username/Discord username, we were hoping to introduce friction so that people didn't spread their kirbies across xyz amount of wallets to dilute the drop.
* We did an airdrop, rather than a lazy mint, because it felt more novel. In addition - due to the market performance last week, it felt like a fun way to distract from the economics, and remind everyone what can be cool about the space.

#### Key Learnings/Next Steps

* We will continue to explore the positives and negatives of holder rewards/on-chain music like this as we go! I think we have to be less worried about some of these decisions - go with the path of least resistance and then evaluate the effectiveness after time has passed. There is so little documentation that exists concerning airdropping full length songs or how to keep the community of a music NFT project engaged. Hopefully this can serve to help.
* We want to set up a [dune ](https://dune.com/browse/dashboards)dashboard so we can track these tokens over time and see if they disperse as omgkirby or sad alex grow as artists. I will update this post once that query is live!
* We want to publish a short mirror article later this month, in collaboration with omgkirby & sad alex, on what it means to release music on-chain (especially for free, to fans!).

Ultimately, the goal here is to bring as much value as we can to existing holders, besides the upcoming PFP projects or anything that may follow. There are new & interesting ways we can interact with music on & off chain, and now it's our job to uncover those & see what the community enjoys the most!
