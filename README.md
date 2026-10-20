# Bis(2-ethylhexyl) phthalate (DEHP) Model
This repository contains a whole-body physiologically based kinetic (PBK) model for di(2-ethylhexyl) phthalate (DEHP) and its primary toxic metabolite, mono(2-ethylhexyl) phthalate (MEHP), in adults. The model was built in PK-Sim® (Open Systems Pharmacology Suite) and was developed to reproduce aggregate exposure to DEHP from multiple routes over extended periods [1].

Model reliability was established by comparing model predictions with human plasma and urine data after single oral DEHP doses and after repeated exposure (see [1] for the data sources). The aggregate exposure scenario is based on literature-derived exposure estimates across routes. Predicted internal exposures were compared with human biomonitoring (HBM) urinary MEHP data from the Information Platform for Chemical Monitoring (IPCHEM).

The model comprises:
- **Compounds:** DEHP (parent) and MEHP (metabolite)
- **Individuals and population:** typical adult individuals and a European virtual population (n = 1000)
- **Simulations:** single oral DEHP administration, MEHP disposition, repeated/continuous DEHP exposure (Lorber scenarios), and aggregate DEHP exposure (individual and population)

## Repository files
| File | Description |
| ---- | ----------- |
| [Bis-2-ethylhexyl-phthalate-Model.json](Bis-2-ethylhexyl-phthalate-Model.json) | PK-Sim® project snapshot of the DEHP/MEHP model, including building blocks, simulations and observed data. Load it in PK-Sim® via *File → Load from Snapshot*. |
| [Evaluation/Input/evaluation_plan.json](Evaluation/Input/evaluation_plan.json) | Evaluation (qualification) plan used to generate the model evaluation report |
| [Evaluation/Input/Content](Evaluation/Input/Content) | Text sections of the evaluation report |
| [Evaluation/workflow.R](Evaluation/workflow.R) | R workflow to create the evaluation report with the OSP qualification framework |

## Code of conduct
Everyone interacting in the Open Systems Pharmacology community (codebases, issue trackers, chat rooms, mailing lists etc...) is expected to follow the Open Systems Pharmacology [code of conduct](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CODE_OF_CONDUCT.md#contributor-covenant-code-of-conduct).

## Contribution
We encourage contribution to the Open Systems Pharmacology community. Before getting started please read the [contribution guidelines](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CONTRIBUTING.md#ways-to-contribute). If you are contributing code, please be familiar with the [coding standard](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CODING_STANDARDS.md#visual-studio-settings).

## License
The model code is distributed under the [GPLv2 License](https://github.com/Open-Systems-Pharmacology/Suite/blob/develop/LICENSE).

## References
[1] Lamon L, Lesage R, Lautz L, Fragki S, Moreau M, Schaller S, Siccardi M, Zare-Jeddi M. Leveraging PBK Models and Human Biomonitoring Data in Aggregate Exposure: A Case Study of repeated DEHP Exposure. *In preparation.*
