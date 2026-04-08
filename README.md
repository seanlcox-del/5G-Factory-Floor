# 5G Home Ready: Factory Floor

An interactive pipeline visualization showing how Donor and MDU/MTU sites move through the 5G Home Ready deployment process.

## Overview

A single-page HTML dashboard built with vanilla JavaScript and SVG. Displays three pipeline sections — Donor Pre-Reqs, Donor Build, and MDU Build — with site counts, cycle times, and team ownership at each milestone.

## Features

- **Pipeline visualization** — Three connected SVG sections showing the full deployment workflow
- **Team color filtering** — Toggle team visibility to focus on specific workstreams
- **Node hover tooltips** — Hover over any milestone node to see label, team, count, and major milestone status
- **Cross-section connectors** — Visual links showing how Pre-Req completions feed into Donor Build
- **View By toggle** — Switch between Living Units and Sites

## Pipeline Sections

### Donor Pre-Reqs
Tracks eNSE Migration and 10G Capable project creation through Transport Pre-Reqs completion.

### Donor Build
Tracks sites from Mod Project Created through Closeout Package Complete, including Ready to Construct, On-Air, and all intermediate milestones.

### MDU Build
Tracks MDU/MTU sites from BAA Initiated through Closeout Package Complete, including Open For Sale and Activation/On-Air milestones.

## Teams

| Color | Team |
|-------|------|
| 🔴 Red | GN&T: 5G Home Ready Engineering |
| 🔵 Blue | VCG: Verizon Enhanced Communities (VEC) |
| 🟢 Green | GN&T: Transport / Access Engineering |
| 🟣 Purple | VCG: Product Management |

## Usage

Open `index.html` directly in any modern browser — no build step or server required.
