# Unifab CRM Prototype

A working, clickable prototype of the Ashlyticss CRM — configured specifically around **Unifab Engineering Project Pvt. Ltd.**'s order-to-cash workflow.

This is a demo, not the production build. It's a single self-contained `index.html` file (no backend, no dependencies) used to validate the product concept before the real system is built.

## What this demonstrates

The core product idea: a CRM whose pipeline stages, fields, and workflow are **configured per client** instead of forced into a generic sales-pipeline template. This prototype shows that configured specifically for a manufacturing/process-equipment client.

## Views included

- **Owner** — revenue trends, pipeline health, and an "Ask your business a question" panel that answers plain-language queries (e.g. *"Which orders are overdue?"*) directly from the live order data
- **Office** — structured order intake (no AI call transcription — human-confirmed structured entry only) and a live WhatsApp notification log
- **Factory** — active orders with deadlines and specs, with a "mark next stage" action that triggers WhatsApp-style client updates automatically

## Pipeline (Equipment Division)

Enquiry → Quote Sent → PO Received → In Production → QC / TPI → Dispatched → Payment Pending → Paid

## How to view it

Open `index.html` directly in any browser, or deploy this repo on [Vercel](https://vercel.com) for a live shareable link (auto-detects `index.html` as the entry point).

## Status

Prototype / concept demo stage. Production build (real backend, database, live WhatsApp Business API integration) not yet started.
