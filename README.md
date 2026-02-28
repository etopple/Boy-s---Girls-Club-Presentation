# BGCIE — IT Modernization Proposal Package

**Client:** Boys & Girls Clubs of the Inland Empire  
**Prepared by:** eTop Technology, Inc.  
**Date:** February 2026  
**Quote #:** WP001493

## Structure

```
├── proposal/          # Client-facing deliverables
│   ├── BGCIE_Cover_Letter.docx
│   ├── BGCIE_Cover_Letter.html
│   ├── eTop_Technology_Inc__WP001493_v1_10.pdf
│   └── BGCIE_IT_Modernization_Strategy.md
│
├── presentation/      # Slidev deck + speaker notes
│   ├── slides.md
│   └── package.json
│
└── internal/          # Internal analysis (do not share)
    └── BGCIE_Deal_Analysis_Internal.docx
```

## Proposal Summary

- **50 users** across Redlands and San Bernardino locations
- **$7,789/month** all-inclusive (managed services + M365 licensing)
- **$24,596.53** one-time migration and infrastructure project
- Replaces: aging server, Meraki networking, fragmented licensing, per-event billing model

## Running the Presentation

```bash
cd presentation
npm install
npm run dev
```

Opens at `localhost:3030`. Press **P** for presenter mode with speaker notes.
