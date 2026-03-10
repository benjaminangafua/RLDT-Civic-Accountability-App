# Rural Liberia Data Trust (RLDT)

## Overview

The Rural Liberia Data Trust (RLDT) is an offline-first, community-governed platform designed to help rural communities in Liberia collect, review, steward, and share education data responsibly. It supports Good School Management Committees (GSMCs), parents, and local stakeholders with trustworthy evidence for local decision-making, accountability, and public dialogue.

## Problem

Rural education communities often lack reliable, locally controlled data to monitor school performance, track commitments, and advocate for support. Existing systems are often centralized, difficult to access, and not designed for low-connectivity environments.

## Solution

RLDT enables local data stewards to collect school indicators using solar-powered tablets and offline workflows. The system uses AI in a human-in-the-loop model to:

- flag missing or inconsistent records
- detect anomalies
- generate plain-language summaries
- produce community-facing scorecards and decision packets

All public sharing is governed by community-defined rules through GSMCs.

## Core Features

- Offline-first data collection
- Solar-powered tablet support
- Community-governed data stewardship
- AI-assisted integrity checks
- Plain-language scorecards
- Decision packet generation
- Controlled public data sharing
- Sync when connectivity becomes available
- Audit trail for review and approval

## Pillar Alignment

This project aligns with Mozilla’s Democracy × AI goals by:

- enabling better information
- strengthening institutional transparency and accountability
- expanding civic participation through community evidence review

## How It Works

1. Local data stewards collect school data offline.
2. The system stores records on-device.
3. AI-assisted checks flag potential issues.
4. GSMCs review flagged records and decide what is valid.
5. The app generates scorecards and decision packets.
6. Approved, non-sensitive data can be shared publicly.
7. Data syncs to the server when internet becomes available.

## Users

- Good School Management Committees (GSMCs)
- Parents and caregivers
- Community education stakeholders
- Teachers and school leaders
- District education authorities
- Rebuild Africa implementation teams

## Technology Stack

### Frontend

- React / TypeScript
- Progressive Web App (PWA)
- IndexedDB for offline storage
- Service Worker

### Backend

- Node.js / Express
- PostgreSQL or SQLite
- Sync API

### AI Layer

- Rule-based anomaly detection
- Summary generation
- Human-in-the-loop review workflow

## Project Structure

```bash
rldt/
├── client/             # Frontend PWA
├── server/             # Backend API and sync engine
├── shared/             # Shared types and utilities
├── docs/               # Documentation
├── data-models/        # Schemas and sample data
├── scripts/            # Utility scripts
└── README.md
```
