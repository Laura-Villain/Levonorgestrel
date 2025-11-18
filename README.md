# Levonorgestrel-Model
Whole-body PBPK model of Levonorgestrel as well as ethinyl estradiol 


This repository contains:


- a PK-Sim project (*.pksim5) file of the current PBPK model(s)
- static content (e.g. text blocks, *.md files) as inputs for an evaluation plan
- an evaluation plan (evaluation-plan.json) to create an evaluation report using the snapshot and static text blocks to display the performance of the model


This levonorgestrel model is intended to be used as a victim drug in CYP3A4-mediated drug-drug interactions (DDI) when orally administered either alone or in combination with ethinyl estradiol in healthy and obese women. 

The model incorporates dynamic changes in SHBG protein-binding, via an Emax model, observed during long-term use of levonorgestrel and ethinyl estradiol. 

The presented model represents an original model development project presented by Cicali *et al.* [[1]](https://ascpt.onlinelibrary.wiley.com/doi/full/10.1002/psp4.12572). 
A complete summary of model development and application can be found in this manuscript and the respective supplemental materials.

## Code of conduct
Everyone interacting in the Open Systems Pharmacology community (codebases, issue trackers, chat rooms, mailing lists, etc) is expected to follow the Open Systems Pharmacology [code of conduct](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CODE_OF_CONDUCT.md#contributor-covenant-code-of-conduct).

## Contribution
We encourage contribution to the Open Systems Pharmacology community. Before getting started please read the [contribution guidelines](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CONTRIBUTING.md#ways-to-contribute). If you are contributing code, please be familiar with the [coding standard](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CODING_STANDARDS.md#visual-studio-settings).

## License
The model code is distributed under the [GPLv2 License](https://github.com/Open-Systems-Pharmacology/Suite/blob/develop/LICENSE).

## References
[1] [Cicali B, Lingineni K, Cristofoletti R, Wendl T, Hoechel J, Wiesinger H, Chaturvedula A, Vozmediano V, Schmidt S. Quantitative Assessment of Levonorgestrel Binding Partner Interplay and Drug-Drug Interactions Using Physiologically Based Pharmacokinetic Modeling. CPT Pharmacometrics Syst Pharmacol. 2021 Jan;10(1):48-58. doi: 10.1002/psp4.12572. Epub 2020 Dec 13. PMID: 33217171; PMCID: PMC7825189](https://ascpt.onlinelibrary.wiley.com/doi/full/10.1002/psp4.12572).
