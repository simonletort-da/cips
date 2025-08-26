## CIP 00XX

<pre>
  CIP: CIP 00XX
  Title: Add Taurus as an SV of Weight 5.5
  Author: Victor Busson
  Status: Draft
  Type: Governance
  Created: 2025-08-26
  License: CC0-1.0
</pre>

## Abstract

* Add Taurus as a Super Validator of weight 5.5 as proposed in the detailed deliverables list below.
* Taurus commits to contribute to the growth of the Canton Network ecosystem and speed up its adoption within the financial sector by integrating Canton Network within its platform, allowing its banking clients to use and build on Canton Network.

## About the applicant

* Taurus SA is a technology company, founded in April 2018, that provides enterprise-grade digital asset infrastructure to issue, custody, and trade any digital assets: cryptocurrencies, tokenized assets, and digital currencies.
* It is a global leader in the banking segment, entrusted by the full spectrum of financial institutions across regions: systemic banks, universal banks, online banks, crypto-banks, private banks, and broker-dealers. Clients include CACEIS, Deutsche Bank, State Street.
* Taurus is a regulated technology provider: it holds a securities firm license from the Swiss Financial Market Supervisory Authority (FINMA) and operates since 2021 once of the first organized trading facility to trade tokenized securities: T-DX
* Taurus meets the highest security, regulatory, risk and compliance standards: ISO27001, ISAE3402 Type 2, FINMA licenses, HSM FIPS 140-2 Level 3, DORA compliant
* Taurus employs around 100 people, the majority being highly qualified PhDs (incl. Cryptography, computer networking, distributed systems, physics), engineers and blockchain & security experts
* Taurus led some of the world’s most significant innovations in digital assets: 1st digital asset custody standards (2019 DACS), 1st open source MPC-CMP implementation, 1st open source private token standard on public blockchains, leading contributor to CMTAT tokenization standards for equity and debt.
* Taurus is backed by Arab Bank Switzerland, Deutsche Bank, Lombard Odier, Pictet, UBS
* It offers a fully modular and integrated platform that covers the full digital asset value chain:
  * Taurus-PROTECT: hot, warm and cold custody solution (technology)
  * Taurus-EXPLORER: nodes & indexing infrastructure solution (technology)
  * Taurus-CAPITAL : asset agnostic tokenization solution (technology)
  * Taurus-NETWORK: collateral management and settlement system (technology)
  * Taurus-PRIME: institutional-grade trading platform (financial services)

## Deliverables for Full SV Reward

| End-product                                                                          | Description/requirements                                                                                                                                                                                                                                                                                                                                                                 | Deadline                                  | Weight Earned                                                                          |
| ------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------- | -------------------------------------------------------------------------------------- |
| **CUSTODY** <br> Integration w/ Taurus-EXPLORER <br> + Integration w/ Taurus-PROTECT | Custody (including nodes & indexing) support of Canton Network Token Standard                                                                                                                                                                                                                                                                                                            | +180 days from CIP approval               | 1                                                                                      |
| **Acceleration Bonus**                                                               | For Custody <br> <br> +0 Bonus if delivered +180 Days from SV CIP Approval <br> <br>   +2 Bonus if delivered +60 Days from SV CIP Approval <br> <br>  Linear sliding scale between +60 and +180 days  <br>  <br> Example: If delivered in +120 days, Fireblocks is awarded +1 SV Weight <br> <br> • At least one Taurus customer must be live, having completed a transaction on MainNet | +180 days from CIP approval               | 2                                                                                      |
| **Adoption Bonus**                                                                   | Category 1 <br> • Per $1.5b of assets transferred <br> <br> Category 2 <br> • For each approved participant (by the Tokenomics Committee), using Taurus to issue an asset >$1M TVL on Canton                                                                                                                                                                                             | +180 days from custody support going live | • 0.5 per live deployment under Category 1 or Category 2 <br> • Max up to 2.5 in total |

## Milestone Mechanics

* The GSF Tokenomics committee commits to deliberate each proposed participant and clearly notify Taurus if the participant would count against the Adoption Incentives
* Taurus will meet with the GSF Tokenomics committee once every 60 days and provide a progress report towards stated deliverables

## SV Reward Mechanics

* An `extraBeneficiary` PartyID associated with the ‘escrowed’ Super Validator will be setup by the GSF with an SV Weight at the maximum earnable weight in the CIP that granted rights to that Super Validator.
  * The Applicant is responsible for all costs associated with the operation of the escrow SV
  * The escrow SV will NOT mint rewards on a block by block basis
  * All escrow SV rewards will go to the Unclaimed Rewards pool
* ⅔ of the Super Validator Operators will update their configurations to allow GSF to host the full weight to be earned by the given Super Validator
* Applicant is required to present proof of successful completed milestones to the Tokenomics Working Group
  * Applicant is required to present a calculation for number of Canton Coin it should earn for meeting the requirements of the milestone
* If the Tokenomics Working Group agrees the milestone has been met and agrees with the calculation, an announcement will be sent via the Tokenomics-Announce mailing List
  * The GSF will update the `extraBeneficiary` to an active PartyID controlled by that Super Validator. 
  * ⅔ of Super Validator Operators will then assign a portion of the Unclaimed Rewards to be minted by the Applicant’s Validator, based on the calculation approved by the Tokenomics working group.
* If any milestones and associated rewards are not achieved by the deadline
  * Applicant will be notified they have not met a deliverable by the GSF
  * Remaining SV Weight assigned to the `extraBeneficiary` SV will be removed from the GSF node configuration, and the total SV weight of the GSF SV node will be reduced by the same amount by a vote of the Super Validators.
  * The Tokenomics Working Group will make a recommendation to the SVs on what to do with the Unclaimed Rewards 
* Applicant is subject to CIP-0045 : SV Operating Requirements
  * If, at any time, the Applicant has been rewarded SV Weight > 2.5, they are required to operate their SV within 6 months of crossing that Weight. This SV node will join the network with an SV weight of zero (0) and may add weights as the SV completes the milestones listed in this CIP.

## Copyright

* This CIP is licensed under CC0-1.0: [Creative Commons CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/).

## Changelog

* **2025-08-26:** Initial draft of the proposal.
