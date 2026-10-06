# Reliability DA · LinkTree

Internal link hub for the LUMA Energy Reliability DA team — quick access to guidelines, Microsoft Forms, trackers/reports, and interactive engineering tools.

## Structure

```
├── index.html                       # Home (LinkTree)
├── guideline-library.html           # Guideline Library
├── field-forms.html                 # Microsoft Forms
├── trackers-reports.html            # Trackers & Reports
├── tools.html                       # Tools hub
├── cmi-avoidance-metric.html        # Power BI embed
├── ip-calculator.html               # IP Calculator
├── metering-calculator.html         # Metering Check
├── qr-code-generator.html           # QR Generator
├── ansi-overcurrent-calculator.html # ANSI Overcurrent Calculator
├── tcc-coordination-calculator.html # TCC Coordination Calculator
├── styles.css                       # Shared LUMA-branded stylesheet
├── assets/images/                   # Logos & guide thumbnails
└── docs/                            # Reference PDFs
```

Note: page filenames were normalized to kebab-case in July 2026 — update any old bookmarks or QR codes that pointed to the previous names (e.g. guides5.html, da_forms.html).

## Branding

Styled to the LUMA Energy palette (lumapr.com):

| Token | Hex |
|---|---|
| Navy | `#14214B` |
| Green | `#79A941` |
| Blue accent | `#1F3A7A` |
| Background | `#EEF2F6` / white cards |

Typography: **Dubai** (official webfont via jsDelivr, DM Sans fallback).

All pages share `styles.css`; the palette lives in the `:root` CSS variables, so future rebrands only require editing that block.

---
Developed by Eiden O. García Torres
