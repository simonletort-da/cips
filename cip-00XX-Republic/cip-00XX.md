## CIP 00XX

<pre>
  CIP: CIP 00XX
  Title: Add Republic as an SV of Weight 6
  Author: Luca Burlando
  Status: Draft
  Type: Governance 
  Created: 2025-09-18
  Approved: 2025-XX-XX
  License: CC0-1.0
</pre>

## Abstract

* Add Republic as an SV of Weight 6.

## About Applicant

* Republic is a leading on-chain investment ecosystem, leveraging its cutting-edge financial infrastructure to redefine global accessibility and optimize capital efficiency.
* Republic boasts a portfolio of over 2,500 companies and a community of 3 million members from over 150 countries. More than $2.6 billion has been deployed through investment platforms, funds, and firms within the Republic family of companies.
* Republic is backed by Morgan Stanley, Galaxy, AngelList, Valor Equity, and other leading institutions.

## Deliverables for full SV Reward:

| Deliverable                                       | Acceptance Criteria                                                                                                                                                                                                                                                                                                                                                                                                        | Deadline                    | Weight Earned |
| ------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------- | ------------- |
| Republic Wallet support for Canton Token Standard | • Republic Wallet integration: Enable Canton in a fully regulated retail wallet by integrating Canton Network Token Standard into Republic’s wallet. <br> • Republic Wallet key features: customizable, API-enabled wallet and validator platform that supports security and utility tokens, with secure key management, recovery, real‑time transactions, automated fees, and continuous updates for reliable performance | +180 days from CIP approval | 1             |

## SV Reward Mechanics:

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

* **2025-09-18:** Initial draft of the proposal.
