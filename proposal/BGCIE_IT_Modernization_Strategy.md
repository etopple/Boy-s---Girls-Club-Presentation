# BGCIE IT Modernization Strategy

## Executive Context & Proposed Direction

------------------------------------------------------------------------

# 1. Current State Overview

## Monthly Recurring Cost (Current)

-   **\$6,500/month (discounted from \$8,000)**
-   Infrastructure-based billing model:
    -   8 Servers @ \$250 each = \$2,000/month
    -   45 Endpoints @ \$100 each
    -   7 Switches
    -   3 Firewalls
    -   7 Access Points
    -   Software support (Microsoft + Adobe)
    -   Additional location support

## San Bernardino Buildout

-   \$29,169.95 total one-time spend
-   Meraki hardware with 5-year licenses:
    -   Switches
    -   Firewalls (MX68)
    -   Access Points (MR36)
    -   Advanced Security subscriptions
-   Additional MRC increase of \$380/month

------------------------------------------------------------------------

# 2. Structural Observations

The current IT model is:

-   Server-dependent
-   VPN-dependent
-   Infrastructure-billed
-   Renewal-based (5-year licensing cycles)
-   Reactive to hardware lifecycle

This model inherently:

-   Encourages hardware growth
-   Creates renewal cliffs
-   Produces capital replacement events
-   Ties MRC to asset count

------------------------------------------------------------------------

# 3. Identified Risk Categories

## Step 1 --- Infrastructure Dependency Risk

**Current** - 8 billed servers - S: drive reliance - VPN required for
file access

**Risk** - Hardware failure - Replacement event - Ransomware exposure -
Access disruption

**Probability:** Medium--High\
**Financial Impact:** - \$24,000/year in server coverage - \$15k--\$30k
potential replacement event

------------------------------------------------------------------------

## Step 2 --- Licensing & Renewal Cliff Risk

**Current** - Meraki 5-year licenses - Advanced Security subscriptions -
Mixed Microsoft licensing model

**Risk** - Renewal spikes - Forced upgrade cycle - Budget instability

**Probability:** Certain\
**Financial Impact:** - Significant renewal events - Continued
overlapping licensing spend

------------------------------------------------------------------------

## Step 3 --- Operational Productivity Risk

**Current** - VPN dependency - Devices not Entra joined - Local data
storage - Executive low tolerance for downtime

**Risk** - Remote access failure - Device failure downtime - Staff
workarounds

**Probability:** Medium--High\
**Financial Impact:** - Productivity loss - Support labor - Executive
disruption

------------------------------------------------------------------------

## Step 4 --- Cost Escalation Risk

**Current** - MRC tied to asset count - Hardware additions increase
MRC - Infrastructure growth increases cost

**Risk** - Scaling penalty - Continued MRC increases

**Probability:** High\
**Financial Impact:** - Ongoing inflation of monthly spend

------------------------------------------------------------------------

# 4. Proposed Operating Model Shift

Not better support ---\
**A different model.**

## Core Principles

-   Cloud-first (no server dependency)
-   VPN as exception, not daily workflow
-   Microsoft 365 Business Premium for all users (\$5.78/user nonprofit)
-   Controlled storage footprint (\<1.5 TB target)
-   Entra-joined endpoints with Known Folder Move
-   Simplified UniFi-based network stack
-   Governance-based pricing (not per-asset billing)

------------------------------------------------------------------------

# 5. What Disappears

-   8 server billing line items
-   Server replacement cycle
-   VPN dependency for files
-   Meraki renewal cliffs
-   Fragmented licensing confusion
-   Infrastructure-based billing logic

------------------------------------------------------------------------

# 6. Proposed Project Buckets

## 1. Microsoft 365 / SharePoint / OneDrive Modernization

-   Business Premium standardization
-   Data migration
-   Storage cleanup & archive
-   Removal of server dependency

## 2. Endpoint Reset & Entra Join

-   Device wipe & rebuild
-   Security baseline deployment
-   Known Folder Move enabled

## 3. Network Standardization (Supporting Scope)

-   Replace Meraki & legacy hardware
-   Deploy UniFi UDM + switches + APs
-   Remove renewal licensing
-   Align network with cloud-first workflows

## 4. Server Decommissioning

-   Validate migration
-   Retire server infrastructure
-   Remove monitoring & patching

## 5. VPN Dependency Reduction

-   Validate workflows without VPN
-   Retain only if required for edge cases

## 6. Post-Cutover Stabilization

-   Support window
-   User guidance
-   Final adjustments

------------------------------------------------------------------------

# 7. Financial Reframe

## Current

-   \$6,500/month
-   Renewal cliffs ahead
-   Server replacement risk
-   Infrastructure growth increases MRC

## Proposed

-   **\$8,000/month**
-   No server replacement cycle
-   No Meraki renewal cliff
-   Standardized Microsoft licensing
-   Simplified infrastructure
-   Governance-based pricing

This is not a \$1,500 increase.

This is: - Removal of capital spikes - Removal of renewal events -
Reduction of volatility - Stabilization of risk profile

------------------------------------------------------------------------

# 8. Executive Positioning

This is not a vendor switch.

This is a risk profile shift.

**Today:** Funding infrastructure maintenance.

**Future:** Funding operational stability.

------------------------------------------------------------------------

# 9. Core Close Line

> The question is not whether IT costs \$6,500 or \$8,000.
>
> The question is whether we continue funding infrastructure risk ---\
> or transition to a model that removes it.
