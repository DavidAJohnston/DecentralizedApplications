The General Theory of Decentralized Applications "DApps"
===============================================

Table of Contents
-----------------

1.   Introduction
    1.  The emergence of decentralized applications
    2.  Definition of a decentralized application
    3.  Bitcoin as a decentralized application
    4.  Nomenclature and its importance
    5.  Classification of decentralized applications
2.   The operation of a decentralized application
    1.   Mechanisms for establishing consensus
    2.   Mechanisms for distributing tokens
    3.   Formation and development of a decentralized application
3.   The current state of type II and III decentralized applications
4.   Conclusion
4.   Appendix
    1.   DApp Best Practices
    2.   DApp Economic Model
    3.   DApp Legal Model 
    4.   A proposed metaphor for decentralized applications
    5.   Johnston's Law
    
Authors
------------
David Johnston, Sam Onat Yilmaz, Jeremy Kandah, Nikos Bentenitis, Farzad Hashemi, Ron Gross, Shawn Wilkinson and Steven Mason


Introduction
------------

### The emergence of decentralized applications

A new model for building successful and massively scalable applications
is emerging. Bitcoin led the way with its open-source, peer-to-peer
nature, cryptographically-stored records (block chain), and limited
number of tokens that power the use of its features. Several
[applications](https://en.bitcoin.it/wiki/List_of_Decentralized_Autonomous_Corporations)
are adopting the Bitcoin model in order to succeed.
[BitShares](https://docs.google.com/document/d/1RLcjSXWuU9vBJzzqLEXVACSCdn8zXKTTJRN_LfoCjNY/edit),
[Mastercoin](http://www.mastercoin.org/) and Open Garden are just a few of
those "decentralized applications" that use a variety of methods to
operate. Some use their own block chain (BitShares), some use existing
block chains and issue their own tokens (Master Protocol and
Mastercoin), and others operate at two layers above an existing block
chain and issue their own tokens (OpenGarden).

This paper describes why decentralized applications have the potential
to be immensely successful, how the different types of decentralized
applications can be classified, and introduces terminology that aims to
be accurate and helpful to the community. Finally, this paper postulates
that these decentralized applications will some day surpass the world’s
largest software corporations in utility, user-base, and network
valuation due to their superior incentivization structure, flexibility,
transparency, resiliency, and distributed nature.

### Definition of a decentralized application "DApp"

For an application to be considered a "DApp", it must meet the following
criteria:

1.  The application must be completely
    [open-source](https://en.wikipedia.org/wiki/Open_source), it must
    operate autonomously, with no entity controlling the majority of its
    tokens, and its data and records of operation must be
    cryptographically stored in a public, decentralized [block
    chain](https://en.bitcoin.it/wiki/Block_chain).

2.  The application must generate tokens according to a standard
    algorithm or set of criteria and possibly distribute some or all of
    its tokens at the beginning of its operation. These tokens must be
    necessary for the use of the application and any contribution from
    users should be rewarded by payment in the application's tokens.

3.  The application may adapt its protocol in response to proposed
    improvements and market feedback but all changes must be decided by
    majority consensus of its users.

### Bitcoin as a decentralized application

Satoshi Nakamoto, the creator of Bitcoin described his invention as “A
Peer-to-Peer Electronic Cash
System[[2]](https://dl.dropboxusercontent.com#ftnt2)”. Bitcoin has been
shown to effectively solve the problems that arise from a trustless and
scalable electronic cash system by using a peer-to-peer, distributed
ledger, the Bitcoin block chain. In addition to being a peer-to-peer
electronic cash system however, Bitcoin is also an application that users can interact with through computer software). But most importantly for the
purposes of this paper, based on the criteria outlined above, Bitcoin is
a decentralized application. Here is why:

1.  All Bitcoin software applications are open-source, no entity (government, company, or organization) controls Bitcoin and all records related to the use of Bitcoin are open and public.

2.  Bitcoin generates its tokens, the bitcoins, with a predetermined
    algorithm that cannot be changed, and those tokens are necessary for Bitcoin to function. Bitcoin miners are rewarded with bitcoins
    for their contributions in securing the Bitcoin network.

3.  All changes to Bitcoin must be approved by a majority consensus of
    its users through the proof-of-work mechanism.

### Nomenclature and its importance

Decentralized applications were initially described as Decentralized Autonomous Corporations, DAC, in an article written by Daniel Larimer of Invictus Innovations. This papers avoids the term corporation for two reasons.

First, because it carries with it unnecessary preconceptions. For instance, a corporation is established in a jurisdiction, it has shares, a CEO, employees, etc. DApps, like Bitcoin, have none of these characteristics. In addition, the narrative is very important for the way DApps are perceived by various nations and jurisdictions. The same way that governments struggle to learn and regulate Bitcoin because the concept of currency is associated with it, governments might be compelled to regulate an open-source computer program that is a decentralized application.

Second, because traditional corporations may engage in several techniques to raise capital (like selling shares of its stock and pay dividends or borrowing against its stock and pay interest) that a DApp does not need. The concept of a DApp is so powerful and elegant, because it does not include  these traditional corporate techniques. The ownership of the DApp's tokens is all that is required for the holder to use the system. It's that simple. The value of the tokens is determined by how much people value the application. All the incentives, all the monetization, all the ways to raise capital are built into this beautifully simple structure. DApps are not required to recreate the functions that used to be necessary in centralized
corporations in order to balance the power of shareholders and offer
returns for investors and employees.

### Classification of decentralized applications

There are several characteristics according to which decentralized
applications can be classified. For the purposes of this paper, we will
classify DApps based on whether they have their own block chain or they
use the block chain of another DApp. Based on this criterion, there
are three types of DApps.

**Type I** decentralized applications have their own block chain.
Bitcoin is the most famous example of a type I decentralized application
but Litecoin and other "alt-coins" are of the same type.

**Type II** decentralized applications use the block chain of a type I
decentralized application. Type II decentralized applications are
protocols and have tokens that are necessary for their function. The
Master Protocol is an example of a type II decentralized application.

**Type III** decentralized applications use the protocol of a type II
decentralized application. Type III decentralized applications are
protocols and have tokens that are necessary for their function. A
hypothetical Cloud Protocol that uses the Master Protocol to issue
'cloudcoins' that can be used to acquire cloud computing services would be an example of a type III decentralized application.

A useful analogy for a type I DApp is a computer operating system (like Windows, Mac OS X, Linux, Android, iOS) for a type II DApp a general purpose
software program (like a word processor, a spreadsheet software, a file
synchronization system such as Dropbox) and for type III DApp, a
specialized software solution (like a mail-merge tool that uses a word
processor, an expense report macro that uses a spreadsheet, or a
blogging platform that uses Dropbox.) Using this analogy, it may be
expected that due to network effects and the ecosystem surrounding each
decentralized application, there will be a few type I DApps, more type II
DApps and even more type III DApps.

At this point, it is important to mention that there are currently several excellent open-source projects that leverage type I DApps. Colored coins and CoinJoin, for example, are based on the Bitcoin block chain and provide useful features to their users. These projects however cannot be classified as type II DApps, according to our definition, because they don't issue and manage a token. (The development and operation of these projects depends on donations instead.)

The operation of a decentralized application
--------------------------------------------

### Mechanisms for establishing consensus

There are two common mechanism by which DAs can etablish consensus: the **proof-of-work**, POW, mechanism and the **proof of stake**, POS,
mechanism.

With the proof-of-work mechanism, decisions about changes in a DApp are
made based on the amount of work that each stakeholder contributes to
the operation of the DApp. Bitcoin uses that approach for its day-to-day
operation. The mechanism for establishing consensus through POW is commonly called mining.

With the proof-of-stake mechanism, decisions about changes in the DApp are
made based on the percent ownership that various stakeholders have over
the application. For instance, the vote of a stakeholder who controls
10% of the tokens issued by a DApp, carries a 10% weight. The Master
Protocol is based on the POS mechanism.

The two mechanisms can be used in parallel, as is the case with
[Peercoin](http://peercoin.net/). Such a combination allows a DApp to
operate with less energy consumption than proof-of-work alone, and
allows it to be more resistant to [51% attacks](https://en.bitcoin.it/wiki/Weaknesses).

### Mechanisms for distributing tokens

There are three common mechanisms by which DAs can distribute their
tokens: mining, fundraising and development.

With the mining mechanism, tokens are distributed to those who
contribute most work to the operation of a DApp. Taking Bitcoin as an
example, bitcoins are distributed through a predetermined algorithm to
the miners that verify transactions and maintain the Bitcoin block
chain.

With the fundraising mechanism, tokens are distributed to those who fund
the initial development of the DApp. Taking the Master Protocol as an
example, Mastercoins were initially distributed to those who sent
bitcoins to a given address at the rate of 100 Mastercoins per bitcoin
sent. The bitcoins collected were then used to fund the development of
applications that promoted the development of the Master Protocol.

WIth the development mechanism, tokens are generated using a predefined mechanism and are only available for the development of the DA. For example, in addition to its fundraising mechanism, the Master Protocol used the collaboration mechanism to fund its future development. An additional 10% of the Mastercoins generated through fundraising was set aside for development of the Master Protocol. Those Mastercoins become available through a pre-derminded schedule and are distributed via a community-driven bounty system where decisions are made based on the proof-of-stake mechanism.

To summarize: Tokens of a DApp that establishes consensus through
proof-of-work are distributed by mining, by people buying directly from
miners and by trading for goods and services; that is the case with
Bitcoin. Tokens of a DA that establishes consensus through
proof-of-stake are distributed based on the contribution of stakeholders
during a fundraiser, by people collaborating on the development of the
DA and by trading for goods and services; that is the case with the
Master Protocol.

### Formation and development of a decentralized application

Development of decentralized applications takes place in three steps.

**Step 1: A whitepaper is published describing the DApp and its features**

As in the case of Bitcoin, the most common way by which a DApp takes form
is by the public release of a whitepaper that describes the protocol, its
features, and its implementation. After the public release, feedback
from the community is necessary for the further development of the DA.

**Step 2: Initial tokens are distributed**

If the DApp is using the mining mechanism to distribute its tokens, a
reference software program is released so that it can be used for
mining. In the case of Bitcoin, a reference software program was
released and the initial transaction block was created.

If the DApp is using the fundraising mechanism, a wallet software 
becomes available to the stakeholders of the DApp, so that they can
exchange the tokens of the DA. In the case of Mastercoin, an Exodus
fundraising address and a wallet script were publicly released.

If the DApp is using the development mechanism, a bounty system is
put in place that allows the suggestion of tasks to be performed, the
tracking of the people who are working on those tasks and the criteria
by which bounties can be awarded.

**Step 3: The ownership stake of the DApp is spread**

As tokens from mining, fundraising and collaboration are distributed to
a greater number of participants, the ownership of the DA becomes less
and less centralized and participants that held a majority stake at
earlier have less and less control. As the DA matures, participants
with more diverse skills are incentivized to make valuable
contributions, and the ownership of the DA is distributed further. Through market forces the tokens of a DApp are transferred to those who value it the most. Those individuals then can contribute to the development of the DA in the areas that they have an expertise.

The case of Bitcoin illustrates the point. By some estimates, Satoshi Nakamoto mined many of the first 1,000,000 bitcoins. As developers contributed code to Bitcoin and miners contributed computational power to the Bitcoin network, the market began to value bitcoins more highly. As the system matured even more, people with diverse skills started valuing Bitcoin and contributing to its development. Now that more than 12 million bitcoins are in circulation and Satoshi Nakamoto's high original ownership stake has been diluted.

### Legal model for the operation of decentralized applications

Operating under open-source licenses allows DAs to be open for innovation without restrictions of copyright or patent. In addition, by being completely open-source, decentralized applications can operate under the legal model of open-source software. Bitcoin, for example, uses the MIT open-source software license. The Master Protocol requires all code that is based on it to be open-source and available to the
community.

The current state of type II and III decentralized applications
----------

One mechanism by which type II DAs can leverage the block chain of type I DAs is for type II DAs to embed additional data to the transactions taking place in the type I DA. The Master Protocol, for instance, embeds additional data on the transactions of the Bitcoin network. Although currently (February 2014) additional data are embedded in an ad hoc way into the Bitcoin block chain, the release of the 0.9 version of the Bitcoin reference client will provide a standard method for that embedding. By using the methodology of "provably prune-able outputs," type II decentralized applications that are based on Bitcoin will be able to embed data in a systematic way and Bitcoin miners will have the option to prune those data. 

Given this development, several type III DApps are in various stages of developed and launch. They include:

- MaidSafe provides a "proof of resource" mechanism & decentralized data structure for storing files privately or publicly in the cloud, 
- StorJ provides a front end Dropbox-like cloud storage of files utalizing MaidSafe and other systems in the backend,
- Ethereum provides concensus based scripting and computing resources,
- OpenGarden provides mesh network-based Internet service,
- Scalion provides a incentivized version of the Tor Network with nodes serving as relays and exits,
- Shared Miles provides a proof of transportation mechanism that allows for an open source transportation standard,
- BlockAuth provides a multi signature OAuth type system for sharing private data with third parties, 
- API Protocol provides an open source standard for hosting, normalizing, and sharing API data.

Conclusion
----------

DApps have the potential to become self-sustaining because they empower
their stakeholders to invest in the development of the DApp.  Because of that, it is conceivable that DApps for payments, data storage, bandwidth and cloud computing may one day surpass the valuation of multinational corporations like Visa, Dropbox, Comcast, and Amazon that are are currently active in the space.

* * * * *

Appendix 1
--------
DApp Best Practices
================================================

### What qualifies a project as a Decentralized Application?

1.  The application must be completely open-source, it must operate autonomously, with no entity controlling the majority of its tokens, and its data and records of operation must be cryptographically stored in a public, decentralized block chain.
2.  The application must generate tokens according to a standard algorithm or set of criteria and possibly distribute some or all of its tokens at the beginning of its operation. These tokens must be necessary for the use of the application and any contribution from users should be rewarded by payment in the application's tokens.
3.  The application may adapt its protocol in response to proposed improvements and market feedback but all changes must be decided by majority consensus of its users.

### What does the coin issuance look like?

Tokens are issued according to the white paper that coordinates the founders thoughts and incorporates community input.  

There are several categories for which tokens may being issued:

1.  Crowdsale: An initial one-time sale of tokens is a common way to initially fund a DApp.  The money raised will be set aside into the foundation which will use that to develop the project.
2.  Developer Pool: A portion of the tokens can be set aside for developers working on the project.  As the market sets a valuation for the project, the developer pool will gain it’s value and can attract contributors to the project.
3.  Premine: It is best to avoid premining a token.  Communities dislike this methology.  If a premine is done it is recommended to have a meaningful reason.
4.  User Behavior (Mining): User Behavior distribution of tokens incentivizes nodes to contribute resources to the DApp.  In Bitcoin, there is a block reward every ten minutes.  This incentives contributors to provide hashing power to the DApp.  In the same way, DApps need to determine how to incentivize the network to contribute the required resource.  This is the most important portion of the token distribution.  Overtime hashing power will be fully rewarded with transaction fees on Bitcoin however to scale to that the block reward provides the incentive.

### What are the tokens exactly?

The tokens purpose is to allow access to a computer system.  For example, an individual must own some amount of bitcoins in order to have any transaction on Bitcoin.  The bitcoins allowed the individual to use a computer system.  The value of using this system may change overtime yet lack the underlying features of an equity security.

There is no underlying assets that can be represented by the tokens, there aren’t dividends and no equity in anything is owned by having a token.

### How do I start developing a DApp business plan?

Developing a DApp has the following steps:

1.  Create a whitepaper: The paper can outline:
  1.  Intentions of the project 
  2.  Coin distribution plans 
  3.  Consensus mechanisms 
  4.  Non-profit management control plan 
  5.  Plans for managing developer bounties
  6.  Technical description of the project
2.  Gain Community Engagement: Release the plan to the community and revising based on feedback.
3.  Crowdsale: Sell the initial tokens based on the plan in the whitepaper.  Setting a date where anyone can contribute to the project.  At this time establishing a non-profit would be suggested.
4.  Begin Executing Plan: The non-profit will plan development

### Frequently Asked Questions:

**How is this a profitable model for developers, users and contributors?**

The model allows contributors to get involved with the project as purchaser of tokens, a project contributor or providing resources to the network for user behavior rewards.  All of these user groups can earn benefit as the tokens can be exchanged.  If the value of the token increases all parties are rewarded.

**What is a User Behavior reward?**

A User Behavior reward is given to contributors that provide utility to the network.  The whitepaper will outline what utility needs to contributed.  For example, hashing power on Bitcoin is rewarded.  Determining what to reward involves having a proof mechanism for guaranteeing the behavior.  For a decentralized data storage project, proof of storage may be a good solution.


Appendix 2
--------
DApp Economic Model
===============================================

"In fact there is a strong correlation (R2 = 0.82) between number of users and price. All these things are not understood by too many people, unfortunately. Also the price doesn't grow linearly with the number of users but instead with the power of 1.45 of the number of users. That is nice because for the price to increase 1000 times you need only 140 times the number of users of today. We have about 2 million BTC users." https://i.imgur.com/CiOxeBY.jpg

"Here a comparison between Metcalfe's, Zipf's and Bitcoin's law."
https://i.imgur.com/AWEfTjZ.jpg

Credit for images and quote gsantostasi via http://www.reddit.com/r/Bitcoin/comments/21pujs/bitcoin_compared_with_metcalfes_and_zipfs_law/

The value of a particular DApp is corrilated well to Metcalfe's Law as this graph demonstrates: http://imgur.com/RDPz54G

Credit for image Peter R via Bitcointalk https://bitcointalk.org/index.php?topic=400235.msg5882283#msg5882283


Appendix 3
--------
DApp Legal Model
===============================================
### Open Source Licensing

DApps operate under a open source license for access to their software. Bitcoin for example operates under the MIT license.  

### What is the legal entity and what do they do?

There are no other legal entities required as the Decentralized Application is not operating as a company.  Owners of tokens do not need to be represented by a corporation.  A contributor to the development of the project does not require any specific legal entity either.

Token issuance is some times done by a non-profit (or a non-profit is formed to assist with the development of the open source software) which contributes to the development of the code.  This non-profit will never receive financial benefits from the software and may have the following responsibilities:

1.  Issuance of initial tokens
2.  Holding of developer tokens
3.  Managing bounty payments 
4.  Setting the direction of the project to be developed

The non-profit can make decisions fully decentralized allowing a “proof of stake” voting mechanism to determine any decision.

### How is the issing of tokens viewed legally?

Few jurisdications have yet publically given their guidance on how Decentralized Applications issuing tokens will be treated from a regulatory and tax perspective. The best advice is to contact a legal expert in the particular jurisdiction in which the user of the token operates. 

From a technical perspective those issuing tokens as part of a crowd sale is selling access to software for the users of that software. The private keys associated with the tokens users purchase during a crowd sale are in a very literal sense the passwords for that user to be able to access that particular Decentralized Application's software.

From a tax perspective those users holding tokens may be said to be holding digital property. However if the token has no market outside of its use in the Decentralzied Application it is hard to determine the actual value of said token.

Appendix 4
--------

### A proposed metaphor for decentralized applications
======================================================

It would be beneficial to have a well-grounded and easily accessible metaphor for DAs. Such a metaphor would ideally have the virtue of
simplexity, so that it could be used for human-computer interfaces.

Such a metaphor could be a [zygote](http://en.wikipedia.org/wiki/Zygote). A zygote is the point where one biological cell generation ends and the next one begins. A zygote acclimates, and it responds to the outside world without changing its genes, it cannot be regulated, it is stuck with its own genes and its recursive. The zygote is autonomous because it is stuck with its own genes, it is an application because it is a cell, it is distributed, and it is authorized to act as a single entity from other other cells; it shares, in other words many of the characteristics of a decentralized application.

Terms that could created out of the term zygote include *zyprotocol*, the zygotic protocol, *zapp*, the zygotic application, *zen*, the zygotic entity, and *zybit*, the zygotic bit.

Appendix 5
--------
### Johnston's Law
======================================================

"Everything that can be decentralized, will be decentralized." David A. Johnston

Based on the economic and efficiency advantages of decentralized applications its clear that existing centralized services will be displaced over time by decentralized alterantives. This shift is likely to come most quickly for services in which the network effect advantages of Metcalfe's Law are most critical to the success of the service provider.
