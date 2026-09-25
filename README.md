# Amazon ML Challenge 2026 — Business Entity Resolution

Machine learning pipeline for resolving business entities across
multiple noisy and independent data sources.

## Problem

The challenge involves identifying records from Source 2 and Source 3
that correspond to entities in the deduplicated Source 1 reference
dataset.

The records contain noisy business names, addresses, country labels,
and other inconsistencies.

## Approach

The solution is organized into the following stages:

1. Data preprocessing
2. Entity normalization
3. Candidate generation / blocking
4. Similarity feature engineering
5. Match classification
6. Singleton detection
7. Validation and evaluation
8. Submission generation

## Project Structure

...

## Dataset

The challenge dataset is intentionally excluded from this repository
because of its size and competition constraints.

Expected local structure:

data/
├── train/
└── test/

## Setup

...

## Running the Pipeline

...

## Evaluation

The primary evaluation metric is F₀.₅, which places greater emphasis
on precision than recall.

## Output

The pipeline generates:

- `matching_results.tsv`
- `candidate_pairs.tsv`

## Reproducibility

...

## License

...
