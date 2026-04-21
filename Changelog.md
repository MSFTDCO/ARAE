# 📒 Changelog – Azure Rapid Assessment Estimator
All notable changes to this project will be documented here.  
Format follows [Keep a Changelog](https://keepachangelog.com/).

---

## [Unreleased]
- Planned features and improvements
  - Add new Azure regions (Austria, Belgium, Switzerland, ...).
  - Adjust to new AVS SKUs
  - Create an enhanced Azure Local estimator
  - Reduce MSRP pricing overhead to selectable meters
- Open requests from feedback channel
  - ...

---
## [8.7.9] – 2026-04-21

### 🛠️ Changes
- Updated monthly FXRates
- Updated Azure Pricing Data with April snapshot
- Updated CSP Pricelist with latest software SKUs


## [8.7.8] – 2026-02-26

### 🛠️ Changes
- Updated monthly FXRates
- Updated Azure Pricing Data with February snapshot
- Updated CSP Pricelist with latest software SKUs
- Adjusted the PaaS Spec Sheet to reflect changed SQL Identifiers in the CSP Pricelist
- Added a warning when selected currency does not match the CPS Pricelist currency


## [8.7.7] – 2026-01-09
### ✨ New Features
- Added a feedback form button to the VM Input tab 

### 🛠️ Changes
- Updated monthly FXRates
- Updated Azure Pricing Data with January snapshot
- Updated CSP Pricelist with latest software SKUs

### 🐞 Bug Fixes
-  corrected Managed Service Markup drop down list definition


## [8.7.6] – 2025-11-20
### ✨ New Features
- FXRates
  - Now reflect actual monthly rates applied aligned with Azure Pricing.
  - Removed QAR and introduced BRL.
  - Selectable currencies now comprise: AUD, BRL, CAD, DKK, EUR, INR, JPY, KRW, TWD, NZD, NOK, RUB, SEK, CHF, GBP, USD.
  - Only included FX rates that are selectable (reducing to 16 currencies).
  - FXRate Month now displayed in the header of the VM Input Sheet.

### 🛠️ Changes
- Updated with November pricing

- SKU Updates
  - removed VpnGw1, VpnGw2, VpnGw3, VpnGw4, VpnGw5 which are no longer available.
  - Hiding the Azure Stack-AVS tab until adoption of AVS SKU changes

- Incentives
  - Updated the Arc SQL Estimator to reflect FY26 Incentive structure.

### 🐞 Bug Fixes
- changed date handling for Price List Date and FXrate Date to be independent from regional localization


## [8.7.5] – 2025-09-17

### 🛠️ Changes
- Updated with September pricing
