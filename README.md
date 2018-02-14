# UpvoteBOT - Steemit Bid Based Voting System

This is a fork of Candy-Bot. It is personalized for my personal use. If you want to to make your own bid-based bot check the original repository : github.com/ah-projects/Candy-Bot

Candy BOT is developed as an open source BOT for Steemit and It do 10 batches daily. After every 2.4 Hours It provides Votes equally among the Bids by the users.

---

# Example:
If User Alice and user Bob both bid in same voting batch, Alice Bids 1 SBD and Bob also bids 1 SBD then both will recieve 50.00% vote of the Bot when the bot comes to vote. In the Same way If Alice Bids 4 SBD but Bob bids 2 SBD then Alice will get a 66.66% Vote while Bob will get a 33.33% Vote.

---

# Installation
Installation of this bot is done with the way done using three applications NodeJS, npm and node. The Source code and Installation Process is opened, some of variables will maybe hidden due to security issues.

```javascript
$ npm install
$ nodejs candybot.js
```


The BOT cantains Config.json file to configure properties and other files conected to it like delegators.js, blacklist, package.js and node_modules Files respectively.

Click [Here]() to see the laest Updated Version of CandyBOT!

# Usage Rules

1. If there are multiple bids with the same post, only one vote will be cast and the remaining bids will be refunded by the manual process.

2. If the bot has already voted for a post, additional bids will be refunded by the manual process.

3. The URL must be correctly expressed in the memo alone. Funds will be refunded by the manual process.

# Minimum Bid, Requirements & Configuration:
---
Minimum Bid | 0.001 SBD or Steem
-|-|
Allows Comments | Yes|
Accept Steem Bids | Yes|
Refunds | Yes|
Post Age Limit | 6 Days|
Batch Voting Time | 2.4 Hours|
Daily Batches | 10 |

# API Used
The main used API Includes `https://api.steemit.com`

# License
This is not a Private Property as mentioned in the main Installation repo [here](https://github.com/MattyIce/postpromoter), So it is Considered under a Creative Commons ([Public Domain](https://creativecommons.org/publicdomain/zero/1.0/)) & we don't claim any kind of Copyright to it but further created by the respected owners.

# Get In Touch With The Creator!

Get in touch with the candybot on [Steemit](steemit.com/@candybo) and [Discord](https://discord.gg/U5yksG9) @Candybot or you can simply contact the owner @ali-hassan.

Buisness and Support email: mail.candybot@gmail.com
