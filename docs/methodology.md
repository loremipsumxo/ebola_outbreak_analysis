# Methodology

## Data Source

This project uses the WHO / HDX Ebola Cases and Deaths Dataset as the analytical source of record.

The public repository includes processed datasets derived from the WHO/HDX
source. The raw source file is excluded from the public repo; it can be
downloaded from HDX if full raw-data reproduction is needed.

## Data Grain

The processed analytical dataset uses one row per country-date.

The original source data is long-format, with rows organized by country, date,
and indicator. The analysis uses two cumulative indicators:

- `Cumulative number of confirmed, probable and suspected Ebola cases`
- `Cumulative number of confirmed, probable and suspected Ebola deaths`

These are not confirmed-only counts.

## Cleaning Decisions

The project excludes `Liberia 2` and `Guinea 2` from the primary country-level
dataset. Directly merging those continuation labels into `Liberia` and `Guinea`
creates duplicate country-date rows, so they are excluded to preserve the
analytical grain.

## Derived Fields

The notebooks and Tableau datasets use:

- Final cumulative cases by country
- Final cumulative deaths by country
- Case fatality ratio: deaths divided by cases
- Top-three country time series for Guinea, Liberia, and Sierra Leone

## Validation

Validation checks included:

- Required columns and date parsing
- Country count
- Duplicate country-date rows
- Final country totals
- CFR denominator checks for small outbreaks

## Limitations

- Counts include confirmed, probable, and suspected cases/deaths.
- WHO/HDX totals may differ from later retrospective reports.
- Period-to-period changes are derived from cumulative totals and are not true incidence.
- CFR values for small outbreaks are unstable descriptive ratios.
- Dataset trends and dashboard visuals do not prove intervention effects.
