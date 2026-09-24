# Exposure Report — Logistics Exception Radar

> Date: 2026-09-24  
> Project: logistics-exception-radar  
> Checker: rg with sensitive patterns

## Files checked

- `README.md`
- `assets/architecture.mmd`
- `assets/dashboard-mockup.html`
- `assets/dashboard-mockup.png` (visual inspection only)

## Patterns checked

- `coordinadora`
- `cm-analitica`
- `ext_`
- `dwh_`
- `public_`
- `novedad`
- `sigo`
- `890904713`
- `@coordinadora\.com`
- `hcanaval@coordinadora\.com`
- revision-style hashes
- long alphanumeric identifiers
- `projects/[a-z0-9-]+`

## Result

No sensitive patterns found in any text file.

## Visual assets reviewed

- `assets/dashboard-mockup.png` contains only fictional data:
  - fake shipment IDs (SH-9011029, etc.)
  - fake depots (Portville North, Riverside, Lakeview)
  - generic verdicts and reasons
- No real route codes, event codes, or operational identifiers.

## Conclusion

Safe to publish.
