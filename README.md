\# Anne E. Sartori



\*\*Offspring of Centenarians and the Growth of TICS\*\*



This repository contains work for my final project for Bayesian Modeling for Biomedical Research and Public Health, BS 849 (BU School of Public Health), Spring, 2025.

This was a joint project with Thanwi Lalu, Joshua Mann, Ailis Muldoon, and Havelah Queen.

Our report aims to understand the association between having a centenarian parent and the growth of TICS (cognitive scores). My contribution to the report studies the association between having a centenarian parent and the growth of TICS using Bayesian hierarchical modeling.



Click here for \[Report](https://github.com/annesartori1/Centenarian-parent-growth-of-TICS/blob/main/report/Centenarian_parent_growth_TICS.pdf).  



Click here for \[Script](https://github.com/annesartori1/ICV-and-complications-of-surgery/blob/main/script/Centenarian_parent_TICS). 



\*\*Skills:\*\* Bayesian hierarchical modeling, RJAGS



---



\*\*Description of (private) Data:\*\*  

## TICS Dataset

The file `tics.data.2021.csv` contains up to 5 longitudinally collected measures of the **Telephone Interview for Cognitive Status (TICS)** in offspring of centenarians and controls enrolled in two studies of longevity and healthy aging conducted at Boston University.  

TICS is a test administered over the phone to assess cognitive function.  

### Variables

| Variable                  | Description                                                                 |
|----------------------------|-----------------------------------------------------------------------------|
| ID                         | Patient ID                                                                  |
| Fam.num                    | Family ID                                                                   |
| Sex                        | 0 = Female, 1 = Male                                                        |
| Ptype                      | 0 = Controls, 2 = Centenarian offspring                                     |
| Age.at.Enrollment          | Age when subjects enrolled in the study                                     |
| Age.Last.Contact           | Age when last seen, or age at death for deceased subjects                   |
| Deceased                   | Yes if participant has died (do not use as a baseline characteristic)       |
| BMI                        | Body Mass Index                                                             |
| SH.Ever.Smoked.            | Yes for current or past smokers at enrollment                               |
| MC.Aspirin                 | Yes for regular aspirin use at enrollment                                   |
| MC.Stroke                  | Yes for history of stroke at enrollment                                     |
| MC.Diabetes.Mellitus       | Yes for history of diabetes at enrollment                                   |
| MC.HTN                     | Yes for history of hypertension at enrollment                               |
| MC.Coronary.Artery.Disease | Yes for history of coronary artery disease at enrollment                     |
| MC.Cancer                  | Yes for history of cancer (excluding skin cancer) at enrollment             |
| MC.Heart.Attack            | Yes for history of heart attack                                             |
| Years.of.Education         | Years of education at enrollment                                            |
| TICS01—TICS05              | TICS scores in 5 longitudinal follow-ups (TICS01 = baseline)               |
| Age01—Age05                | Age at the corresponding TICS test                                          |


