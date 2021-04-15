# W3F Open Grant Proposal


* **Project Name:** DataHighway
* **Team Name:** DataHighway DAO, MXC Foundation, IPFS team
* **Payment Address:** 0xC6D7522f7B012b22Bc365C9C43b3DBf13B9aAfF9


> ⚠️ *The combination of your GitHub account submitting the application and the payment address above will be your unique identifier during the program. Please keep them safe.*

## Project Overview :page_facing_up:

DataHighway is the first IoT parachain candiate that builts on Substrate to faciliate the data transfer between different blockchains. The Inter-Chain data marketplace can bring the data from MXC IoT network to IPFS, BTT, AR, ETH, EOS, DOT, and other Polkadot parachains like CRU.

### Overview


* DataHighway is a DAO that builts on Substrate to faciliate the Inter-Chain data transfer.DataHighway's community members will ultimately be incentivized to operate a sophisticated IoT parachain based on Polkadot, where they may stake, govern, mine and otherwise participate using the new DHX token and its associated Decentralized Autonomous Organization (DAO), and Inter-Chain Data Market.
* DataHighway: 100% mineable, 100% Proof of Participation, 100% DAO, 100% you
* DataHighway is in the first batch of Builder Program
* We would like to get into W3F grants to attract more data projects to build with us.

### Project Details
![Overview](https://raw.githubusercontent.com/DataHighway-DHX/documentation/master/assets/images/diagram-flow-dhx.png)
**DAO**
* It will not have a central authority to regulate its monetary base and fiscal policy, instead it will be regulated by the DHX DAO, which will govern future growth strategies.

**Mining**
* It will allow users to be rewarded in return for participation.

**Inter-Chain Data Market**
* The DataHighway's (DHX) Inter-Chain Data Market allows participants to become data providers and to share IoT data from their devices to application developers in exchange for DHX tokens.

**LPWAN**
* A category of devices that run on low bandwidths (less than 125kHz, 200bps) with low power consumption (less than 2W when transmitting). Typically the technologies involved include LoRaWAN, Sigfox, Weightless, NB-IoT.

**Roaming**
Devices (LPWAN IoT End Devices) are owned by Data Providers and registered at a "home" Network Server (or Supernode that has purchased a specific Network ID) that belongs to a specific Network Operator (such as the MXC Network).

Data Consumers may request to be granted access to receive packets of data that have been uplinked from a device, which may require purchasing ad-hoc access or a subscription from the DataHighway's Inter-Chain Data Market (see separate "Inter-Chain Data Market" Whitepaper).

![Mining](https://raw.githubusercontent.com/DataHighway-DHX/documentation/master/assets/images/diagram-use-case-hardware-mining.png)

### Ecosystem Fit

* There are a lot of DAPPs platforms on a lot of blockchains, and there are also a lot of Polkadot parachain projects, all of them need the real world IoT data like the temperature, tire pressure, delivery package data to feed into their DAPPs, DataHighway is the decentralized data marketplace for these DAPPs.
* Target audiences would be the DAPPs that need to use real world IoT data.
* The data transfer needs between different blockchains like IPFS, BTT, MXC, CRU, AR
* There are only few IoT parachain candidates in the ecosystem, they are doing Bluetooth sharing or robotics, we are the Inter-Chain data marketplace that can work with them to facilitate the data transactions from and to them.

## Team :busts_in_silhouette:

### Team members

* Luke Schoen https://github.com/ltfschoen
* Ilya Beregovskiy https://github.com/festelo
* Christian Groeschel https://github.com/cgroeschel

### Contact

* **Contact Name:**  Xin Hu
* **Contact Email:** DAO@datahigway.com
* **Website:** https://datahighway.com



### Team's experience

Luke was from Parity team , who worked on a lot of web3 projects since 2014. 
Ilya is a full stack blockchain developer that proficient in Rust and Flutter.
Chrisitian is a blockchain DevOps who has more than 15 years experiences.

### Team Code Repos
https://github.com/DataHighway-DHX/node
https://github.com/DataHighway-DHX/apps



## Development Status :open_book:

If you've already started implementing your project or it is part of a larger repository, please provide a link and a description of the code here. In any case, please provide some documentation on the research and other work you have conducted before applying. This could be:

* links to improvement proposals or [RFPs](https://github.com/w3f/General-Grants-Program/tree/master/rfp-proposal) (requests for proposal),
* academic publications relevant to the problem,
* links to your research diary, blog posts, articles, forum discussions or open GitHub issues,
* references to conversations you might have had related to this project with anyone from the Web3 Foundation,
* previous interface iterations, such as mock-ups and wireframes.

## Development Roadmap :nut_and_bolt:

This section should break the development roadmap down into milestones and deliverables. Since these will be part of the agreement, it helps to describe _the functionality we should expect in as much detail as possible_, plus how we can verify and test that functionality. Whenever milestones are delivered, we refer to this document to ensure that everything has been delivered as expected.

Below we provide an **example roadmap**. In the descriptions, it should be clear how your project is related to Substrate, Kusama or Polkadot. We _recommend_ that the scope of the work can fit within a three-month period and that teams structure their roadmap as 1 milestone ≈ 1 month.

For each milestone,

* make sure to include a specification of your software. _Treat it as a contract_; the level of detail must be enough to later verify that the software meets the specification.
To assist you in defining it, we have created a document with examples for some grant categories [here](../src/grant_guidelines_per_category.md).
* include the amount of funding requested _per milestone_.
* include documentation (tutorials, API specifications, architecture diagrams, whatever is appropriate) in each milestone. This ensures that the code can be widely used by the community.
* provide a test suite, comprising unit and integration tests, along with a guide on how to set up and run them.
* commit to providing Dockerfiles for the delivery of your project.
* indicate milestone duration as well as number of full-time employees working on each milestone, and include the approximate number of days along with the cost per day.
* _Deliverables 0a-0d are mandatory_ and shall not be removed, unless you explicitly specify a reason within the PR's `Additional Notes` section (e.g. Milestone X is research oriented and as such there is no code to test).

> :zap: If any of your deliverables is based on somebody else's work, make sure you work and publish _under the terms of the license_ of the respective project and that you **highlight this fact in your milestone documentation** and in the source code if applicable! **Teams that submit others' work without attributing it will be immediately terminated.**

### Overview

* **Total Estimated Duration:** Duration of the whole project (e.g. 2 months)
* **Full-Time Equivalent (FTE):**  Required workload of a full-time employee for the whole project (see [Wikipedia](https://en.wikipedia.org/wiki/Full-time_equivalent)) (e.g. 2 FTE)
* **Total Costs:** Amount of payment in USD for the whole project. The total amount of funding _needs to be below $30k for initial grants_ and $100k for follow-up grants. (e.g. 12,000 USD)

### Milestone 1 Example — Implement Substrate Modules

* **Estimated Duration:** 1 month
* **FTE:**  2
* **Costs:** 8,000 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0a. | License | Apache 2.0 / MIT / Unlicense |
| 0b. | Documentation | We will provide both inline documentation of the code and a basic tutorial that explains how a user can (for example) spin up one of our Substrate nodes. Once the node is up, it will be possible to send test transactions that will show how the new functionality works. |
| 0c. | Testing Guide | Core functions will be fully covered by unit tests to ensure functionality and robustness. In the guide, we will describe how to run these tests. |
| 0d. | Article/Tutorial | We will publish an article/tutorial/workshop that explains [...] (what was done/achieved as part of the grant). (Content, language and medium should reflect your target audience described above.)
| 1. | Substrate module: X | We will create a Substrate module that will... (Please list the functionality that will be coded for the first milestone) |  
| 2. | Substrate module: Y | We will create a Substrate module that will... |  
| 3. | Substrate module: Z | We will create a Substrate module that will... |  
| 4. | Substrate chain | Modules X, Y & Z of our custom chain will interact in such a way... (Please describe the deliverable here as detailed as possible) |  
| 5. | Docker | We will provide a dockerfile to demonstrate the full functionality of our chain |


### Milestone 2 Example — Additional features

* **Estimated Duration:** 1 month
* **FTE:**  1
* **Costs:** 4,000 USD

...


## Future Plans

Please include here

* how you intend to use, enhance, promote and support your project in the short term, and
* the team's long-term plans and intentions in relation to it.


## Additional Information :heavy_plus_sign:

**How did you hear about the Grants Program?** Web3 Foundation Website / Medium / Twitter / Element / Announcement by another team / personal recommendation / etc.

Here you can also add any additional information that you think is relevant to this application but isn't part of it already, such as:

* Work you have already done.
* Wheter there are any other teams who have already contributed (financially) to the project.
* Previous grants you may have applied for.
