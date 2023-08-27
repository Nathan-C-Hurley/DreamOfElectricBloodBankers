# Would doctors dream of electric blood bankers? Large language model-based artificial intelligence performs well in many aspects of transfusion medicine.

## Abstract

**Background:** Large language models (LLMs) excel at answering knowledge-based questions. Many aspects of blood banking and transfusion medicine involve no direct patient care and require only knowledge and judgement. We hypothesized that public LLMs could perform such tasks with accuracy and precision.

**Study Design and Methods:** We presented three sets of tasks to three publicly-available LLMs (Bard, GPT-3.5, and GPT-4). The first was to review short case presentations and then decide if a red blood cell transfusion was indicated. The second task was to answer a set of consultation questions common in clinical transfusion practice. The third task was to take a multiple-choice test experimentally validated to assess internal medicine postgraduate knowledge of transfusion practice (the BEST-TEST).

**Results:** In the first task, the area under the receiver operating characteristic curve for correct transfusion decisions was 0.65, 0.90, and 0.92, respectively for Bard, GPT-3.5 and GPT-4. All three models had a modest rate of acceptable responses to the consultation questions. Average scores on the BEST-TEST were 55%, 40%, and 87%, respectively.

**Conclusion:** When presented with transfusion medicine tasks in natural language, publicly available LLMs demonstrated a range of ability, but GPT-4 consistently scored very well in all tasks. Research is needed to assess the utility of LLMs in transfusion medicine practice. Transfusion Medicine physicians should consider their role alongside such technologies, and how they might be used for the benefit and safety of patients.

## Authors

- Nathan C. Hurley, MD, PhD†
- Kristopher M. Schroeder, MD†
- Aaron S. Hess, MD, PhD†,§

**Affiliations:**
- † Department of Anesthesiology, University of Wisconsin, Madison, WI
- § Department of Pathology and Laboratory Medicine, University of Wisconsin, Madison, WI

## Files in the Repository

- `LICENSE` -- GNU GPLv3 License
- `README.md`
- `patient_stems.txt` -- Raw list of patient stems, required by Task 1
- `Task 1 - Patient Scenarios.ipynb` -- Code for running Task 1
- `Task 3 - BEST TEST.ipynb` -- Code for running Task 3. Note that the BEST TEST is not included, and must be requested directly from its owners.
- `results/key.csv` -- Key of Gold Standard answers for Task 1
- `figures/flow_diagram.png` -- Figure

## Figure Description

![Flow diagrams of experimental procedures](figures/flow_diagram.png)

**Figure:** Flow diagrams of experimental procedures for Task 1 (A) and Task 3 (B). In Task 1, 44 different combinations were assembled from 11 case stems and 4 hemoglobin values, and presented to each large language model along with a short, introductory preamble to the model. Each combination was re-presented to each model a minimum of 10 times, resetting the model between every trial. In Task 3, the 20-question BEST-TEST was presented to each large language model. In order to investigate for batching effects, the test was presented to the large language model in each of three different ways: as a complete test of 20 questions, as 4 batches of 5 questions each, or as 20 batches of 1 question each. Each batch (25 total) was presented to each model a minimum of 10 times, re-setting the model between each trial.  

## License

This project is licensed under the terms of the GNU GPLv3 License. See [LICENSE](LICENSE) for more details.

## Contact

**Corresponding Author:**  
Aaron S Hess  
Email: Ahess5@wisc.edu  
Telephone: (608) 263-8100  
Fax: (608) 263-0575
