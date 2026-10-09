# Theory Stress-Tests: An Interactive Threshold Model of Firms' Data Portfolios

An interactive, five-prong stress-test of a threshold model of firms' data portfolios (working paper under review; author and title withheld for blind review). The model extends Gimeno, Folta, Cooper, and Woo (1997) from entrepreneurs' human capital to firms' data.

## What this is

Theory papers usually state only the direction of each effect. Many of their predictions, though, depend on how large those effects are. This tool makes those conditions visible. It has five prongs:

1. **Model variables.** The theory's variables and identities, declared in one specification file.
2. **Sign restrictions.** A checker that rejects any version of the model that breaks the theory's assumptions.
3. **Propositions.** Each proposition tested on one chosen version and across many randomly drawn admissible versions.
4. **Boundary conditions.** Charts and maps showing where each prediction holds, weakens, or reverses.
5. **Practitioner view.** Plain-language questions that let a manager see what the theory predicts for a firm like theirs.

## Files

- `index.html` – the complete interactive tool. It runs in any browser with no installation.
- `spec/data-threshold-model.json` – the machine-readable specification: variables, sign restrictions, propositions, functional forms, defaults, and sampling choices.
- `LICENSE` – terms for reusing the code.

## Reproducibility

Robustness results draw 1,500 parameter sets uniformly from the ranges listed in the specification file, using a fixed random seed (2026). Anyone opening the page sees the same results for the same settings.

The functional forms and sampling ranges are modeling choices, not estimates. Changing them is the point: the tool shows which conclusions survive.

## Run it locally

Download `index.html` and open it in a browser.
