# Open Banking Read-Write API

The Read/Write Data API specification describes a collection of RESTful APIs that enable TPPs to access information and initiate payments for customers, by connecting to ASPSPs – securely, efficiently, and with customer consent.

The specification is structured as a series of profiles, resources and data models. The structure is intended to give ASPSPs a suite of functionality to meet their regulatory and commercial requirements. ASPSPs implementing aspects of the specification should select a version of the R/W Data API Profile, compatible functional profiles (such as Accounts and Transactions or Payments) and compatible resources.

Details of version compatibility can be found in **profiles** section and specific sub-sections of **resources and data models** section of the specification.

This specification should be read in conjunction with the Customer Experience Guidelines, Operational Guidelines and Management Information Requirements. Together these form the OBIE standard, which should enable any ASPSP which implements the specification to meet their obligations under both the CMA Order and PSD2/RTS.

The key difference between the CMA Order and PSD2/RTS requirements relate to which product types are implemented, and the timing for implementation. For example, the CMA Order requires the CMA9 to implement the standard for PCA and BCA accounts earlier (in some cases) than the PSD2/RTS timelines. The timings are defined in the Open Banking Roadmap (https://www.openbanking.org.uk/wp-content/uploads/Open-Banking-Revised-Roadmap-July-2018.pdf).

## Known Issues
The specification must be read in conjunction with the [Known Issues](https://openbanking.atlassian.net/wiki/spaces/DZ/pages/47546479/Known+Specification+Issues).

## Swagger Specification

The Swagger Specification for R/W APIs can be downloaded from the following GitHub Repository:

https://github.com/OpenBankingUK/read-write-api-specs

## Change Log

### Version 3.1.4

#### Add a Change Log
- Added a Change Log with commit links to be able to view differences between versions

> The diff links below are experimental for this draft and may function correctly
Feedback on their utility is welcome.

#### Decision 205
[View Diff](https://github.com/OpenBankingUK/read-write-api-docs/commit/c9757fcb35e9d2d6d88e45c9de62df9bd5533aaa)
- Scope for Event notifications
  - Changed scope for `event-notifications` API to be either of accounts or fundsconfirmations
- Optionality of PUT requests
  - Changed the optionality of `PUT /callback-urls`
- Optionality of DELETE requests
  - Changed the optionality of `DELETE /callback-urls`

#### Decision 206 - Optionality of acknowledgements for aggregated polling
[View Diff](https://github.com/OpenBankingUK/read-write-api-docs/commit/538e1995407c4178336a9c9fcd18d9e364a05e51)
- Clarified behaviour that is expected when ASPSPs do not want to process acknowledgements for aggregated polling

#### Decision ???
[View Diff](https://github.com/OpenBankingUK/read-write-api-docs/commit/bfc668834060eb212360fe7fe892b0e9c389394c)

High Cost Credit

#### Waiver 7
[View Diff](https://github.com/OpenBankingUK/read-write-api-docs/commit/f0ca9da113626f7fec980b384ed1d54fbe5e0a24)

#### Fix Known Issues
[View Diff](https://github.com/OpenBankingUK/read-write-api-docs/commit/ba4abc36b60b89da48b980586be2d72e0bdb9c35)

#### Decision ??? - CIBA Profile changes
[View Diff](https://github.com/OpenBankingUK/read-write-api-docs/commit/89ea24c373591f6f90b2c7795b1c9a0dfb108a99)

#### Housekeeping - Fix markdown errors and file naming
[View Diff](https://github.com/OpenBankingUK/read-write-api-docs/commit/89ea24c373591f6f90b2c7795b1c9a0dfb108a99)

#### Decision ??? - DCR changes
[View Diff](https://github.com/OpenBankingUK/read-write-api-docs/commit/c77293e1f0542b5c437de6831d4aeac7a7f86c26)

#### DCR 3.1 (Migrate from Confluence)
[View Diff](https://github.com/OpenBankingUK/read-write-api-docs/commit/ba47bcaea2235bbe6f9eb873ae4b9a553666d78a)
