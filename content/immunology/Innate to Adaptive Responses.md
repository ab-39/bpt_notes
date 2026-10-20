# Innate to Adaptive Responses
#bpt/immunology #bpt/racp_cls
- - -
### Overview
Although the innate immune system and complement are typically sufficient to clear ~90% of infections, the remainder will trigger a response by the adaptive immune system, which relies on antigen presenting cells. 
![](Innate%20to%20Adaptive%20Responses/image%202.png)
After the [[initiation of the immune response]], type II interferon, IL-17, TNFβ, IL-2, IL-12, and IL-23 are responsible for the infection of the adaptive response, which is primarily effected by TH1 and TH17 cells:
| Cytokine        | Source                       | Major Target                                | Function                                                     |
|-----------------|------------------------------|---------------------------------------------|--------------------------------------------------------------|
| IFNγ            | TH1 (CD4+) cells, NK cells   | Macrophages, dendritic cells, T and B cells | Activate macrophages, promote Ig class switching, promote TH1 and inhibit TH2 cells |
| IL-17           | TH17 (CD4+) cells            | Epithelium, endothelium, PMNs, fibroblasts  | Recruit neutrophils, promote inflammation                    |
| TNFβ            | TH1 (CD4+) cells             | PMNs, tumour cells                          | Kill tumour cells, activate PMNs, activate endothelium to allow trafficking  |
| IL-2            | TH1 and TH0 (CD4+) cells     | Lymphocytes                                 | Lymphocyte proliferation                                     |
| IL-12 and IL-23 | Dendritic cells, macrophages | NK cells, TH1 and TH17 (CD4+) cells         | Activate T-cell production of IFNγ and IL-17                 |

Once activated, T-cells kill target cells via three main mechanisms:
- Perforin - a protein complex similar to the MAC
- Granzymes - potent activators of apoptosis that are ‘injected’ into the target cell via perforin
- CD95L-CD95 interactions - induce apoptosis in virally infected cells
- - -
### Dendritic Cells
Dendritic cells can be thought of as a more sophisticated macrophage, and their main purpose is _antigen presentation_. They are resident in the tissues, and constantly sample the environment through phagocytosis, pinocytosis, and receptor-mediated endocytosis. 

> [!NOTE] Definitions
> - Antigen = a substance that binds to an antibody **and** triggers an immune response - generally high-molecular weight proteins (although there are some carbohydrate antigens)
> - Hapten = a substance that binds an antibody or T-cell receptor but _cannot_ trigger an immune response without being bound to a carrier (e.g. DNP)
> - Epitope = the part of the antigen that is recognised by the paratope (i.e. antigen combining site) of an antibody or TCR - usually 6-21aa depending on the conformation of the protein

Once a potential antigen has been taken up into the dendritic cell, families of receptors - most importantly the **_Toll-like receptors_** - play a critical role in allowing the cell to differentiate between non-self antigen (that needs to be presented) and self-antigen (that can safely be destroyed). Once activated, TLRs will trigger downstream molecules (e.g. NFκB, AP1, IRF, etc.) to begin production of inflammatory cytokines, and will also trigger conformational changes in the DC to increase surface area and upregulation of costimulatory molecules (e.g. CD80/86, CD40) to encourage T-cell activation.

> [!NOTE] Initiating the T-cell response needs _two_ signals:
> **Signal One:** T cells are generated in the Thymus and are programmed to be specific for one particular antigen. Once they leave the thymus, they circulate throughout the body until they recognise their antigen on the surface of antigen presenting cells (APCs). The T cell receptor (TCR) on both CD4+ helper T cells and CD8+ cytotoxic T cells bind to the antigen as it is held in a structure called the MHC complex, on the surface of the APC. This triggers initial activation of the T cells. The CD4 and CD8 molecules then bind to the MHC molecule, stabilising the whole structure. This initial binding between a T cell specific for one antigen and the antigen-MHC it matches sets the whole response in motion. This normally takes place in the secondary lymphoid organs.
> 
> **Signal Two:** In addition to TCR binding to antigen-loaded MHC, both helper T cells and cytotoxic T cells require a number of secondary signals to become activated and respond to the threat. In the case of helper T cells, the first of these is provided by CD28. This molecule on the T cell binds to one of two molecules on the APC – B7.1 (CD80) or B7.2 (CD86) – and initiates T-cell proliferation. This process leads to the production of many millions of T cells that recognise the antigen. To control the response, stimulation of CD28 by B7 induces the production of CTLA-4 (CD152). This molecule competes with CD28 for B7 and so reduces activation signals to the T cell and winds down the immune response. Cytotoxic T cells are less reliant on CD28 for activation but do require signals from other co-stimulatory molecules such as CD70 and 4-1BB (CD137). 

![](Innate%20to%20Adaptive%20Responses/image%203.png)
- - -
 ### Cytokines in Adaptive Host Defence
Once activated, T-cells will begin to express CD40L, which differentiates from naive T-cells. We can further classify effector T-cells by the cytokiens that they produce:
| Th Subset | Directing Cytokine | Cytokines Produced           | Function                                                     | Host Defence Against              | Role in Disease                               |
|-----------|--------------------|------------------------------|--------------------------------------------------------------|-----------------------------------|-----------------------------------------------|
| TH1       | IL-12, IFNγ        | IFNγ, TNFα                   | Cell mediated immune responses against intracellular pathogens | Intracellular microbes            | Immune-mediated chronic inflammatory disease  |
| TH2       | IL-4               | IL-4, IL-5<br>IL-9, IL-13    | Humoral + IgE immunity                                       | Helminthic parasites              | Allergic and atopic disorders                 |
| TH17      | TGFβ, IL-6, IL-23  | IL-17<br>IL-21, IL-22, IL-23 | Activate neutrophils against extracellular pahogens          | Extracellular bacteria and fungi  | Immune-mediated chronic inflammatory disease  |
| TREG      | TGFβ, IL-10        | IL-10, TGFβ, IL-35           | Modulate effector T-cell responses                           |                                   |                                               |
Note that T cells require a costimulatory signal from CD80/86 via CD28 to proliferate - this is the pathway exploited by [[oncology/Immune Checkpoint Inhibition|immune checkpoint inhibition]], as CTLA4 also binds CD80.
- - -
![](Innate%20to%20Adaptive%20Responses/image.png)