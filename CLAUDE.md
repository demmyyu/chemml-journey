# CLAUDE.md

## About me

I'm a synthetic organic chemist (PhD, total synthesis) learning Python and machine learning. I know synthetic chemistry deeply. I programmed in R and MATLAB years ago, so I know variables, loops, functions and vectors, but I'm new to Python and ML.

## How to teach me

- **Explain Python in plain technical terms, with no analogies.**
- **Mostly skip comparisons to R or MATLAB.** My R and MATLAB experience is many years old, so explain Python on its own terms.
  - **Exception: plotting.** I used MATLAB for plotting more recently, so comparisons between matplotlib and MATLAB plotting are welcome.
- **Keep explanations concise:** what each line does and why. Skip programming basics I already know.
- **Prefer teaching over just doing.** Explain code before or after writing it, and avoid dropping large blocks of unexplained code.
- **Give me small exercises regularly**, and do **not** solve them. Let me attempt them first; only give hints if I ask, and review my solution when I share it.
- **Show, don't just tell.** I'm a synthetic chemist and understand structures and pictures much faster than paragraphs of text. For every new concept:
  - **Draw the molecules involved** with RDKit, and **highlight the relevant atoms or bonds** (substructure matches, atom environments, fingerprint bits, what a model looks at).
  - **When a cell outputs numbers, arrays or bit vectors, also show a picture** of what they mean (e.g. draw the fragment behind a fingerprint bit with `Draw.DrawMorganBit`, colour atoms by a value, plot a distribution) and say in one sentence what I should look at in the output.
  - **Use small, simple example molecules first** (e.g. ethanol, butanol, acetic acid, benzoic acid) before applying a concept to a whole dataset.
  - **Keep text cells short:** 2–4 sentences, then a picture or a code cell. Prefer a figure or a small table over a long explanation.

## Time budget

- I work on this project **5–8 hours per week**.
- **Each notebook should take about 2–3 hours, including exercises.** Use one exercise per topic unless I ask for more.
- If a topic needs more time, **split it into several notebooks and tell me the plan before creating them.**

## Environment

- Use the conda environment **`chemml`** for all Python work (e.g., `conda activate chemml`, or `conda run -n chemml python ...`).
- When installing packages, install them into `chemml` and explain what each package is for.

## Confidentiality

- **Never include unpublished structures from my PhD project** in code, examples, datasets, comments, or files. Use public molecules (e.g., from published papers, PubChem, ChEMBL, or textbook examples) instead.

## Language

- Write all code, comments, and files in **English**.
