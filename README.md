# Button-Card Playground

An interactive reference and YAML code generator for [`custom:button-card`](https://github.com/custom-cards/button-card) — offered freely to the Home Assistant community.

## What it does

One job: you adjust controls, it generates YAML. Cut and paste that YAML into your own Lovelace dashboard.

- **15 chapters** covering all button-card features from basic visibility to advanced JS templates
- **3 interactive examples per chapter** with named presets for instant configuration
- **Live YAML output** updates as you change controls — always paste-ready
- **Chapter summary card** at the end of each chapter combining all features
- **No HA connection required** — works as a standalone panel or plain HTML file

## Coverage

| Level | Topics |
|---|---|
| L1 — Foundations | Display toggles, color & color_type, size, aspect ratio, layout blocks |
| L2 — Composition | State-aware styling, CSS styles, button groups, pictures, actions, finishing touches |
| L3 — Dynamic | JS templates, living values, card templates, variables, custom fields, conditional CSS |
| L4 — Advanced | Protection & locks, action sequences, JS actions, event bus, live streams, polling |

## Install via HACS

1. Open HACS → Frontend
2. Search **Button-Card Playground**
3. Download and add as a Lovelace resource
4. Add a panel to your sidebar

## Manual install

Copy `playground/controls.html` and `playground/preview.html` to your HA `www/` folder and open from the browser.

## Requirements

- Home Assistant (any recent version)
- [`custom:button-card`](https://github.com/custom-cards/button-card) installed via HACS

## Related

This playground is **Tool 1** of two companion tools for HA dashboard styling:

- **Button-Card Playground** (this tool) — per-card YAML generation
- **[HA Theme Builder](https://github.com/ohthedufner/ha-theme-builder)** — live native theme creation with real-time dashboard preview

## Credits

Built with appreciation for the original [button-card](https://github.com/custom-cards/button-card) by RomRider and contributors.
