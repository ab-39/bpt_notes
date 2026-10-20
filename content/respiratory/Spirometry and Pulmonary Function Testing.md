# Spirometry and Pulmonary Function Testing
 #bpt/respiratory  #bpt/racp_cls
- - -
### What is spirometry?
Spirometry is a simple test that looks at the movement in and out of the lungs during a forced manoeuvre. 

The key stages of spirometry are:
1. Inhalation to full capacity
2. Forced expiration until lungs are empty
3. Inhalation back to full capacity

![](Spirometry%20and%20Pulmonary%20Function%20Testing/image.png)

This gives us several key measurements:
- FEV1 - the forced expiratory volume in one second (should be >70% of FVC)
- FVC 
- Peak flow
- FEV1/FVC ratio

Additionally, we may see the strength of the diaphragm (and other inspiratory muscles = MIPS) or the strength of the abdominal muscles (and other expiratory muscles = MEPS). Any reduction here is generally suggestive of a neuromucsular disorder. 
- - -
### The role of carbon monoxide
The presence of a diffusion limitation for carbon monoxide (DLCO) sheds some further light on the diagnosis after routine spirometry. A low DLCO implies some destruction of the lung parenchyma, and is seen in conditions such as emphysema (obstructive) and IPF (restrictive).
- High DLCO -> asthma, diffuse alveolar haemorrhage
  - High DLCO that drops -> alveolar haemorrhage
- Low DLCO -> emphysema, ILD, heart failure, PAH

This is calculated using [[Physics for Medicine#Fick’s Law of Diffusion|Fick’s law of diffusion]], which states that the diffusing capacity of a given gas will be proportional to the volume of gas diffused, and inversely proportional to the pressure gradient across the barrier, i.e.:
> $D_{L_x} = V_x / (P_1 - P_2)$ 

In the case of carbon monoxide, its affinity for haemoglobin is so high that its free concentration is negligible, and it does not exert a partial pressure, i.e.:
> $D_{L_{CO}} = V_{CO} / P_{A_{CO}}$ 

This is measured by getting the patient to take a single breath of gas with ~0.3% CO, hold their breath for ten seconds, and then breath it out. The change in concentration of CO enables the DLCO to be calculated. 

Dividing the DLCO by the alveolar volume gives the KCO - the rate of alveolar capillary blood uptake, i.e.:
> $K_{CO} = D_{L_{CO}} / V_A$ 

- High KCO -> pneumonectomy, incomplete lung expansion (e.g. neuromuscular disorders, obesity)
- Low KCO -> pulmonary vascular disorders, alveolar haemorrhage

#### Prognostic Value
- DLCO <40% -> significant risk of postoperative complications
- DLCO >60% -> low incidence of postoperative complications
- - -
### The role of nitric oxide
The fraction of excreted nitric oxide correlates with TH2 mediated inflammation and sputum eosinophilia:
- ≥50ppb -> presence of inflammation responsive to steroid
- <25ppb -> absencec of inflammation responsive to steroid
- - -
### Preparing the patient
Traditionally, caffeine (a methylxanthine, like theophylline) is avoided before PFTs as it acts as a bronchodilator. There is meta-analytic level evidence to support this.
- - -
### Interpreting the Test
Most lung function values will be reported using standard deviations:
| Z-Score       | Interpretation |
|---------------|----------------|
| > —1.65       | Normal         |
| —1.65 -> —2.5 | Mild           |
| —2.51 -> —4   | Moderate       |
| <—4.1         | Severe         |

As a rule of thumb, interpretation starts with the FEV1/FVC ratio:
- FEV1/FVC <0.7 -> [[Obstructive Lung Disease|obstructive pathology]]
- FEV1/FVC ≥0.7 -> [[Restrictive Lung Disease|restrictive pathology]] 

> [!NOTE] Lying-Standing Spirometry
> In normal cases, lying flat will cause the FVC to decrease by ~10%. Drops in FVC larger than this (in the order of 30-50%) are suggestive of a **_diaphragmatic palsy_**. 

- - -
### References
A great AAFP primer on PFTs - [p359](https://www.aafp.org/pubs/afp/issues/2014/0301/p359.pdf)
Cochrane review on caffeine - [The effect of caffeine in people with asthma](https://www.cochrane.org/CD001112/AIRWAYS_the-effect-of-caffeine-in-people-with-asthma)
Overview article - [Pulmonary Function Tests: Easy Interpretation in Three Steps](https://pmc.ncbi.nlm.nih.gov/articles/PMC11242573/)
- - -
