![Alt Text](reference/figures/SACRO_Logo_final.png)

## AI-SDC Family Tools

[TABLE]

## ACRO-R: Statistical Disclosure Control

ACRO is a free and open source tool that supports the semi-automated
checking of research outputs (SACRO) for privacy disclosure within
secure data environments. SACRO is a framework that applies
best-practice principles-based statistical disclosure control (SDC)
techniques on-the-fly as researchers conduct their analysis. SACRO is
designed to assist human checkers rather than seeking to replace them as
with current automated rules-based approaches.

## What is ACRO-R?

ACRO implements a principles-based statistical disclosure control (SDC)
methodology that:

- Automatically identifies potentially disclosive outputs
- Applies optional disclosure mitigation strategies
- Reports reasons for applying SDC
- Produces summary documents for output checkers

## Core Features

### Semi-Automated Disclosure Checking

- **Drop-in replacements** for common Python analysis commands (pandas,
  statsmodels, etc.) with configurable disclosure checks
- **Automated sensitivity tests** : frequency thresholds, dominance (p%,
  NK rules, etc.), residual degrees-of-freedom checks
- **Optional mitigations** : suppression, rounding, and more to come
- **Session management** : track, rename, comment, remove, add
  exceptions, and finalise reports
- **Configurable risk parameters** via YAML files
- **Generates auditable reports** in JSON or Excel

### Design Principles

- **Free and open source** under MIT (ACRO) / GPLv3 (SACRO Viewer)
- **Easy to install** via PyPI, CRAN, or GitHub; cross-platform (Linux,
  macOS, Windows)
- **Familiar APIs** - same function signatures as native commands:
  acro.crosstab mirrors pandas.crosstab, etc.
- **Comprehensive coverage** - tables, regressions, histograms, survival
  plots, etc.
- **Transparent & auditable** - clear reports, stored queries, designed
  for human-checkers
- **Configurable & extensible** - organisation-defined disclosure rules,
  multi-language support
- **Scalable** - lightweight, session-based, local execution

## Getting Started

[TABLE]
