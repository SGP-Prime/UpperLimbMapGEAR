# Upper Limb Map — GEAR

Interactive brachial plexus map for regional anaesthesia education.

Built for **GEAR — Grupo de Ecografia e Anestesia Regional** as part of Resident Lesson 1.

## Live demo

Once GitHub Pages is enabled for this repository, the map will be served at:

<https://sgp-prime.github.io/UpperLimbMapGEAR/>

## What it does

A topological schematic of the brachial plexus — roots, trunks, divisions, cords, terminal nerves, all named sub-branches down to the digital nerves — with twenty ultrasound-guided nerve blocks overlaid as toggleable colour-coded zones.

- **Interactive block toggles**: every block can be turned on or off individually from the sidebar; each is grouped by anatomical level (proximal plexus → supraclavicular → cords → axilla → upper arm → elbow → forearm → hand).
- **Curated presets**: one-click subsets — *Plexus only*, *Phrenic-sparing*, *Distal only*, *Selective branches*, plus *Show all* and *Hide all*.
- **Family-by-level colour scheme**: orange for proximal plexus, magenta for supraclavicular, purple for cords, blue for axilla, teal for upper arm, red for elbow, olive for forearm, brown for hand.

Companion innervation maps (skin, muscle, bone, joint capsule) are planned and will be added in subsequent revisions.

## Blocks included (20)

| Level                  | Blocks                                                                            |
| ---------------------- | --------------------------------------------------------------------------------- |
| Proximal plexus        | Interscalene · Superior trunk · Suprascapular nerve                               |
| Supraclavicular        | Supraclavicular                                                                   |
| Cords (infraclavicular)| Infraclavicular (lateral sagittal) · Costoclavicular                              |
| Axilla / terminal      | Axillary BPB · Axillary nerve (selective) · ITM plane · Intercostobrachial        |
| Upper arm              | Mid-humeral / humeral canal                                                       |
| Elbow                  | Median · Radial · Ulnar · Lateral cutaneous of forearm (LCNF)                     |
| Forearm                | Median · Ulnar · Radial · Posterior interosseous (PIN)                            |
| Hand / digital         | Digital nerve block                                                                |

## File structure

```
UpperLimbMapGEAR/
├── index.html      # the interactive map — fully self-contained, all SVGs and JS inlined
└── README.md
```

No build step, no dependencies, no internet required at runtime. Drop into any static host or open `index.html` directly in a browser.

## Deployment

GitHub Pages, single-branch:

1. Settings → Pages → Source: `Deploy from a branch`, branch `main`, folder `/ (root)`.
2. Save. After a few minutes GitHub Pages will publish the site at the URL above.

## License

To be decided — currently all rights reserved by GEAR.

---

Built with the assistance of [Claude](https://claude.ai).
