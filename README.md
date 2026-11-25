<!-- styled:v2 -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1d1726,50:167dfe,100:9533fa&height=180&section=header&text=LedgerLaw%3A%20Law%20Firm%20Billing%20%26%20Collections%20Dashboard&fontSize=25&fontColor=ffffff&fontAlignY=36&desc=Case%20study%20%E2%80%A2%20Legal%20%E2%80%A2%20Legal%20finance%20dashboard&descAlignY=58&descSize=16&animation=fadeIn" width="100%" alt="LedgerLaw: Law Firm Billing & Collections Dashboard" />

**A finance dashboard on a law firm's billing data showing billed against collected, AR aging and the invoices that need a follow-up.**

<p>
  <img src="https://img.shields.io/badge/Legal-167dfe?style=flat-square" alt="Legal" />
  <img src="https://img.shields.io/badge/Legal%20finance%20dashboard-9533fa?style=flat-square" alt="Legal finance dashboard" />
  <img src="https://img.shields.io/badge/React-231f20?style=flat-square" alt="React" />
  <img src="https://img.shields.io/badge/Node.js-231f20?style=flat-square" alt="Node.js" />
  <img src="https://img.shields.io/badge/Python-231f20?style=flat-square" alt="Python" />
  <img src="https://img.shields.io/badge/Accounting%20API-231f20?style=flat-square" alt="Accounting API" />
  <img src="https://img.shields.io/badge/n8n-231f20?style=flat-square" alt="n8n" />
  <img src="https://img.shields.io/badge/PostgreSQL-231f20?style=flat-square" alt="PostgreSQL" />
</p>

<p>
  <a href="#overview">Overview</a> ·
  <a href="#key-features">Key features</a> ·
  <a href="#results">Results</a> ·
  <a href="#tech-stack">Tech stack</a>
</p>

</div>

---

![LedgerLaw billing dashboard: billed, collected, collection rate, outstanding AR, billed vs collected chart, AR aging and open invoices.](assets/cover.webp)

## Overview

Billing and collection numbers had to be pulled together by hand from invoices and payments. Lexvaxa built LedgerLaw, a custom finance dashboard on the firm's billing data. It shows billed, collected and collection rate, billed against collected over time, revenue by practice area and invoice status, AR aging buckets and a list of the largest outstanding invoices. Screens shown use sample data, so no client records are exposed.

## The challenge

Partners waited for manual reports to see cash flow, and overdue invoices were easy to miss.

## The solution

n8n syncs invoices and payments from the accounting API into PostgreSQL, and a React dashboard shows collections, aging and overdue accounts live.

## Key features

- Billed, collected and collection rate
- Billed vs collected by month
- Outstanding AR and AR aging buckets
- Revenue by practice area and invoice status
- Largest open invoices with days outstanding

## Results

- Partners track cash flow and overdue accounts in one live view

## Tech stack

![React](https://img.shields.io/badge/React-1d1726?style=for-the-badge) ![Node.js](https://img.shields.io/badge/Node.js-1d1726?style=for-the-badge) ![Python](https://img.shields.io/badge/Python-1d1726?style=for-the-badge) ![Accounting API](https://img.shields.io/badge/Accounting%20API-1d1726?style=for-the-badge) ![n8n](https://img.shields.io/badge/n8n-1d1726?style=for-the-badge) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-1d1726?style=for-the-badge)

## Demo

A working version of the dashboard UI with **sample data** is in [`demo/index.html`](demo/index.html). Download it and open it in a browser; it has no build step.

## Privacy

Client names and records are confidential. Every screen in this repository uses sample data, and source code that belongs to the client is not published.

## Links

- Case study on Lexvaxa: https://lexvaxa.com/work/law-firm-billing-collections-dashboard

---

<div align="center">

**Built by [Ch Muhammad Samiullah](https://github.com/samiullah156-creator)** · AI Automation Engineer and Full-Stack Developer at [Lexvaxa](https://lexvaxa.com)

<a href="https://github.com/samiullah156-creator"><img src="https://img.shields.io/badge/More%20projects-181717?style=for-the-badge&logo=github&logoColor=white" alt="More projects" /></a>
<a href="https://lexvaxa.com/contact"><img src="https://img.shields.io/badge/Work%20with%20me-167dfe?style=for-the-badge&logo=googlecalendar&logoColor=white" alt="Work with me" /></a>
<a href="https://www.linkedin.com/in/sami-lexvaxa/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>

<sub>⭐ Star this repo if you found it useful</sub>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:9533fa,50:167dfe,100:1d1726&height=110&section=footer" width="100%" alt="" />
