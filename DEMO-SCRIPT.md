# Pulse demo script

## Start and stop

1. Double-click **Start Demo.command**. Chrome opens at **http://pulse.localhost:8080**.
2. Close that Terminal window when you're done. That stops the demo.

The first time, macOS may ask whether Terminal can access your Downloads folder: click **Allow**.
No internet needed; React and the fonts are bundled in `vendor/`.

## The client

Clear Sky Energy, Tullamore. Colin Fogarty, Managing Director. The demo clock is fixed to
**Friday 25 September 2026, 16:00**, so Home always says "Good afternoon, Colin".
Every number comes from one shared data block (`CSE` near the top of the logic script); totals are computed, not typed.

## Deep links for rehearsal

`http://pulse.localhost:8080/?page=Jobs&sub=Customer%20Profile&job=J-1428`, `?page=Dashboard&aspect=wallboard`,
`?page=Warehouse&sub=Stock%20Takes`, `?page=Records&sub=Companies`.

## Questions Helios answers

| Ask | Helios shows | Key words it listens for |
|---|---|---|
| Are next week's installs covered? | 64 panels needed, 38 in stock, 3 installs short, PO for 40 | panels, installs, covered, PO, schedule |
| Who owes us money? | €58,740 across 11 invoices; Moran Agri €14,860, 41 days | owe, debtors, overdue, Moran, invoices |
| Where did that battery go? | €4,870 stock-take variance; LUNA2000 traced to J-1476 | battery, LUNA, stock take, variance, van |
| What's stuck in paperwork? | 9 jobs, €41,300 blocked, 5 SEAI pre-filled | paperwork, SEAI, NC6, certs, forms |
| Why did J-1428 lose margin? | 28% quoted, 16.5% actual, €5,580 unquoted | margin, costing, J-1428, motor |
| Why are leads down? | 74 in May, 31 in Sept, 14 waiting, 7 deposits | leads, deposits, quotes, marketing |
| Where are we slow? | Lead to cash 71 days vs 46; paperwork and deposits are the drag | slow, fast, report, performance |
| Where are the vans? | Crew A at Killeigh, Crew B at Kilbeggan, Jack on the N52 | vans, fleet, GPS |
| What goes out this week? | €23,235 to suppliers and subbies vs €30,910 due in | goes out, suppliers, bills, money out |
| Draft a chase for Moran Agri | A write tool: drafts it and waits for your yes | chase, email, draft, send |

## Moments to show

- **Home:** afternoon briefing, then approve the panel PO from "Needs you today".
- **Dashboard → Office Wallboard → Launch TV mode:** the screen for the office.
- **Jobs → Customer Profile:** Colin's whiteboard as 16 live steps. Mary Kenny is at step 11 of 16 (Jack's photos, design sent, picking lists by trade, BER booked). Also J-1428 and J-1476.
- **Whiteboard extras:** Warehouse → Movements (every scan in and out) and Reorders (suggested orders), Paperwork → Handover Packs, Finance → Cash In & Out, Crews → Vehicles (GPS map), Dashboard → Performance (where we're slow and fast).
- **Finance → Deposits → Send all:** Xero invoice + Stripe link + email in one click.
- **Settings → Governance:** nightly backups, 30-day history, EU data. Answers "it's not backed up".

## Watch out for

- **Stay in dark mode.** The Clear Sky blue and amber are tuned for dark.
