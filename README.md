# EVE Arbitrage Calculator v2026 - arbitrage calculator 2026

> **A browser-based EVE market arbitrage calculator that compares trade hubs, calculates profit after fees, and highlights the best opportunities in the 2026 release.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/ethangmcole355/eve-market-arbitrage-2026?style=flat-square)](https://github.com/ethangmcole355/eve-market-arbitrage-2026)

---

<p align="center">
  <a href="https://ethangmcole355.github.io/eve-market-arbitrage-2026/">
    <img src="https://img.shields.io/badge/Download-EVE%20Arbitrage%20Calculator%20Latest-brightgreen?style=for-the-badge" alt="Download EVE Arbitrage Calculator">
  </a>
</p>

> **[Direct Download - EVE Arbitrage Calculator v2026](https://ethangmcole355.github.io/eve-market-arbitrage-2026/)**

---

[Download Latest Build](https://ethangmcole355.github.io/eve-market-arbitrage-2026/)

---

## What this tool does

EVE Arbitrage Calculator is a web app for evaluating price gaps between EVE trade hubs. It is built to focus on real-world return, comparing market prices across locations while taking fees, route expenses, and cargo limits into account before you move goods.

It is aimed at traders who need a fast way to sort through possible deals. By comparing hubs side by side and ranking results by ISK per jump and ISK per m3, it makes it easier to spot items worth hauling and routes worth prioritizing.

---

## Capabilities

- Cross-hub price comparison for EVE market items
- FLIP and LIST profit models for different trading approaches
- Net-of-fees calculations that factor in trading costs
- Route-based ranking by ISK per jump
- ISK per m3 ranking for cargo efficiency
- Editable inputs for tax, broker fee, freight, cargo size, and minimum volume
- Cached ESI route data for repeated lookups
- Hourly publish workflow for refreshed page builds

---

## Getting started

1. Download or clone the repository.
2. Open the generated web page in a browser, or publish the static files to your preferred hosting target.
3. If you are working locally, start from the HTML entry point in the repository folder.

Typical local workflow:

- Clone the repository
- Open the main HTML file in a browser
- Refresh after updating market inputs or rebuilding the published page

---

## How to use it

1. Pick the trade hubs you want to analyze.
2. Look at the spread between buy and sell prices.
3. Tune tax, broker fee, freight, cargo size, and minimum volume to fit your route.
4. Compare outcomes using FLIP or LIST style profit modeling.
5. Sort by ISK per jump or ISK per m3 to surface the most efficient trades.

Example workflow:

- Scan a hub pair
- Review net profit after fees
- Check route efficiency
- Filter out low-volume items
- Export or bookmark the opportunities you want to revisit

---

## Settings

Most options are configured directly in the page UI. Common inputs include:

- Tax rate
- Broker fee
- Freight cost
- Cargo size
- Minimum volume

If your deployment uses cached route data or published builds, those values are refreshed through the site workflow rather than a separate config file.

---

## Requirements

- Web browser with HTML support
- Access to EVE market data and route information through the published page
- Storage or hosting for the static web files if you are deploying it yourself
- ESI route data availability for cached route-based calculations

---

## FAQ

**How often is the page updated?**  
The build is published on an hourly workflow.

**Can I adjust the calculation inputs?**  
Yes. Tax, broker fee, freight, cargo size, and minimum volume are editable.

**Does it support route-aware ranking?**  
Yes. Opportunities can be ranked by ISK per jump as well as ISK per m3.

**What if the numbers look off?**  
Check the hub selection, fee inputs, cargo assumptions, and volume thresholds first.

**Where do I get the latest build?**  
Use the download link above to open the current published version.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
