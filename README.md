# Akij Feed — Milling Production Performance / OEE Loss Diagnostic

Single-file HTML dashboard for **Akij Feed — Milling**, covering the **Poultry / Cattle / Layer / Fish (sinking & floating)** lines, shifts A–C.

## Features
- **Toggle:** Last completed day and Month-to-date
- OEE KPIs (Availability / Performance / Quality / Overall OEE) vs targets **A90 / P86 / Q97 / OEE75**
- Where time is going; OEE by line; Find-the-bottleneck
- Top downtime + downtime by category (min) — unplanned only
- **Opportunity Loss = NPT min ÷ cycle time (min/MT)** → lost output (MT)
- Production & OEE trend (last 16 days)
- Shift Action Board — downtime reasons with responsible-team tagging
- Shift OEE and Gemba walk

## Data source
`Production Report` (gid=1852840407) and `Breakdown` (gid=482789258) tabs of the Akij Feed OEE sheet.

## Notes
- OEE = Availability × Performance × Quality.
- Availability = Actual Run Time ÷ Planned Production Time (planned downtime excluded).
- Live: pulls the sheet on page open.
