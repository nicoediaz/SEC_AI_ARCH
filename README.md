# Replication Package

This repository contains the replication package for the paper:

**A Practitioners' Characterization of Security Guidelines for AI-Augmented Software Architectures**

The study was conducted in two stages: a pre-study with security experts and a main study with software practitioners. The repository contains the survey instruments, raw data, and analysis results for both stages.

## Repository Structure

### `PRESTUDY/`

Contains the material related to the expert pre-study.

#### `SURVEY/`
- `EXPERT_SURVEY.pdf`  
  Survey instrument used to assess and prioritize the security guidelines considered in the study.

#### `RESULTS/`
- `PRESTUDY_RESULTS.xlsx`  
  Responses and results obtained from the expert pre-study.

---

### `MAIN STUDY/`

Contains the material related to the practitioner study.

#### `SURVEY/`
- `INFORMED_CONSENT.pdf`  
  Informed-consent document presented to participants.

- `SCREENING_SURVEY.pdf`  
  Technical screening questionnaire used to assess participants' basic knowledge of program comprehension, software security, and AI.

- `MAIN_SURVEY.pdf`  
  Main survey instrument used to assess guideline application frequency, conformance-checking strategies and sources, perceived AI-debt mitigation, architectural relevance, and complementary open-ended responses.

#### `RESULTS/`
- `ALL_DATA.xlsx`  
  Raw data collected during the main study.

- `MAIN_RESULTS.xlsx`  
  Results of the quantitative analyses reported in the paper, including descriptive statistics and statistical tests.

## Study Overview

The pre-study was used to prioritize a set of security guidelines for AI-augmented software architectures. The five highest-ranked guidelines were subsequently evaluated in the main practitioner study.

The main study investigated:
- reported guideline application frequency;
- conformance-checking strategies and information sources;
- perceived effectiveness for mitigating AI technical debt;
- perceived relevance across architectural modules; and
- complementary insights collected through open-ended questions.

## Reproducibility

The files contained in the `RESULTS` folders provide the data and analysis outputs used to derive the findings reported in the paper. The survey instruments included in the `SURVEY` folders document the questions and response options presented to participants.
