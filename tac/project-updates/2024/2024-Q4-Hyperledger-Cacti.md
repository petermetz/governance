---
layout: default
title: 2024 Q4 Hyperledger Cacti
parent: 2024
grand_parent: Project Updates
---


# Project Health

- The project is in good health!
- The project repository was successfully moved to [its own repository](https://github.com/hyperledger-cacti) following the move from the Hyperledger Foundation to Linux Foundation's Decentralized Trust. Cacti was one of the first projects on which this experiment was carried out, and it was successful thanks to the LFDT administrators.
- A major release (`2.0.0`) was made recently.
- The mentorship projects are progressing nicely, with solid code contributions from the mentees, including Cactus-Weaver integration.
- Work on keeping Cacti up-to-date with the IETF SATP interoperability protocol standard is continuing nicely.
  * Cacti maintainers continue to be actively involved in the IETF SATP Working Group, co-authoring protocol specifications.
- We are not doing too badly on the [OpenSSF Scorecard Metrics](https://scorecard.dev/viewer/?uri=github.com%2Fhyperledger-cacti%2Fcacti) with a present score (as of the time of this file's commit) of 6.3, but there is a lot of scope to improve.

LFX Insights (Beta) Link: https://insights.lfx.linuxfoundation.org/foundation/lf-decentralized-trust/overview/github?project=cacti

# Questions/Issues for the TAC

No questions for the TAC at this time.

# Releases

- v2.0.0 - issued (major release)

# Overall Activity in the Past Quarter

- Several minor releases with incremental changes and improvements were made (the last one being `2.0.0-rc.7`) in the old organization (`github.com/hyperledger`) prior to the major release (`2.0.0` in the new organization `github.com/hyperledger-cacti`).
- The Discord channel sees significant activity and Q/A. The daily pair programming calls are well attended by mentees, existing contributors and would-be contributors alike.
- Questions are answered in a mostly timely fashion though it's not perfect we do make a conscious effort to respond quickly.
- One of these mentorship projects involves a major change to the Cacti code base and architecture, namely the integration of the Cactus and Weaver modules into a common and comprehensive set of capabilities for cross-network operations. A first-cut version of these common COPM modules is [close to being merged](https://github.com/hyperledger-cacti/cacti/pull/3546) into the main branch.
- There was a lot of work done on the SATP-Hermes framework in the past quarter (see the [satp-dev](https://github.com/hyperledger-cacti/cacti/tree/satp-dev) branch).
  * The SATP-Weaver-Relay framework (the other sample implementation of the SATP standard under Cacti) did not make any progress since the [May 23 workshop](https://lf-hyperledger.atlassian.net/wiki/spaces/events/pages/21794363/Standardizing+DLT+Interoperation+Implementing+IETF+Secure+Asset+Transfer+Protocol+in+Hyperledger+Cacti), but we hope to get more code contributions in the future, especially after the IETF published official RFCs.

# Current Plans

1. We are working on improving our OpenSSF Scorecard numbers.
2. We are working on a more automated and sustainable way to maintain package references in source code and configuration files so that if (or when)the repository is migrated to a new organization, the relevant GitHub Actions will automatically publish packages to the new organization's namespace whenever a release is made. (FYI, the publish actions related to the Weaver packages failed to take effect in the recent `2.0.0` release because of hardcoded references to `hyperledger`. We will fix this in an upcoming minor release.)

# Maintainer Diversity

We have 8 active maintainers from 4 different organizations total:

- Izuru Sato 
- Michal Bajer 
- Peter Somogyvari 
- Takuma TAKEUCHI 
- Jagpreet Singh Sasan 
- Venkatraman Ramakrishna 
- Sandeep Nishad 
- Rafael Belchior 

# Contributor Diversity

- Source: https://insights.lfx.linuxfoundation.org/foundation/lf-decentralized-trust/reports/organizations?project=cacti
- Top 3 contributors were Hyperledger(??), Accenture, IBM, and Fujitsu respectively, with Hyperledger contributing close to 60% of the activity. 

# Additional Information


