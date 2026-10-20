# chemml-journey

**A synthetic organic chemist learning machine learning, one notebook at a time.**

I'm a PhD candidate at the Technical University of Munich, working on natural product synthesis using a photochemical key step.

Machine learning and cheminformatics are a new field for me, and I'm enjoying them a lot. So I'm putting in extra hours on weekends to learn them properly, and this repository is my learning log, kept in public.

## What's here

| Notebook | What it does |
|---|---|
| `01_first_molecules.ipynb` | Turns SMILES strings into structures and calculates molecular weights with RDKit |

## Where this is going

1. **Predicting reaction yields.** Training models on a public high-throughput dataset of ~4,000 Buchwald–Hartwig couplings (Ahneman et al., *Science* 2018), and checking whether what the model learns matches a chemist's intuition.
2. **AI retrosynthesis vs. the literature.** Running AiZynthFinder on published natural product targets and comparing its routes with the real total syntheses. How does it handle complex ring systems and protecting groups?

## How I work

Python, RDKit, pandas and scikit-learn, with Claude Code as a pair programmer. I set the questions, read and question every step, and check the results against the chemistry. The instructions I give the AI are in `CLAUDE.md`.

## Contact

[Demmy Yu] · [LinkedIn](https://www.linkedin.com/in/demmyyu)
