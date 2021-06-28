# Changelog (unreleased)

## [Unreleased]

### Added

- in `sequences.v`:
  + lemmas `seriesN`, `seriesD`, `seriesZ`, `is_cvg_seriesN`, `lim_seriesN`,
    `is_cvg_seriesZ`, `lim_seriesZ`, `is_cvg_seriesD`, `lim_seriesD`,
    `is_cvg_seriesB`, `lim_seriesB`, `lim_series_le`, `lim_series_norm`

### Changed

- in `measure.v`:
  + generalize lemma `eq_bigcupB_of`

### Renamed

- in `classical_sets.v`:
  + `bigsetU` -> `bigcup`
  + `bigsetI` -> `bigcap`
  + `trivIset_bigUI` -> `trivIset_bigsetUI`
- in `measure.v`:
  + `B_of` -> `seqD`
  + `trivIset_B_of` -> `trivIset_seqD`
  + `UB_of` -> `setU_seqD`
  + `bigUB_of` -> `bigsetU_seqD`
  + `eq_bigsetUB_of` -> `eq_bigsetU_seqD`
  + `eq_bigcupB_of` -> `eq_bigcup_seqD`
  + `eq_bigcupB_of_bigsetU` -> `eq_bigcup_seqD_bigsetU`

### Removed

### Infrastructure

### Misc
