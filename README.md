# career-development-comb-survey
R code for a mixed-methods study applying behavioural science (COM-B, TDF, Behaviour Change Wheel) to the career development of UCL research professional services staff. Produces the survey descriptive tables and figures, overall and by cohort.

# Career development of research professional services staff: survey analysis

R code accompanying: Barriers and enablers to career development for research professional services staff: a behavioural science approach to intervention development - to add DOI when published.

## What the script does
career_dev_analysis.Rmd analyses the anonymised survey data (N = 64; CTO, DTE and Impact cohorts) and produces:
- Table 1: sociodemographic and career-related characteristics
- Table 3 and Supplementary Table S3: career development activities (overall and by cohort)
- Supplementary Table S2: perceived helpfulness of intervention suggestions (% helpful, M (SD))
- Figures 4–6 and Supplementary Figures S1–S9: responses to COM-B/TDF statements
- Figure 7 and Supplementary Figures S10–S12: helpfulness ratings of intervention suggestions

## Requirements
R (v4.2.0 or later) with readxl, dplyr, tidyr, forcats, stringr and ggplot2.

## Data
Before running: replace enter_pwd_here in the read_excel() line with the path to the data file on your computer, and in the out_dir line with the folder where you want the figures saved. The survey data are not included in this repository to protect participant anonymity.

## Citation
To add citation when published.
