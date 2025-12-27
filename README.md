# Feline Genetics Tracker

A GitHub repository for tracking the genetics of a cat breeding program, focusing on sex-linked coat colors in calico and tortoiseshell cats.

This repository serves as a digital logbook for a British Shorthair breeding program. It documents genotypes and phenotypes of breeding cats, simulates mating outcomes, and uses GitHub workflows to plan and justify genetic predictions.

## Key Concepts

- **Sex-linked inheritance**: X and Y chromosomes determine sex and carry coat color alleles.
- **X-chromosome inactivation (lyonization)**: Random inactivation of one X chromosome in female mammalian cells leads to mosaic expression of coat color alleles in heterozygous females.
- **Calico vs. Tortoiseshell**: Both require a heterozygous X-linked genotype (X^B X^O) and random X-inactivation. Calico cats additionally express the autosomal white spotting gene (S) that creates large white patches.

## Repository Structure

- `cats/`: YAML files for each cat, recording name, sex, genotype, phenotype, and notes.
- `litters/`: YAML files documenting each litter, listing parents and resulting kittens.
- `README.md`: This file.