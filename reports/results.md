results
================

# HYPOTHESES:

We hypothesized that:

  - H1. Adding soluble C would alleviate substrate limitation, whereas
    adding soluble N would alleviate resource limitation, resulting in
    increased microbial activity, i.e. **greater CO2 production**,
    **increased diversity in SOM compounds**, and a **relative depletion
    in complex/aromatic compounds**. These responses would be influenced
    by soil physico-chemical properties:
    
      - H1a. pore size: The effect of C additions would be greater in
        tightly-held pore water.
    
      - H1b. wetting direction: The effect of C amendments would be
        greater in cores wet from below, due to C limitation at greater
        soil depths. Conversely, the effect of N amendments would be
        greater in cores wet from above.
    
      - H1c. antecedent moisture conditions: Respiration response to C
        amendments would be greater in soils previously maintained at
        field moist conditions, compared to soils previously subjected
        to drought.

  - H2. Homogenization would increase the diversity and the aromaticity
    of pore-water DOC, and this effect would be comparable across all
    treatments (i.e., non-amended vs. C or N amended), regardless of
    resource availability.

-----

# FT-ICR-MS

## total peaks

total peak counts were influenced by:

  - not Homogenization
  - Suction (50 \> 1.5 kPa)
  - Moisture (drought \> fm)
  - not Wetting
  - Amendments (declines in N)

<!-- end list -->

``` r
readd(peakcounts_total_core)
```

    ## [1] NA

In intact cores, total peak counts were influenced by:

  - suction:wetting
  - moisture:wetting

<!-- end list -->

``` r
readd(aov_total_peaks_intact)
```

    ## [1] NA

## diversity of peaks

## complex/aromatic peaks

Aromatic peaks (i.e. complex:simple ratio) were influenced by:

  - Homogenization (homogenized \> intact)
  - Suction (50 kPa \> 1.5 kPa)
  - Moisture (drought \> fm)
  - Amendments (control \> C \> N)
  - not Wetting direction

<!-- end list -->

``` r
readd(aov_arom_aliph_ratio_all)
```

    ## [1] NA

For intact soils, Amendment effects were greater in fine pores than in
coarse pores

  - in coarse pores, no effect of amendment
  - in fine pores, both C and N amendments caused a relative depletion
    of complex compounds

<!-- end list -->

``` r
readd(gg_aliph_aromatic_intact_suction)
```

    ## [1] NA

# DOC

# RESPIRATION