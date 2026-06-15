# Sindhi karṇu Complex Verb Dataset

This repository contains a dataset of complex verb constructions formed with 
the Sindhi light verb ڪرڻ (karṇu, "to do"), extracted from the Mewaram 
Sindhi-English Dictionary (University of Chicago Digital South Asia Library).

## Contents

- `actual_extraction` — raw extracted entries containing ڪرڻ, including 
  headword, page number, construction, English meaning, and full dictionary 
  entry text.
- `extraction_argument_structure_column` — the same data with an added 
  `ArgStr` column, manually annotated for argument structure (Agent/Theme/
  Experiencer/Stimulus and associated case markers or postpositions).

## Source

Mewaram Sindhi-English Dictionary, Digital South Asia Library, 
University of Chicago: https://dsal.uchicago.edu/dictionaries/mewaram

## Method

Entries were extracted using a Python script (requests + lxml) targeting 
headwords containing ڪرڻ, cleaned and filtered, then manually annotated for 
argument structure as part of a term paper on light verb constructions in 
Sindhi (Linguistics, HSE University, 2026).
