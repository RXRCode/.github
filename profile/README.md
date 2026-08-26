<div align="center">

<h1>RXRCode</h1>

<h3>Software for the work behind commerce.</h3>

<p>
  Products · Client engineering · Open source
</p>

<p>
  <a href="https://rxrcode.dev">
    <img src="https://img.shields.io/badge/rxrcode.dev-6DC6DA?style=for-the-badge&logo=googlechrome&logoColor=0D1117" alt="RXRCode Website">
  </a>
  &nbsp;
  <a href="mailto:contact@rxrcode.dev">
    <img src="https://img.shields.io/badge/contact-111827?style=for-the-badge&logo=minutemailer&logoColor=6DC6DA" alt="Contact RXRCode">
  </a>
</p>

<code>BUILDING FOR MERCHANTS · COMMERCE TEAMS · DEVELOPERS</code>

</div>

---

## `> whoami`

**RXRCode** is an independent founder-led software studio building focused products, client systems, and open-source developer infrastructure around the operational work behind commerce.

Our public work currently goes deepest in Shopify, with a broader focus on **storefront quality, product workflows, operational systems, integrations, automation, and developer tooling**.

```yaml
organization: RXRCode
website: https://rxrcode.dev

work:
  - Products
  - Client Engineering
  - Open Source

principles:
  - observable
  - structured
  - deliberate
  - operable
```

---

# Products

<table>
<tr>
<td width="50%" valign="top">

<h3>StoreProof</h3>

<p><strong>Storefront QA, with proof.</strong></p>

<p>
Real-browser Shopify storefront QA that separates health, coverage, and confidence, then records evidence behind the result.
</p>

<p>
<img src="https://img.shields.io/badge/STATUS-PUBLIC_BETA-6DC6DA?style=flat-square&labelColor=111827">
<img src="https://img.shields.io/badge/READINESS-PAID_BETA_READY-111827?style=flat-square&labelColor=0D1117">
</p>

<p>
Production acceptance is complete. Current validation is focused on founder-led outreach with Shopify agencies, freelancers, and merchants before broader feature expansion.
</p>

<a href="https://storeproof.rxrcode.dev"><strong>Explore StoreProof →</strong></a>

</td>
<td width="50%" valign="top">

<h3>CatalogCue</h3>

<p><strong>Grounded Shopify product-to-content workflows.</strong></p>

<p>
An embedded Shopify app that turns verified product information into review-ready blog drafts while keeping merchants in control of review and saving.
</p>

<p>
<img src="https://img.shields.io/badge/STATUS-PRIVATE_DEVELOPMENT-6DC6DA?style=flat-square&labelColor=111827">
<img src="https://img.shields.io/badge/VERSION-v0.9.1-111827?style=flat-square&labelColor=0D1117">
</p>

<p>
The manual generation and Shopify draft-save flow is implemented. Current work is development-store smoke testing, broader integration coverage, deployment hardening, and beta preparation.
</p>

<a href="https://rxrcode.dev/catalogcue"><strong>CatalogCue status →</strong></a>

</td>
</tr>
</table>

---

# Open source

<table>
<tr>
<td width="50%" valign="top">

<h3>Shopify Fixtures</h3>

<p><strong>Reproducible development data for Shopify.</strong></p>

<p>
A conservative CLI for generating, validating, diffing, pulling, and safely applying deterministic Shopify development-store fixture state.
</p>

<p>
<img src="https://img.shields.io/badge/STATUS-v0.2_PRERELEASE-6DC6DA?style=flat-square&labelColor=111827">
<img src="https://img.shields.io/badge/NPM-next-111827?style=flat-square&labelColor=0D1117">
<img src="https://img.shields.io/badge/LICENSE-MIT-111827?style=flat-square&labelColor=0D1117">
</p>

<a href="https://github.com/RXRCode/shopify-fixtures"><strong>GitHub →</strong></a>
 ·  <a href="https://www.npmjs.com/package/@rxrcode/shopify-fixtures"><strong>npm →</strong></a>

</td>
<td width="50%" valign="top">

<h3>Catalog Parity</h3>

<p><strong>Compare commerce catalogs before migrations go live.</strong></p>

<p>
An offline, deterministic CLI for comparing source and target CSV/JSON catalog exports, surfacing missing records, unexpected records, and field-level drift.
</p>

<p>
<img src="https://img.shields.io/badge/STATUS-v0.1.x_PRERELEASE-6DC6DA?style=flat-square&labelColor=111827">
<img src="https://img.shields.io/badge/PROCESSING-LOCAL_ONLY-111827?style=flat-square&labelColor=0D1117">
<img src="https://img.shields.io/badge/LICENSE-MIT-111827?style=flat-square&labelColor=0D1117">
</p>

<a href="https://github.com/RXRCode/catalog-parity"><strong>GitHub →</strong></a>
 ·  <a href="https://www.npmjs.com/package/@rxrcode/catalog-parity"><strong>npm →</strong></a>

</td>
</tr>
</table>

---

## `> current_builds`

| Project              | Type            | Current state                 | Current direction                                                                    |
| -------------------- | --------------- | ----------------------------- | ------------------------------------------------------------------------------------ |
| **StoreProof**       | Product         | Public beta · paid-beta ready | Validate repeat use and willingness to pay with agencies, freelancers, and merchants |
| **CatalogCue**       | Shopify app     | Private development · v0.9.1  | Smoke test the full Shopify workflow, harden deployment, prepare beta                |
| **Shopify Fixtures** | Open-source CLI | v0.2 prerelease on npm `next` | Expand safe update support and development-store workflows                           |
| **Catalog Parity**   | Open-source CLI | v0.1.x prerelease             | Validate migration/reconciliation workflows and CI use cases                         |

---

# Client engineering

Some commerce problems need a reusable product. Others need a system built around the business.

RXRCode works selectively with commerce teams on:

```text
storefronts        → customer-facing commerce experiences
custom apps        → purpose-built operational software
integrations       → systems that need to exchange data reliably
automation         → repetitive workflows that should not stay manual
```

The goal is **clearer workflows, observable systems, and software that remains operable after launch.**

[Start a project →](https://rxrcode.dev/contact)

---

## `> engineering_principles`

### Observable

Important behavior should be visible. Failures, state changes, and outcomes should be understandable without guesswork.

### Structured

Turn ambiguous operational work into explicit inputs, states, actions, and outputs.

### Deliberate

Solve the actual workflow before expanding the feature set. Choose technology because it improves the system, not because it is available.

### Operable

Shipping is not the end of the engineering problem. Software should remain understandable, maintainable, recoverable, and useful in production.

```diff
+ Solve real operational problems.
+ Make important behavior observable.
+ Prefer explicit workflows over hidden complexity.
+ Keep products focused enough to understand.
+ Build systems people can continue to operate.

- Complexity for complexity's sake.
- Features without a clear job.
- Technology as the product story.
- Hidden operational state.
- Experiments presented as finished products.
```

---

## `> current_ecosystem`

Our public work currently goes deepest in the Shopify ecosystem.

<p align="left">
<img src="https://img.shields.io/badge/Shopify-111827?style=for-the-badge&logo=shopify&logoColor=6DC6DA">
<img src="https://img.shields.io/badge/TypeScript-111827?style=for-the-badge&logo=typescript&logoColor=6DC6DA">
<img src="https://img.shields.io/badge/React-111827?style=for-the-badge&logo=react&logoColor=6DC6DA">
<img src="https://img.shields.io/badge/Next.js-111827?style=for-the-badge&logo=nextdotjs&logoColor=6DC6DA">
<img src="https://img.shields.io/badge/Node.js-111827?style=for-the-badge&logo=nodedotjs&logoColor=6DC6DA">
<img src="https://img.shields.io/badge/GitHub-111827?style=for-the-badge&logo=github&logoColor=6DC6DA">
</p>

<sub>Tools can change. The engineering discipline stays deliberate.</sub>

---

## Work with RXRCode

**Website** · https://rxrcode.dev
**Start a project** · https://rxrcode.dev/contact
**Email** · [contact@rxrcode.dev](mailto:contact@rxrcode.dev)
**Open source** · https://github.com/RXRCode

---

<div align="center">

### `build useful software // make the work clearer`

<strong>RXRCode</strong>

<sub>Products · Client engineering · Open source</sub>

<br><br>

<a href="https://rxrcode.dev">rxrcode.dev</a>

</div>
