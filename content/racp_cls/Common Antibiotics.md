# Common Antibiotics
#bpt/infection #bpt/pharmacology #bpt/racp_cls
- - -
### Overview
#### Basic Bacteriology
Broadly, bacteria can be divided into two classes on the basis of the Gram stain:
- Gram positive = two layers:
  - Thick peptidoglycan cell wall
    - Capable of retaining crystal violet stain hence appears blue
  - Cytoplasmic membrane
- Gram negative = three layers:
  - Outer membrane consisting of lipopolysaccharide and porins
  - Thin peptidoglycan cell wall
    - Cannot retain crystal violet _but_ can retain counterstain (e.g. safranin) hence appears pink
  - Cytoplasmic membrane 

#### TDM Terminology for Antibiotics 
![](Common%20Antibiotics/image.png)
- - -
## Β-Lactam Antibiotics

**Mechanism of Action:** 
Bind to _penicillin-binding protein_ (a type of transpeptidase) in the bacterial cell wall, preventing cross-linking of peptidoglycan and leading to impaired cell wall integrity with bactericidal effect.

**Measure of Efficacy:**
Free drug time above MIC (i.e. these are _time-dependent_ antibiotics). 

### Penicillins
**Spectrum:**
Generally quite narrow, mostly GPCs predominantly _Streptococcus_ spp. for early generation penicillins, which can be treated with low concentrations of pencillin. Also [[syphilis]]. Newer-generation penicillins can be quite broad. 

_E. faecium_ is frequently resistant to penicillins (and _E. faecalis_ less so). 

### Cephalosporins 
**Spectrum:**
Varies with generation - earlier generations tend to have narrow, more Gram-positive coverage, while higher generations have broader, Gram-positive and Gram-negative activity. The exception is ceftriaxone, which has broad Gram-negative coverage only (except for _Strep. pneumoniae_, which it does treat) and is able to penetrate the CNS. 
- The _Enterococcus_ species are inherently resistant to all cephalosporins. 
- Cefiderocol - the siderophore cephalosporin - binds to extracellular free iron to allow itself to be _actively_ taken up into the bacterial cell by iron transporters in a kind of Trojan horse ploy (hence its trade name **Fetroja**) -> active against NDM-producing _Enterobactereciae_, as well as resistant _Acinetobacter_ and _Stenotrophomonas_ infections.

**Mechanisms of Resistance**:
Cleavage of β-lactam ring by β-lactamase enzymes. Alteration of PBP binding site. Important bacterial genes implicated in cephalosporin resistance include _CTX-M_, the most common ESBL gene, and _ampC_ (which is _not_ an ESBL). 

#### Adverse Effects
All β-lactams (but particularly cephalosporins) can cause seizures at high concentrations.

### Mechanisms of Resistance:
1. Alter porins -> prevent entry of antibiotic into the cell
   - Particularly important in _P. aeruginosa_ developing resistance to carbapenems
2. Hydrolysis of β-lactam ring by β-lactamase enzymes:
   - Some semi-synthetic penicillins (e.g. methicillin, flucloxacillin) are more resistant to β-lactamases
   - Addition of a β-lactamase inhibitor (e.g. clavulanic acid, tazobactam) also enables antibiotics to act against resistant bacteria
   - Gram-negative organisms tend to be able to produce [[extended spectrum β-lactamase]] proteins or express the [[ampC]] gene that provide a broader resistance profile
   - An emerging threat in terms of antibiotic resistance is the emergence of carbapenemase-producing Enterobacteriaceae
     - There are five particularly worrisome enzymes:
       - _Klebsiella pneumoniae_ carbapenemase (KPC)
       - New Delhi metallo-β-lactamase proteinase (NDM)
       - Oxacillin-type β-lactamase-48 (OXA48)
       - Verona-integron-encoded metallo-β-lactamase (VIM)
       - Imipenem-hydrolysing metallo-β-lactamase (IMP)
     - Treatment depends on the particular enzyme:
       - NDMs -> ceftazidime-avibactam plus aztreonam
         - Then: cefiderocol, colistin-based combination therapy
       - KPCs -> ceftazidime-avibactam
         - Then: meropenem-vaborbactam, cefiderocol, colistin-based combination therapy
![](Common%20Antibiotics/image%202.png)
3. Alteration of PBP binding site:
   - This is the mechanism by which MRSA is able to resist newer, semi-synthetic antibiotics
   - _mecA_ gene (among others) encodes the PBP2a protein
     - Mutations to PBP2x can confer penicillin-resistance in some _Streptococcus pneumoniae_ strains, which can be overcome with _very_ high concentrations of antibiotic, particularly for respiratory tract infections, where the alveolar:serum concentration of penicillin is roughly 1:1
       - This does not hold for CNS infections, as the required doses of penicillins to achieve adequate CNS concentrations would result in unacceptable toxicity 
   - Confers resistance to most penicillins, cephalosporins (third-generation and below), and carbapenems
   - Not enzymatic -> cannot be overcome by β-lactamase inhibitors
4. Efflux pumps

**Alternative Choices of Antibiotics**:
- **Glycopeptides** - e.g. vancomycin, teicoplanin - mainstay of treatment of MRSA, but still have relatively high treatment failure rates (~25%)
  - New drugs emerging - e.g. dalbavancin, oritavancin
- **Linezolid** - bacteriostatic antibiotic with very broad Gram-positive cover and antitoxin effect. Caution: myelosuppressive, can cause irreversible neuropathy, and can contribute to [[serotonin syndrome]]
- **Daptomycin** - lipopeptide that depolarises the bacterial cell membrane. Itself inactivated by pulmonary surfactant (-> cannot use in pneumonia). Can cause myopathy, peripheral neuropathy, and eosinophilic pneumonia
- Ceftaroline - 5th generation cephalosporin targeting the PBP2a protein
- TMP-SMX
- Clindamycin
- Erythromycin
- Doxycycline
- Rifampicin and fusidic acid (neither can be used as monotherapy)
- Gentamicin
- Moxifloxacin (limited data)

> [!IMPORTANT] Multi-Resistant MRSA
> In addition to the definition of MRSA above, clones of MRSA that are either:
> - Resistant to two or more non-β-lactam antibiotics, or
> - Resistant to ciprofloxacin (EMRSA-15 clone)
> Are deemed _multi-resistant_ MRSA, or mMRSA. 

#### Β-Lactamase Inhibitors
These can be added to β-lactams to enable activity against (some) β-lactamases. They work by acting as a false substrate for the bacterial enzyme with high avidity, thus sparing the actual antibiotic.
> _Avibactam_ is the exception, which binds reversibly binds and inactivates the β-lactamase enzyme, after which it is can detach and inactivate other enzymes! It has activity against class A (e.g. ESBL, KPC), class C (ampC), and class D (OXA48) enzymes, but not the metallo-β-lactamases. 
- - -
### Aminoglycosides 
**Mechanism of Action:** 
Bind to the 30S ribosomal subunit to interfere with bacterial protein synthesis, leading to eventual cell death. Can be combined synergistically with β-lactam antibiotics, as their destructive effect on the cell wall facilitates penetration of the cytoplasm by aminoglycosides. 

**Measure of Efficacy:**
Peak-to-MIC ratio (i.e. these are _concentration-dependent_ antibiotics). 
> Note that toxicity, on the other hand, tends to be time-dependent

**Spectrum:**
Tend to offer superior coverage of Gram-negative organisms. 

**Mechanisms of Resistance**:
Efflux pumps. 
- - -
### Fluoroquinolones
#### Measure of Efficacy:
AUC-to-MIC ratio

#### Spectrum:
Varies:
- Ciprofloxacin -> excellent Gram-negative coverage, the only oral antipseudomonal ([watch this space…](https://pubmed.ncbi.nlm.nih.gov/30014729/)) **but**… terrible Gram-positive coverage
- Moxifloxacin -> great Gram-positive coverage
- - -
### Glycopeptides
#### Mechanism of Action
Bind to the subterminal d-Ala residue of the pentapeptide side chain in bacterial cell walls -> inhibition of peptidoglycan cell wall synthesis with _bactericidal_ effect. _Cannot_ penetrate the outer lipid membrane of Gram-negative bacteria. 

**Spectrum**:
Gram-positive (including _C.difficile_, except there the effect is bacteriostatic).

#### Measure of Efficacy:
24h AUC-to-MIC ratio

**Adverse Effects**:
Vancomycin: Red Man Syndrome - infusion related reaction (secondary to histamine release), nephrotoxic 
Teicoplanin: nephrotoxicity, ototoxicity

**Mechanisms of Resistance**:
The _Enterococci_ - _faecium_ (bad!) and _faecalis_ (less bad) - are able to develop high-level resistance to vancomycin through genes that alter the terminal residues of the pentapeptide change from d-Ala-d-Ala -> d-Ala-d-Lac, which disables the binding and crosslinking of vancomycin. This is encoded through three genetic clusters:
- _vanA_ - high level resistance to vancomycin _and_ teicoplanin. Genes can be located on a plasmid or transposon and thus are transferable.
  - Note that transfer can occur to _non_-_Enterococcus_ spp. as well via the process of conjugation (direct plasmid exchange as opposed to transduction, which is via a viral vector)
- _vanB_ - mid-level resistance to vancomycin **but** remains susceptible to teicoplanin. Genes located on a transposon and are thus transferable.
- _vanC_ - low level resistance to vancomycin **but** remains susceptible to teicoplanin. Different alteration to cell wall (d-Lac -> d-Ser). Occurs on the chromosome of less common _Enterococcus_ spp. Not transferable. 

**Alternative Choices of Antibiotics**:
- Penicillins - if isolated vancomycin resistance (most commonly _E. faecalis_) 
- Teicoplanin - if _vanB/C_
- Linezolid
- Daptomycin +/- β-lactam
- Tigecycline
- Ceftaroline (for _E. faecalis_)
- For UTIs: nitrofurantoin, fosfomycin
  - Note nitrofurantoin contraindicated if CrCl <60mL/min
- - -
### Macrolides
**Mechanism of Action**
Insert into the 23s subunit of the 50s ribosome, blocking protein assembly of the transpeptidase enzyme.

#### Measure of Efficacy
24h AUC-to-MIC ratio

**Mechanisms of Resistance**
- _mefA_ gene -> efflux pump = low-level resistance
- _ermB_ gene -> alteration of binding site = high-level resistance 
- - -
