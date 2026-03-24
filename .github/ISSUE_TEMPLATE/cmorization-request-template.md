---
name: CMORization request full text
about: Full text template for a CMORization request (CMIP6 like)
title: "[CMORization request]"
labels: CMORization request
assignees: ''

---

## Mandatory information:

#### Full path to the case(s) of the experiment on NIRD 
(e.g. /projects/NS2345K/oyvinds/cases)

#### experiment_id 
(e.g. LRTAP-low)

#### model_id 
(e.g. NorESM2-LM)

#### CASENAME(s) and years to be CMORized 
(e.g. NSSP245_LRTAP-lowdiet_f19_tn14_Forces_20231031, 2015-2050)

### Optional information

#### (additional information, if the experiment is branched/hybrid restart from previous parent experiment; you may find more information relevant to the experiment_id here: https://github.com/NorESMhub/noresm2cmor/blob/master/tables/CMIP6_CV.json)

#### parent_experiment_id 
(e.g. LRTAP-base)

#### parent_experiment_rip 
(e.g. r1i1p4f5)

#### branch_method
(e.g. 'Branch-restart from year 2015-01-01 of LRTAP-base',)

### other information

#### experiment_rip
(e.g. r1i1p4f5)

#### parent case path
(e.g. /projects/NS2345K/oyvinds/cases)

#### case
(e.g. NHIST_f19_tn14_Forces_base_20231006)

#### Physics information:

#### Alternative / updated model version based on CMIP6 but updated with parameterisations from projects NFR-KeyClim and H2020-Forces

#### Information on aerosol emissions and GHG concentrations, should be added to metdata

## Progress
(each can be made a sub-issue by clicking the right hand side dots after creation of the main issue)

- [ ] CMORization of atmosphere / land done
- [ ] CMORization of ocean / ice done
- [ ] published to ESGF
