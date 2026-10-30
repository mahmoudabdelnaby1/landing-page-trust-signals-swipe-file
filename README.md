# Landing Page Trust Signals & Regulatory Compliance Swipe File

> Review editable trust-signal examples and copy patterns for Arabic landing pages. Use official assets only when authorized and display regulatory credentials only when they apply to the business.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Format: CURATED_DATASET](https://img.shields.io/badge/Format-CURATED--DATASET-green.svg)](#)
[![Tier: 1](https://img.shields.io/badge/Tier-1-orange.svg)](#)
[![Region: MENA](https://img.shields.io/badge/Region-Egypt%20%7C%20GCC%20%7C%20Saudi-purple.svg)](#)
[![Tests: Passing](https://img.shields.io/badge/Tests-Passing-brightgreen.svg)](#)
[![Owner: mahmoudabdelnaby1](https://img.shields.io/badge/Owner-mahmoudabdelnaby1-blue.svg)](https://github.com/mahmoudabdelnaby1)

---

## 📌 Problem Statement & Target Persona

### Target Persona
**BOTH** operating in high-growth e-commerce, digital publishing, and direct-response marketing across Saudi Arabia, UAE, and Egypt.

### Core Problem
Build an open-source landing page trust signals repository for MENA: 1) illustrative trust-strip and badge examples; do not use third-party or regulatory marks without authorization and current eligibility, 2) Responsive, accessible HTML/CSS trust strip components, 3) Bilingual Arabic/English micro-copy swipe file for refund, privacy, and shipping guarantees, 4) Placement best practice guide.

---

## 🛠️ Repository Architecture & Deliverables

This repository provides self-contained, documented implementations and specifications:

- `assets/svg-badges/mawthooq-verified.svg`
- `components/trust-strip-responsive.html`
- `components/trust-strip.css`
- `data/trust_signals_library.json`
- `docs/mena-trust-psychology.md`
- `docs/trust-architecture-guide.md`
- `examples/preview_gallery.html`
- `LICENSE`
- `README.md`
- `SOURCES.md`
- `swipe-file/guarantee-microcopy-ar-en.md`
- `tests/test_data_integrity.py`


---

## 🚀 Quick Start & How to Run Locally

### Run Test Suite Locally
```bash
# Ensure no bytecode generation
export PYTHONDONTWRITEBYTECODE=1  # Linux / macOS
$env:PYTHONDONTWRITEBYTECODE="1"  # Windows PowerShell

# Run Python unittest discovery
python -m unittest discover -s tests
```

### Interactive Browser Tool
Open `components/trust-strip-responsive.html` directly in your web browser (Chrome, Edge, Safari) to use the local interactive calculator or dashboard. Operates 100% client-side with zero external network calls.

---

## 📊 Sample Input & Output Fixtures

> **Data Disclosure:** Any included sample data is illustrative and may be synthetic; it is not a measured customer result or market benchmark unless a source and collection method are stated alongside it. These files run offline with standard libraries and require no paid third-party API credentials.

```json
{
  "domain": "cro",
  "repository": "landing-page-trust-signals-swipe-file",
  "status": "READY_FOR_LOCAL_REVIEW",
  "license": "MIT"
}
```

---

## ⚠️ Known Technical & Domain Constraints

- **Saudi Statutory Disclosures:** E-commerce landing pages in KSA must prominently display CR number, VAT tax registration number, and physical commercial address.
- **Payment Gateway Badge Accuracy:** Merchant badges must accurately reflect authorized regional payment networks (Mada, Apple Pay, Tabby, Tamara).
- **Truth in Advertising Regulations:** Prohibits unsubstantiated '100% Satisfaction' or '#1 in Market' claims without auditable proof to comply with consumer protection laws.

---

## 📚 Primary Documentation & Verifiable References

- [Saudi Ministry of Commerce: E-Commerce Executive Regulations](https://mc.gov.sa/) - Mandatory merchant disclosures and consumer protection guidelines in Saudi Arabia.
- [Saudi General Authority for Media Regulation (GAMR)](https://gcam.gov.sa/) - Statutory advertising standards and compliance requirements.
- [Saudi Central Bank (SAMA): Authorized Payment Gateways Directory](https://www.sama.gov.sa/) - Official register of authorized electronic payment services.

---


## 👤 Maintainer & License

- **Author & Maintainer:** [Mahmoud Abdelnaby](https://github.com/mahmoudabdelnaby1) (`@mahmoudabdelnaby1`)
- **License:** [MIT License](LICENSE) - Open-source, auditable, and freely adaptable for internal enterprise or commercial use.
