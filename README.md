# TaxID2Lineage
# Language: Python
# Input: TXT
# Output: TSV
# Tested with: PluMA 1.1, Python 3.6

PluMA plugin to obtain lineage from taxonomic identifiers

The plugin takes as input a tab-delimited file of keyword-value pairs:
input: Ensembl bacteria species (TXT)
input_skiprows: 0 or 1
linage_file: Input lineages file
tax_col: Column of taxonomic id
include_columns: Columns to use for lineage
include_column_names: Column names to use for lineage
email: Your e-mail address

New lineage file will be in TSV format
