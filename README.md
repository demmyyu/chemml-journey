# chemml-journey

**A synthetic organic chemist learning machine learning, one notebook at a time.**

I'm a PhD candidate at the Technical University of Munich, working on natural product synthesis using a photochemical key step.

Machine learning and cheminformatics are a new field for me, and I'm enjoying them a lot. So I'm putting in extra hours on weekends to learn them properly, and this repository is my learning log, kept in public.

## What's here

| Notebook | What it does |
|---|---|
| `01_first_molecules.ipynb` | Turns SMILES strings into structures and calculates molecular weights with RDKit |
| `02_python_basics.ipynb` | Python fundamentals for data work: lists, dictionaries, loops, functions, with exercises (in progress) |

## Where this is going

1. **When do chemical descriptors help predict yields?** Using a public high-throughput dataset of ~4,000 Pd-catalysed Buchwald–Hartwig aminations (Ahneman et al., *Science* 2018), I compare models trained on chemical descriptors, on simple component labels and on random numbers, following the debate in Chuang & Keiser (*Science* 2018). The real test is predicting additives and aryl halides the model has never seen.
2. **How many experiments does it take to find the best conditions?** A simulated optimisation campaign on the same dataset: random screening vs. model-guided experiment selection vs. a strategy I design as a chemist.
3. **Where does AI retrosynthesis fail on natural products?** Running AiZynthFinder on about 10 published natural products and comparing its routes with the real total syntheses. Which strategic steps does it miss: photochemistry, protecting groups, late-stage oxidations?

## How I work

Python, RDKit, pandas and scikit-learn, with Claude Code as a pair programmer. I set the questions, read and question every step, and check the results against the chemistry. The instructions I give the AI are in `CLAUDE.md`.

## Contact

Demmy Yu · [LinkedIn](https://www.linkedin.com/in/demmyyu)
