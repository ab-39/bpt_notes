# Gene Therapy
#bpt/genetics #bpt/racp_cls
- - -
### Overview
Gene therapies are new and varied - there is no single way to pin it down, but one definition is:
> The treatment of a genetic disease by permanent modifications to the patient’s DNA

This encompasses things like gene augmentation and editing, but excludes things like mRNA vaccinations or other nucleic acid therapeutics (that _do not_ permanently alter the patient’s DNA). 

One way to divide gene therapy is somatic vs. germline gene therapy:
- Somatic -> therapeutic modifications made to genes in somatic cells that are _not_ inherited by later generations
  - All current gene therapies fall into this category
- Germline -> therapeutic modifications made to germ cells that will be inherited by later generations

Another way to classify gene therapies is by route of administration:
- _In vivo_ -> therapeutic genes are delivered into the patient directly via a delivery vector 
- _Ex vivo_ -> therapeutic genes are delivered into the patient’s cells outside the body, and the modified cells are then administered to the patient 

In general, it is important to remember that gene therapies are most useful in less complex (e.g. monogenic) conditions, and under circumstances where the genetic variant hasn’t already led to some permanent structural abnormality.
- - -
### Techniques
#### CAS9-CRISPR
This relies on a guide RNA ‘taking’ the CAS9 nuclease to the target sequence of DNA, where it is able to create a double stranded break in a section of DNA. This can either then ‘inactivate’ a problematic gene (e.g. gain of function mutation) or allow for the therapeutic gene to be stitched into place. 

#### DNA-coated Colloidal Gold
Injecting DNA-coated gold into the nucleus of a cell.

#### Viral Vectors
Often retroviruses, herpesviruses, etc.
Benefits include:
- Able to cross blood brain barrier

Drawbacks include:
- May be pre-existing antibodies against the vector
- Limited capacity to carry genetic material 

#### Lipid particles
- - -
### Safety Considerations
#### Vector Considerations
Need to consider:
- How much genetic material the vector can carry
- If the target cell is mitotic or not
- Safety factors:
  - Host immune response 
  - Insertional mutagenesis
  - Insertional oncogenesis 
  - Off target effects
![](Gene%20Therapy/image.png)
- - -
### In Vivo Gene Therapies
#### _RPE65-related Retinal Dystrophies_ 
> Voretigene neparvovec 
Treats conditions such as retinitis pigmentosa, which are abnormalities of the photoreceptors of the retina that cause progressive vision loss. Often present in childhood, and can be quite aggressive (Lever’s amaurosis).

_RPE65_ is critical to the normal cycle through which light acts on 11-cis-retinal -> all-trans-retinal:
![](Gene%20Therapy/image%202.png)
Accumulation of toxic all-trans retinyl ester leads to retinal neuronal death. Voretigene is administered via an adeno-associated viral vector to provide a functioning copy of the _RPE65_ gene, but needs to be administered while there are still functional neurons left to save.

#### _SMN1_ / Spinal Muscular Atrophy
> Onasemnogene abeparvovec
- - -
### Ex Vivo Gene Therapies
These are most commonly haematopoietic stem cells that are used to treat immunodeficiencies, haemoglobinopathies, and other haematological conditions. Typically utilise a lentiviral vector.

#### [[Chimeric Antigen Receptor T-Cells]]
Gene augmentation to introduce an antigen receptor that recognises cancer antigens into a patient’s own T-cells. Risks of ICANS (neurotoxicity) and cytokine release syndrome. 
- - -
### Gene Editing
#### Sickle Cell Disease and Β-Thalassaemia
> Casgevy 
This is a CAS9-CRISPR mediated gene producted that inactivates the _BCL11A_ protein, allowing fetal haemoglobin (HbF) to be expressed. Note that this does not eliminate the defective Hbβ/HbS - so there will be some active disease/vasoocclusive crises.  
- - -
