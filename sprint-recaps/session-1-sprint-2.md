# Session 1: Sprint 2

**Author(s):** @jakestandley#0001

**Sprint Period:** May 3rd, 2022 - May 16th, 2022

**Next Sprint Ends:** May 16th, 2022

## Quick Links <a href="#quick-links" id="quick-links"></a>

| [omgkirbydao Twitch](https://www.twitch.tv/omgkirbydao) | [omgkirbydao Twitter](https://twitter.com/omgkirbyDAO) | [omgkirbydao Discord](http://discord.com/invite/omgkirby) | [Download omgkirby NFT mp4/stems/wav](https://www.notables.co/gallery/omgkirby) |
| ------------------------------------------------------- | ------------------------------------------------------ | --------------------------------------------------------- | ------------------------------------------------------------------------------- |

## Overview <a href="#summary" id="summary"></a>

Session 1: Sprint 2 has been all about outreach, and marketing the omgkirbyDAO project outside the walls of our Discord. We've increased our emphasis on the "Community Funnel", which we've sketched a basic iteration of below. Our goals here are to:&#x20;

1. **draw in new members** to our community via external sources, such as Twitter Spaces
2. **reward active members** of our community via the Sakura Event
3. **reward active holders** via the omgkirby x sad alex airdrop
4. **empower active holders** to utilize the DAO treasury and take an active role in its development via the creation of Working Groups

{% embed url="https://www.figma.com/file/SCqCCU3pRXCDDqx41F2XCl/Test-funnel?node-id=0:1" %}
rough outline of our "Community Funnel"
{% endembed %}

I think defining this funnel is important to understand where we're succeeding and where we're not up to par when it comes to spreading our resources to support the Community. For example - just by glancing at the above diagram, it's easy to identify that we need a better hook to keep those who join the Discord but are not yet holders.&#x20;

In the future, I would like to tie some basic metrics to each of these tiers so we can understand

* how much are we spending to support this portion of the Community?
* how many Community members do we have in this portion of the Community (sans external)?
* how consistently are Community members staying engaged?

By performing this analysis, we should be able to better separate our marketing team, which should focus on **growing** the community with external outreach, and our community team, which should focus on **engagement** from Discord community -> working group members.&#x20;

I think by having these two teams granted their own resource pools & their own goals, we'll be able to keep coming up with cool new ways to spread the omgkirby brand. One of these is our new 24/7 radio station, which launched last week on YouTube!

{% embed url="https://www.youtube.com/watch?ab_channel=omgkirby&v=jZjzGeXbfCU" %}
Check out our new 24/7 YouTube Radio StationI
{% endembed %}

I'm excited to see where this phase of Community for the omgkirbyDAO can take us!

I apologize for a little bit of inside baseball, but as we continue to grow the DAO, I think it's super important to document everything we do - whether it succeeds or not. And on that note...



### "don't let me down" - omgkirby x sad alex

{% hint style="info" %}
This excerpt will live in [dont-let-me-down-airdrop.md](../nft-releases/dont-let-me-down-airdrop.md "mention") as a living document for future updates
{% endhint %}

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



### Sakura Event Update

I wanted to shout out **@Aurelian#7564** & **@totallybullish#1234** again this week for the **Sakura Event**. We've now given out 26 kirbies to the community leading up to the PFP mint!

With the event coming to an end in the next week or so, I'm excited to see what the community enjoyed most, and what we can do following the PFP drop with any new members that will be hopping into the Discord.



### Twitter Spaces

After some feedback from our Marketing Working Group during Sprint 1, we put a much bigger emphasis on Twitter Spaces during this sprint. We hosted two Twitter Spaces last week, each with >100 total listeners. Our guests included

* [OG Ron C](https://twitter.com/OGRONC)
* [sad alex](https://twitter.com/imsadalex)
* [Superf3st](https://twitter.com/SUPERF3ST)

discussing topics like onboarding artists into web3, how web3 can elevate music festivals & more. Shoutout to Community Member **@1owkey.eth#0711** for getting involved! Stay tuned to [omgkirbyDAO's twitter](https://twitter.com/omgkirbydao) for updates on our upcoming twitter spaces!



### Community Highlights

1. I want to give a quick shoutout to **@bab#1183** for always being active in the chat - they sometimes beat the mods to welcoming new community members, as well as helping us set up our Twitter Space this coming Friday (May 20th, 2022) with the mee6 NFT team!
2. Shoutout to **@Wesley Aster#7776** for taking the lead in the DAO Voting Working Group. Thanks to their help, we will be able to move on to evaluating the best voting strategies used across several DAOs - and ultimately publish our own quorum guidelines!

The community has been super active over the last few weeks! As the Session 1 Working Groups come to a close, I'm excited to see which Community Members pitch new WG ideas for Session 2 over the Summer!

## Proposals <a href="#proposals" id="proposals"></a>

Similar to last sprint, this sprint had minimal live votes. Each Working Group has their budget allotted - which is reviewed below. The team has been focused on preparing for the PFP launch. Once the PFPs launch, we can expect more DAO Voting.



## DAO Treasury update <a href="#treasury-update" id="treasury-update"></a>

Multisig Wallet Address: [ 0x7291cc605653a9FCfbceD63313156E654eAF259b](https://etherscan.io/address/0x7291cc605653a9fcfbced63313156e654eaf259b).

|     Description    | Amount (ETH) | Notes                  |
| :----------------: | :----------: | ---------------------- |
|   Start Treasury   |     96.98    |                        |
|                    |              |                        |
| Operating Expenses |    (1.10)    | Community Manager, Mod |
| Marketing Expenses |    (0.00)    |                        |
| DAO Album Expenses |    (0.62)    | Airdrop for holders    |
|                    |              |                        |
|   Final Treasury   |     95.26    |                        |

[You view the full breakdown in google sheets here!](https://docs.google.com/spreadsheets/d/1GgLyCajYvp8vfqGRnS2dKGfPSVU1aDGCPl6AxHY1NT4/edit?usp=sharing)

This sprint's expenses were primarily our Operating Expenses - Community Team pay. In addition, we incurred \~ 0.62ETH in gas fees for our airdrop of "don't let me down". These prices were inflated slightly due to the ETH selloff that occurred last week.

This sprint I built the update entirely using [Utopia Labs](https://www.utopialabs.com/) export! So now it should be much easier to see who is getting paid, and for what.

## Post Mortem <a href="#post-mortem" id="post-mortem"></a>

**Note:** Organized by [Working Group](../working-groups.md)

****[**Complex voting system established**](https://snapshot.org/#/omgkirby.eth/proposal/0x850d67f2a33766bcb51b5ff1efd24ba5492a65d61879088d8d55991d32bff43c) **by @lemondropkid#3159**

* _What was accomplished this sprint_
  * Had a WG meeting and finalized the scope of work for the rest of the session. Also got three new community polls in.
* _Did you achieve or fall behind your proposed goals - why?_
  * Fell behind on timeline pretty significantly. WG leader did not delegate the workload effectively.
*   _How will next sprint be different?_

    * We’re going to move forward with the community submissions we have now so that we are unblocked and can move on to the next parts of the project.



****[**Treasury Management**](https://snapshot.org/#/omgkirby.eth/proposal/0xc1b2c368d9b0a1743d4d7530d8cb2d9b3408bc8db85d53f2eaea9f5f72b44f65) **by @jakestandley#0001**

* _What was accomplished this sprint_
  * Launched a rough v0.1 of our [Treasury PowerBI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiYzgxMDUxYmEtYjMzOS00YmMyLTlmMGQtOWRkNzBiYWM1ZDU5IiwidCI6IjhkYTQ3YTBjLTEwNzUtNGNkNy1hNWRiLTAyYTEzNDI0MmIzZSIsImMiOjF9\&pageName=ReportSection). This queries from Etherscan at the moment, and is joining on txnHash to metadata we enter in Utopia Labs
  * We located some [basic metrics for the NFT collection](https://uniq.cx/collection/omgkirby-genesis) that are free to access for everyone
* _Did you achieve or fall behind your proposed goals - why?_
  * Definitely fell a bit behind our[ Sprint goals](https://airtable.com/shrTy5Awdb0JBjRfm). I had some work issues arise that burned a lot of my time last week.
  * In addition, I think scheduling and delegating technical tasks within a DAO is still an issue.
* _How will next sprint be different?_
  * Going to check in with the team again on the research front and see if we can better pick a handful of DAOs to talk to before the end of the week
  * Going to launch v0.2 of the PBI dashboard this week to gather team feedback



[**Organize Marketing Effort**](https://snapshot.org/#/omgkirby.eth/proposal/0x6ac2113a9b5a3916814efb02f6317e4399706939cc341df98f4d62df035592fd) **by @Aurelian#7564**

* _What was accomplished this sprint_
  * Still waiting on some numbers to come in , but overall discord retention has gone up, and we are trending toward the upside of membership growth. Twitter has grown by 1592 new followers, with impressions up nearly 7295%. The omgkirby account on opensea has been verified. We are working on a new batch of collabs, and finished an amazing collab with Sad Alex. We also have the 24/7 omgkirby live radio, which should over time, not only provide a space for future collabs, but bring new members and interest into the project.
* _Did you achieve or fall behind your proposed goals - why?_
  * Achieved, but would like to see more growth in the discord, and utilizing the growth from spaces.
* _How will next sprint be different?_
  *   This will be leading up to the drop itself, so I expect to see another large surge of new members, combined with the increasing traction gained as spaces and collabs become more prevalent. We will be shifting narrative to really show the music and web3 world that this is the place for rising artists to come and make their name in this space along with the communities that want to support, invest, and be a part of that process side by side with said artists.



****[**omgkirby creates a track with high-visibility artist feature**](https://snapshot.org/#/omgkirby.eth/proposal/0xe4dbf47ab59bcd48b7d28b7b73da17378369400829f9b81f98a3d8f76bb667ba) **by @jakestandley#0001**

* _What was accomplished this sprint_
  * omgkirby, the Artist, worked this week to complete the collaboration.
* _Did you achieve or fall behind your proposed goals - why?_
  * We are on target - there is a targeted release date in mind
* _How will next sprint be different?_
  * Hoping to announce more after the PFP drop!



[**omgkirbyDAO Album**](https://snapshot.org/#/omgkirby.eth/proposal/0xc774c5ec7271cac38a48acfdd186c0f59bdf7fe37e9401acecf2747f675ad6de) **by @kryptokid#6525**

* _What was accomplished this sprint_
  * We compiled our list of target artists and began initial reach out. We'll be collecting un-used vocal stems as well as providing certain artists instrumentals based off of the genesis collection.
* _Did you achieve or fall behind your proposed goals - why?_
  * The initial sprint goals were set on a far too accelerated timeline for something as complex as an album with potentially 20-30 people involved. We're continuing to push forward but have found the time frames set in the initial sprint were unrealistic.
* _How will next sprint be different?_
  * We will continue down the path we are on and build out the genesis omg kirby album, but it will be on a different timeline from the other WG sprints. The final sprint will still comprise of the "creation" phase of this album.



Based on the feedback above I have a few key takeaways:

1. We may need to agree on a better way to delegate work, and reward/incentivize those that volunteer to help directly.&#x20;
   1. Almost every working group this Sprint suffered from poor delegation, causing them to fall behind schedule a bit, as there is a single point of failure.
   2. Maybe creating a Vice-Lead, or a similar position, which has equal ability to make decisions or allocate resources if necessary, needs to be created for future sessions?

## Next Steps <a href="#next-steps" id="next-steps"></a>

1. Continuing our momentum on Twitter Spaces - especially leading into the PFP drop.
2. Need to come up with a better way to delegate & track work as a decentralized organization.
3. Draft & publish our first formal blog post on the omgkirby Mirror as a DAO

## Helpful Resources <a href="#helpful-resources" id="helpful-resources"></a>

1. [Dilutive DAOs: Building a Community in Perpetuity](https://m.mirror.xyz/Eb308XiSttfLIWWMq5tVZd6xswtUbVjEGngEBHezAEE)
2. [Is the Spotify Editorial Playlist Landscape Fair to Emerging Artists?](https://www.music-tomorrow.com/blog/is-spotify-editorial-playlist-landscape-fair-to-emerging-artists)
3. [The DAO Treasury Issue](https://mirror.xyz/stastny.eth/yLKqFv6vIwj\_nKLh8Pn20dXqJOCsZLkVzb2bzT-7Y08)

## Conclusion <a href="#conclusion" id="conclusion"></a>

Despite some slow down from the Working Groups due to busy leads - Sprint 2 went well. Between the airdrop, the 24/7 radio launch & some awesome work from the Community team - the community has been the more active than any period since the Mint. This sprint we'll be looking forward to:

* Report & recommendation for our DAO voting quorum
* Treasury Management Dashboard
* Ramp up in marketing leading up to the PFP launch
* & more!

Make sure you stay tuned to our Discord & twitter for more information. As always reach out to me (**@jakestandley#0001**) if you're ever looking to get more involved in the community!🌸&#x20;
