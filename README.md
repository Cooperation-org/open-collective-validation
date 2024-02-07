# Enable Validation of Open Collective Expenses 

## Purpose

The purpose of this repo is to enable permissionless attestations about expenses made on Open Collective projects

### Status

Scraper is completed, see [./scraper](./scraper)

Data has been imported into the LinkedTrust interface and published to the Ceramic Network using the [trust-claim-data-pipeline](https://github.com/Whats-Cookin/trust-claim-data-pipeline) scripts

The expenses are now visible at [Live.Linkedtrust.us](https://live.linkedtrust.us) and may be publicly attested to, for example

https://live.linkedtrust.us/validate?subject=https://linkedtrust.us/claims/102083

<img width="843" alt="image" src="https://github.com/Cooperation-org/open-collective-validation/assets/798887/066aa2c8-f0b8-4044-b038-9ef267a668be">

The claims and attestations about them are written to decentralized storage and can be viewed elsewhere on the Ceramic Network such as at 

https://cerscan.com/mainnet/stream/kjzl6kcym7w8y9qei13m3wd4oy7xtb8mv0ckldnkm2ih7it2cl5zf4ivqaph1ic

### TODO Next

Some corrections need to be made about the currency type, and the system needs to be automated with continuous updates, the user interface for attestors needs to be improved, including ability to add other sources of credibility, and we need to create a notification flow that could be integrated for open collective administrators.  
