# Project resume

Next action: None pending; change content in the private mock and rebuild.

Last update: 2026-11-17, Claude Code.

## Status

- Live at https://rodolfosilva.engineer (custom domain, HTTPS enforced). The old
  `rodolfodente-hue.github.io` addresses redirect to it.
- The portfolio at the site root is built from the private mock (v15 plus later
  edits) by a build script kept with the private work-samples project. Do not
  edit `index.html`, `img/`, `pdf/` or `prog/` here by hand: change the mock and
  rebuild, or the next build overwrites the edit.
- 2026-11-15: C-Clamp End added as the sixth CAM-programmed part (program,
  toolpath video, details panel), built from the mock.
- 2026-11-16: OD & ID Taper (RS-2003) updated from the mock: revised 10-operation
  program, new drawing (circular runout to ASME Y14.5-2018), toolpath video as
  Video 5 and in its panel, rewritten panel with a program review. The panel
  says the part was machined on a manual lathe and the CNC program is programmed and
  simulated in SolidWorks CAM; no measured values are shown. The video grid centers a fifth video under
  the 2x2.
- 2026-11-16: Face and Turn (RS-2001) and Simple Cylinder (RS-2002) drawings
  updated from the mock: new Rev A sheets and PDFs to ASME Y14.5-2018 and new
  drawing captions in their panels.
- 2026-11-16: C-Clamp End drawing RS-2004 Rev B: counterbore callout with position
  tolerance, hole limits .195/.189 with datum A, hidden-line profile; panel text
  and caption updated, built from the mock.
- 2026-11-17: milling drawings RS-2005..2009 replaced by the ASME Y14.5-2018
  versions (PDFs and drawing images); Milled Step Bar text now says two reamed
  holes and the T-Slot Nut panel says profile of a surface .005, built from the mock.
  The drawing image and PDF links carry `?v=2` so browsers fetch the new files
  instead of cached copies (commit `8904d2b`).
- 2026-11-17: toolpath videos moved into each part's details panel, under the
  drawing; the separate video grid on the machining page is removed (commit
  `c236646`). Part counts ("9 parts, 6 programmed" and similar) removed from the
  site on Rodolfo's instruction (commit `5ab6b30`). Both built from the mock.
- 2026-11-17: site review published (built from the work-samples branch
  `site-review-2026-11`): headline "Mechanical Engineer | Manufacturing & Quality
  Engineering", role tags on the Work cards, a KPI row and a "Skills and tools"
  footer on all 11 case studies, the unsupported Defect Tracking "Every case" result
  removed, Production Line Flow stations numbered S1-S13 and the defect reason cards
  lettered A-H (no shop names). `.gitattributes` marks PDFs binary.
- `cert/` holds the certificate and diploma copies linked from the Education page.
- `job-bot/` holds the two pages required by Google's app settings.

## Open tasks

- The domain renews at a high price; decide before it expires whether to keep it,
  move it to another registrar, or change domain. Auto-renew is off. Rodolfo
  deferred this on 2026-11-15; a one-time Claude Code routine emails him a
  reminder on 2027-09-15.

## Done

- 2026-11-15: the résumé request email (domain address, forwarded to Rodolfo's
  inbox) was tested and works.
