
# Dataset Documentation

## Purpose

This folder will contain the documentation and organization of cattle-feed images used for developing the Pashu Poshan visual quality classification model.

## Planned Feed Types

1. Green fodder
2. Dry fodder
3. Silage

The final feed types will depend on data availability and the feasibility of assigning reliable quality labels.

## Quality Categories

| Label | Category | Description |
|---|---|---|
| 0 | Good | Feed assessed as good visual quality using documented criteria appropriate to its type. |
| 1 | Moderate | Feed showing intermediate visual quality based on the agreed criteria. |
| 2 | Poor | Feed showing visible quality defects according to the agreed criteria. |

These labels are provisional. They must be defined and validated with appropriate expert guidance before training.

## Data Sources

- Publicly available datasets, subject to their licenses.
- Images collected with permission from farms or livestock facilities.
- Expert-supported image assessments, wherever possible.

## Planned Folder Structure

```text
dataset/
├── README.md
├── raw/
│   ├── green_fodder/
│   ├── dry_fodder/
│   └── silage/
└── processed/
```

Raw images and processed datasets will not be committed to GitHub until their size, licensing, and privacy implications have been checked.

## Data Collection Status

Not started.

No dataset has been collected, labelled, or validated yet.
