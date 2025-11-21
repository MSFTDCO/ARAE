# 📒 Changelog – ### Azure Rapid Assessment Estimator
All notable changes to this project will be documented here.  
Format follows [Keep a Changelog](https://keepachangelog.com/).

---

## [Unreleased]
- Planned features and improvements
  - Add new Azure regions (Austria, ..., Switzerland, ...).
  - Adjust to new AVS SKUs
  - Create an enhanced Azure Local estimator
  - Reduce MSRP pricing overhead to selectable meters
- Open requests from feedback channel
  - ...

---

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


---

## [8.7.5] – 2025-09-17
### ✨ New Features
- 
- 

### 🛠️ Changes
- Updated with September pricing
- 
