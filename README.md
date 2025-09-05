# NPH Detection Checklist — Prototype App

This is a static, client‑side prototype to help clinicians document features **suggestive of Normal Pressure Hydrocephalus (NPH)**. It provides a stepwise form, calculates the **Evans Index**, compares **pre/post tap‑test** metrics, and generates a printable summary.

## How to use
1. Download and unzip the folder.
2. Open `index.html` in any modern browser (Chrome, Edge, Safari, Firefox).
3. Work through Steps 1–6. On the Summary step you can **Save** (local browser), **Load**, **Export JSON**, or **Print/Save as PDF**.

## What it does
- Captures history, exam, imaging, tap‑test details, and exclusion of mimics
- Auto‑calculates **Evans Index** (frontal horn width ÷ inner skull diameter)
- Flags **notable improvements** (≥20% change) in gait metrics after tap test
- Produces a concise, printable **report**

## What it does **not** do
- It is **not** a diagnostic tool or medical device
- No server; **all data stays in your browser** (localStorage)
- The “overall” line is a cautious heuristic reminder to seek specialist evaluation — **not** a diagnosis

## Customize
- Edit thresholds or text inside `app.js` (e.g., % change for “notable” improvement)
- Add hospital logo or footer in `index.html`

## Safety
Use clinical judgement and local policies. Confirm imaging and clinical findings with appropriate specialists.
