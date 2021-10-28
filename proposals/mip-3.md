# Menace Improvement Proposal (MIP-3)

## tl;dr
Give ourselves NFTs as governance tokens to vote (setup NFT DAO)

## Motivation
We should this because...
- We need to vote on things with in the DAO (we need a governance token)
- We need to automate the onboarding process further so we can onboard more folks (eventually do daily auctions)
- NFTs are cool way to do governance tokens, we can have cool art too

## Context

We would fork NounsDAO (nouns.wtf) and follow their model. A generative PFP based on premade assets is auctioned off once a day. This NFT acts as the governance token that votes to direct the flow and purpose of the treasury and collective capital. Owners have veto power with a unanimous vote in early stages; later dissolves as further structure is strengthened 

Using a Nouns DAO Structure with expanded features that focus on leveraging our artistic community and on creating a proper system to support NFTs as a new asset class. 

## Scope
What is the scope of the project? What will it require?
- Smart contract development for the NFTs
- NFTs for every members of the DAO
- Art for the NFTs
- Super simple site that allows for DAO members to mint their DAO NFTs
- Frontend deployment of this page etc.

### Not in the scope of this proposal
- If we can do these, great
- Daily Auctions, that can 
- The idea here is to split up the tasks. Get the NFTs in DAO members hands first, and then daily auctions

### Art 
- TBD

### NFTs
- Limit the OG founder Menace NFTs to a 100? (up for debate)
- Royalties, 5%? all royalties go to DAO treasury wallet

### SW Reqs
- We'd like to reuse as much as possible, and not build (if we can)
- Fork this monorepo: https://github.com/nounsDAO/nouns-monorepo
- contracts for Nouns: https://github.com/nounsDAO/nouns-monorepo/tree/master/packages/nouns-contracts 
- deploy contract etc.

## Owners
Who will be owners for the project and be responsible for delivering the project
- @0xJuly, @NaturalVoids have volunteered so far (open to other folks joining)

## Resources / Compensation
Do you need funding? Do the contributors of the project need to be paid in NFTs or FTM? 
- Compensation for artists
- Compensation for devs

## Timeline
How long will this roughly take?
- Art: X weeks
- Contracts for deploying: X weeks
- Frontend minimal minting site: X weeks

### Additional context
Add any other context or screenshots about the feature request here.
- More to come
