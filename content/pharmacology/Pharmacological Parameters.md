# Pharmacological Parameters
#bpt/pharmacology
***
### Volume of Distribution
This is a conceptual measurement of the distribution of the drug. It is the volume of fluid that would be required to contain all of the drug in the body at the concentration at which the drug exists in the plasma. 
> $V_d = Dose / C_0$

Low Vd (<1L/kg) -> polar drug, protein bound, in the plasma
High Vd -> lipophilic 

Utility exists in calculating a loading dose:
> $Dose_{load} = V_d * C_{target}$ 
- - -
### Absorption Rate Constant
The absorption rate constant, $K_a$, refers to the rate at which a drug enters the system.
- - -- - -
### Clearance
Clearance is the rate of elimination of a substance relative to its concentration in a bodily fluid:
> $Cl = Rate_{elimination}/C$ 
Clearance is expressed as a rate: volume per unit time.

Clearance is expressed relative to concentration to allow for the fact that the rate of elimination can change in drugs that follow first-order kinetics. As such, in drugs that follow first-order kinetics, _clearance is a constant_. In drugs that follow zero-order or Michaelis-Menten (i.e. saturable) kinetics, however, this does not hold. For zero-order kinetics, elimination occurs as a constant amount of drug per unit time, which yields a variable rate as the process is not proportional to concentration. For Michaelis-Menten kinetics:
> $Cl = V_m / (K_m + C_p)$ 
Where:
- $V_m$ = maximum rate of elimination
- $K_m$ = the plasma concentration at which half of the maximum rate of elimination occurs
- $C_p$ = the concentration of the substance in the plasma 
Note that this is equivalent to the expression $Rate/C$, as $V_m * C_p / (K_m + C_p)$ gives the rate of enzymatic clearance of a saturable drug. 

Clearance is additive, i.e.:
> $Cl_{systemic} = Cl_{hepatic} + Cl_{renal} + Cl_{other}$
Where other can be sweat (e.g. lithium), breath (e.g. alcohol), etc. 
- - -
### Protein Binding
Drug-protein binding is a reversible, saturable process that usually involves only a handful of key plasma proteins:
- Albumin:
  - High affinity for acidic drugs - e.g. aspirin, warfarin, penicillins, etc.
  - Low affinity for basic drugs - e.g. propranolol, etc.
  - Low affinity for neutral drugs - e.g. digoxin, etc. 
- ⍺1-acid glycoprotein:
  - High affinity for basic drugs - e.g. quinidine, propranolol, lignocaine, etc.
- Other glycoproteins - e.g. β-glycoprotein, lipoproteins, etc. 
![](Pharmacological%20Parameters/image.png)
The _unbound_ fraction of the drug ($f_u$) is ‘relevant’, in that it is the fraction of the drug that is available for physiological and pharmacological processes, i.e.:
- Interaction with receptors - this is relevant as the a drug can be within the _free_ therapeutic range even if it is not within the _total_ therapeutic range 
- Metabolism 
- Renal excretion
- Dialysis
- - -
### Renal Clearance and Dose Adjustment
Protein binding affects renal clearance:
> $Cl_{renal} = Cl_s + Cl_f = Cl_s + f_u * GFR$
Where $Cl_f$ is renal clearance due to filtration and $Cl_s$ reflects the clearance due to renal secretion. 

For drugs excreted by the kidneys completely unchanged, the dose adjustment is simple:
> $Dose_{patient} / Dose_{normal} = CrCl_{patient}/CrCl_{normal}$

For drugs excreted between 50-99% unchanged by the kidneys, we only need to adjust for the fraction excreted unchanged by the kidney, i.e.:
> $Dose_{patient} / Dose_{normal} = (1-f_u) + f_u * CrCl_{patient}/CrCl_{normal}$

As a rule of thumb, drugs that are excreted <50% unchanged by the kidneys do not need to be adjusted in renal failure. All of these calculations need to take in to account what fraction of the total excretion occurs in the kidneys. 
- - -
### Half Life
The half life is the time taken for the plasma concentration of a drug to decrease by fifty percent:
> $t_{1/2} = ln(2)* V_d/Cl \approx 0.7 * V_d/Cl$ 

For drugs following first order kinetics, this is a constant (deriving from the equation: $C = C_0*e^{-kt}$):
> $t_{1/2} = ln(2)/k \approx 0.7/k$ 

The concept of half life does not _really_ apply to drugs following zero-order or Michaelis-Menten kinetics, as these are non-linear and tend to demonstrate a constant amount of drug being cleared per unit time. 
***
### Hepatic Extraction Ratio
Clearance is dependent on liver blood flow 
> $E = Cl_{hepatic} / Hepatic Blood Flow$ 
***
### Steady State Concentration
Steady state concentration is achieved when the rate of drug input is equal to the rate of elimination. In general, steady state is achieved after 4-6 half lives have elapsed, irrespective of the starting concentration. 
> IV: $C_{ss} = (Dose/t)/Cl = rate/Cl$ 
> PO: $C_{ss} = (Dose * F) / (Cl * τ)$
Where τ is the dosing interval. If the clearance is not known, this can be calculated using the elimination rate constant:
> $C_{{ss}_{max}} = C_{0_{max}} / 1 - e^{-kτ}$
For a drug given intravenously, this will simplify to:
> $C_{{ss}_{max}}$
> $= Dose / 1 - e^{-ln(2)τ/t_{1/2}}$
> $= Dose/1-(1/2)^{τ/t_{1/2}}$

> [!NOTE] Worked Example
> Suppose a drug has a target concentration of 300mg/L, a half life of 8h, and is administered at 8hrly intervals. What is the optimal dose?
> 
> Here, the dose is equal to $C_{ss} * (1 - (1/2)^{τ/t_{1/2}})$ 
> In other words: 300 * (1 - 1/2) = 150mg

The corollary of this is that the dose rate once steady state is achieved is simply the product of the clearance and the steady state concentration.

Loading doses allow for the initial concentration to be closer to the steady state concentration, but it will _still take_ 4-6 half lives to achieve the $C_{ss}$.  If loading:
> $C_{initial} = load / V_d$
***
### Bioavailability 
Bioavailability is denoted $F$.  Fundamentally, it is given by the ratio of the oral AUC (which itself is the integral of concentration with respect to time) to the IV AUC, i.e.:
> $F = AUC_{oral}/AUC_{IV}$
However, if the doses given via the two routes are different, this needs to be corrected for (assuming dose proportionality/linear kinetics):
> $F = (AUC_{oral} / Dose_{oral}) / (AUC_{IV} / Dose_{IV})= (AUC_{oral} * Dose_{IV}) / (AUC_{IV} * Dose_{Oral})$

PO bioavailability is affected by:
- FPHM
- Drug formulation and physicochemical properties 
- Route of administration 
- Physiologic factors 
- Hepatic extraction ratio ($E$):
  - $F_{max} = 1 - E$

#### Relative Bioavailability
This compares the oral bioavailability, typically of a new generic drug, with the reference standard on the market, and is a method by which drug companies can demonstrate bioequivalence and bypass stage III studies:
> $F = AUC_{new} / AUC_{reference}$
Note that unlike oral bioavailability, which is always (by definition) ≤1, relative bioavailability of a drug can be greater than 1.
***
### Charge
Ionisation makes substances _less_ lipid soluble, decreasing its ability to cross biological membranes. This is described for weak acids or bases by the _Henderson-Hasselbalch equation_:
> $pH = pK_a + log_{10}([Base]/[Acid])$ 
Where $K_a$ is the acid dissociation constant - a quantitative measurement of the strength of an acid in solution ([read more](https://derangedphysiology.com/main/cicm-primary-exam/acid-base-physiology/Chapter-412/traditional-and-physico-chemical-approaches-acid-base)). 

One (of many) key clinical applications of this fact is that changing the pH of the urine leads to differential secretion of acidic drugs, i.e.:
- Urinary alkalisation -> increased excretion of acidic drugs (e.g. aspirin, barbiturates)
- Urinary acidification -> decreased excretion of acidic drugs  
- - -
### Compartments
In general, we think of drugs as existing in two compartments:
- Central = plasma
- Peripheral = tissues
In addition to this, the input (oral dose) and output (urine) compartments have also been described.
![](Pharmacological%20Parameters/image%202.png)
- - -
### Pharmacodynamics 
Drugs exert their effect at receptors, and this effect can be quantified in two ways:
- $E_{max}$ = the maximal effect exerted by a drug (i.e. a _phenomenon_)
- $EC_{50}$ = the concentration required to achieve 50% of the maximal effect (i.e. a concentration)

This can be neatly summarised in the Hill equation for the sigmoid E(max) model:
> $E = E_{max} * C^σ / (EC_{50} + C^σ)$ 
Where:
- $E$ = effect
- $C$ = plasma concentration
- $σ$ = sigmoidicity
- - -
### Therapeutic Index
The therapeutic index, the ‘room to move’ between benefit and toxicity, is given by the ratio of the EC(50) for adverse ‘toxic’ effects ($TD_{50}$) and therapeutic ‘effective’ effects ($ED_{50}$), i.e.:
> $TI = TD_{50} / ED_{50}$
- - -
### Potency
A measure of the dose required to produce a response. Measured with the $ED_{50}$ - the dose required to produce a response in half the population. Note that a **low** $ED_{50}$ equates to a highly potent drug. The $ED_{50}$ does **not** depend on the maximal effect.
- - -
