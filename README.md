# Zcash_Observatory_Docs
Documentation for the Observatory (to keep it out of the main repo)

# Zcash Observatory

Mitchell Krawiec-Thayer and Pranav Thirunavukkarasu

Contact: [Mitchell@InsightFellows.com](mailto:mitchell@insightfellows.com)

Full writeup at [https://fellows.link/ZcashObservatory](https://fellows.link/ZcashObservatory)

## Motivation:
As Zcash adoption expands and the network scales, consumers, researchers, and businesses will all require high-quality data quantifying network health and security. Users need data and visibility related to both performance (latency, load, etc) and security (reorganizations, double spend attacks, etc). Our observatory nodes and network will detect and alert for a variety of these phenomena. In addition to monitoring and reporting network security, quantified understanding of network characteristics will inform protocol design decisions related to Zcash scaling and privacy. A comprehensive observatory NetSec system will increase Zcash’s attractiveness for commercial adoption and infrastructure integration.

## Key deliverables & features:
-  Archive and analyze alternative/orphaned blocks and transactions
-  Detect and alert on potential double spend attacks
-  Detect and alert on probable selfish/stubborn mining
-  Quantify global network topology and latency
-  Block/transaction propagation time
-  Miner-timestamp spoofing
-  Peerlist homogeneity, network connectivity, network centralization
-  Open-source public front-end/dashboard to visualize Zcash network health & security
-  Research database for Zcash analysis (nearest is BigQuery, lacking NetSec data)
-  All products will be released as free open-source software thanks to Zcash Foundation support

## Status
- [x] Advanced logging
- [x] NetSec alerts
- [x] Research pipelines
- [ ] Global network
- [ ] Dashboard / front-end

## Donate to Observatoy development

We'd like to thank the Zcash Foundation for the [financial support](https://grants.zfnd.org/proposals/21786689-zcash-observatory) enabled us to develop the observatory tooling. We are currently developing a public research database, open-source alerting system, and free dashboard. The Observatory Project is seeking sponsors to fund the continued creation and operation of these public NetSec utilities.

```
Shielded sponsorship:
zs1gvj8aha3drjnerl3fxp3etwa2s8yepp45yqdkueuewe2cmuyadxyaxc838k5vcrldxdxv80atp6

Transparent sponsorship:
t1LWFw5i5La9WJ1SBfn4VZ74L2dkVHUzoB4

Fiat sponsors welcome, contact: Mitchell@InsightFellows.com
```
![https://raw.githubusercontent.com/insight-decentralized-consensus-lab/Zcash_Observatory_Docs/master/donations.png](https://raw.githubusercontent.com/insight-decentralized-consensus-lab/Zcash_Observatory_Docs/master/donations.png)

