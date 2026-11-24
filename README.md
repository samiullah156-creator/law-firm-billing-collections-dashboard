# LedgerLaw: Law Firm Billing & Collections Dashboard

**A finance dashboard on a law firm's billing data showing billed against collected, AR aging and the invoices that need a follow-up.**

![Legal](https://img.shields.io/badge/Legal-167dfe?style=flat-square) ![Legal finance dashboard](https://img.shields.io/badge/Legal%20finance%20dashboard-9533fa?style=flat-square) ![React](https://img.shields.io/badge/React-231f20?style=flat-square) ![Node.js](https://img.shields.io/badge/Node.js-231f20?style=flat-square) ![Python](https://img.shields.io/badge/Python-231f20?style=flat-square) ![Accounting API](https://img.shields.io/badge/Accounting%20API-231f20?style=flat-square) ![n8n](https://img.shields.io/badge/n8n-231f20?style=flat-square) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-231f20?style=flat-square)

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

React · Node.js · Python · Accounting API · n8n · PostgreSQL

## Demo

A working version of the dashboard UI with **sample data** is in [`demo/index.html`](demo/index.html). Download it and open it in a browser; it has no build step.

## Privacy

Client names and records are confidential. Every screen in this repository uses sample data, and source code that belongs to the client is not published.

## Links

- Case study on Lexvaxa: https://lexvaxa.com/work/law-firm-billing-collections-dashboard
- Built by **Ch Muhammad Samiullah** ([GitHub](https://github.com/samiullah156-creator)) at [Lexvaxa](https://lexvaxa.com)
