# Echocardiography
#bpt/racp_cls #bpt/cardiology
- - -
### Overview
Echocardiography, particularly transthoracic echocardiography, is a useful and (often) noninvasive [[cardiology/Cardiac Imaging|cardiac imaging]] modality that provides a range of useful information on structural and functional cardiac parameters.
- - -
### Terminology
There are four windows through which views of the heart are obtained during transthoracic echocardiography:
1. Parasternal (probe placed vertically along the sternum) -> front of heart structures (e.g. RV, AV, aortic root, LVOT, LV)
2. Apical (anterior axillary line pointing along the axis of the heart) -> apical structures (LV, RV)
3. Subcostal (looking ‘up’ from under the xiphisternum) -> base of heart structures (pericardium, RV)
4. Suprasternal view (looking down from sternal notch) -> aortic arch, SVC
![](Echocardiography/image.png)

In addition to this, there are two planes of imaging:
- Long axis -> looking from apex-base or vice-versa
  - Parasternal 
  - Apical
- Short axis -> perpendicular to long-axis/cross sectional
  - Parasternal
  - Subcostal
- Four-chamber -> quasi-coronal 
- - -
### Views
#### PLAX = parasternal long axis view:
- Top of triangle = patient’s right axilla
- Base of triangle = patient’s left axilla

Useful for visualising left ventricle, LVOT, and aorta:
![](Echocardiography/image%202.png)

But can easily be tilted to allow for visualisation of the RV and RVOT:
![](Echocardiography/image%203.png)

#### PSAX = parasternal short axis view:
‘Cuts’ through the base of the heart to allow for visualisation of the valves:
![](Echocardiography/image%204.png)
![](Echocardiography/image%205.png)
Also useful for assessing:
- Aortic valve
- Interatrial septum
- Coronary cusps
- Pulmonary valve
- Pulmonary arterial branches
- Papillary muscles 

#### Apical Four Chamber:
Orthogonal to the long-axis views:
![](Echocardiography/image%206.png)
Essentially looking ‘up’ at the heart from the apex, with good ability to visualise all four chambers, as well as function of the TV and MV. 
![](Echocardiography/image%207.png)

#### Subcostal Four Chamber:
Begins with the transducer being placed under the xiphisternum and pointed in a cephalad direction: 
![](Echocardiography/image%208.png)
![](Echocardiography/image%209.png)
Yields a four chamber view that is particularly useful for:
- Doppler views of ASD/shunt
- RV - e.g. [[cardiology/Arrhythmogenic Cardiomyopathy|arrhythmogenic cardiomyopathy]]

Can additionally be used to assess the abdominal vessels, which is useful for measuring fluid status:
![](Echocardiography/image%2010.png)
The ‘classic’ test here being the sniff test: if the IVC does not collapse with a sniff, it suggests that the IVC/RA pressures are elevated. 

#### Suprasternal Long Axis View:
Looking down from the sternal notch:
![](Echocardiography/image%2011.png)
Relatively limited utility except for assessing the aortic arch.
- - -
### Practical Points in Echocardiography
#### Assessing Ventricular Function
The measure of ventricular function begins with the ejection fraction, the percentage of ventricular diastolic volume ejected with each systole:
> `EF (%) = [(EDV - ESV) / (EDV)] * 100`

This is classically obtained using _Simpson’s method_, which utilises the LV perpendicular length changing LV-area during systole and diastole, defined as the black-white interfact visible on echocardiogram to generate a calculated volume:
![](Echocardiography/image%2012.png)
While still useful and widely used, the 2D Simpson biplane method is technically outperformed by newer 3D methods.

#### Global Longitudinal Strain
To understand GLS, think of the heart as a cone. As actin interacts with myosin under the effect of calcium and ATP in systole, this causes the heart to contract linearly about ~20% in the longitudinal direction (ejection). After systole, the heart then quickly relaxes actively under the effect of tropomyosin, and regains ~15% of the length lost in systole (rapid inflow). During this time, the mitral valve opens to allow ventricular filling. This is folowed by a mid diastolic pause in filling (diastasis). The remaining length is regained during atrial contraction.

Visualising the heart as a cone from below, we can then visualise longitudinal strain as shortening in each each direction in the familiar arterial territories:
![](Echocardiography/image%2013.png)

GLS is particularly utilised in cardio-oncology protocols for [[oncology/Chemotherapy Toxicities|chemotherapy toxicities]] related to anthracyclines and trastuzumab, as changes in strain can often precede changes in ejection fraction. 
- - -
### Doppler Echocardiography
In the context of echocardiography, Doppler refers to a reflected velocity map, that is mapped on a Cartesian plane, where:
- The x-axis = time
- The y-axis = velocity (positive = towards the transducer)

The simplified form of the Bernoulli equation (see [[Physics for Medicine]]) can then be used to derive the pressure gradient across two points in time:
> `ΔP = 4v^2`
![](Echocardiography/image%2014.png)

#### Aortic Valve
![](Echocardiography/image%2015.png)
The normal peak AV velocity is in the vicinity of 1.1m/s, giving a peak gradient of 5mmHg. The average velocity is the area under the curve, and the simplified Bernoulli equation can be used to calculate a mean gradient based on this. 

The ‘normal’ values for the aortic valve are:
- Vmax = 1.0-2.5m/s
- PGmax = 4-25mmHg
- AVA = 1.5-3.0sqcm

This aims to echo the information that can be obtained from invasive measurements:
![](Echocardiography/image%2016.png)

#### Velocity Time Integral
Unlike continuous wave Doppler, the velocity time integral is calcultaed by taking a number of time points during systole to calculate the area under the curve, measured as the VTI in cm. Multiplying this by the cross sectional area where the velocity was interrogated allows for the derivation of the volume at that point in the circulation. 
- - -
### Colour Doppler Imaging 
Blue = away from the transducer
Red = towards the transducer
![](Echocardiography/image%2017.png)
High speeds (>0.5m/s) are unable to be directionally placed, and are thus labelled ‘turbulent’ (green) by the software. This is strongly associated with the presence of a pathological valvular lesion. 
- - -
### Diastology
To quote the great Neil Strathmore, ‘a thick ventricle is a stiff ventricle’. With time, as the heart strains against elevated systemic pressures it can hypertrophy and stiffen. In response to this, receptors throughout the body (not necessarily the heart) promote fluid retention to maintain filling pressures:
![](Echocardiography/image%2018.png)

Echocardiogram can approximately calculate elevated filling pressures through various algorithms. Transmitral pulse wave Doppler is the key technology here, that measures two entities:
- The early wave (E): passive ventricular filling
  - Deceleration time: the rate of decay of the E wave
- The atrial wave (A): active ventricular filling during atrial contraction

Similar waveforms (S, D, and Ar/reversal) can be calculated for the left atrium and the pulmonic veins. Finally, we can measure the isovolumic filling time, that correlates inversely as atrial filling pressures.

The movement of the mitral annulus (tissue velocity) is also measured using pulsed wave Doppler:
- e’ = displacement of the mitral annulus during passive ventricular filling

The ratio of E to e’ (E/e’) is one of the most important markers of diastolic failure:
- As left atrial filling pressures increase, so too does E, but
- As the ventricle stiffens, E’ will decrease

This means that as diastolic function becomes increasingly impaired, the E/e’ ratio will _increase_. Similarly, the relative importance of active atrial filling becomes more important, and the E/A ratio also diminishes. However, in the situation of advanced diastolic dysfunction, fluid retention can lead to a pseudonormalisation of the E/A ratio, which can be distinguished from true normal by the D-wave dominance in the pulmonary vein pulsed wave Doppler:
![](Echocardiography/image%2019.png)
![](Echocardiography/image%2020.png)
The E/e’ ratio remains linear and does not pseudonormalise, allowing us to distinguish _where_ on the U-shaped curve a patient is sitting. 

There are, thus, five parameters used in the assessment of LV diastolic function:
1. Mitral inflow velocity (E/A)
2. Mitral annular velocities (septal and lateral e’)
3. E/e’
4. TR velocity (note - the patient thus needs _some_ TR for diastolic function to be correctly assessed)
5. LA indexed volume 
- - -
### [[Pulmonary Hypertension]] and Echocardiography
Swann-Ganz balloon catheterisation revolutionised the investigation of pulmonary hypertension by allowing the (almost) direct measurement of left atrial pressures. 
![](Echocardiography/image%2021.png)
Tricuspid regurgitation measured using colour Doppler is critical to the diagnosis of PH. The ratio of TRVmax (a surrogate of PAP) to E/E’ (a surrogate of LAP) is called the ePLAR, and, if reduced (below 0.28), suggests that the pulmonary hypertension is post-capillary in aetiology. 
- - -
### Stress Echocardiography
Determines induced ischaemia via the detection of RWMAs. Particular utility in the workup of dyspnoea. General protocol is to begin with a resting ECG and TTE, and then exercise the patient. After this, the patient returns to the bed and has views of the:
- PSLAX
- PSSAX
- A4
- A2
- Apical LAX
- Apixal SAX

After this, the images are adjusted for heart rate to allow for comparison of RWMAs in the pre- and post-exercise images. This is particularly useful for sytolic function. Diastole can also be assessed using pre- and post-exercise E/e’ ratios.
- - -
### Transoesophageal Echocardiography
The oesophagus sits right behind the LA, making it the perfect spot from which to get views of the heart:
![](Echocardiography/image%2022.png)
![](Echocardiography/image%2023.png)

There are three fundamental places where TOE is used:
1. Endocarditis
   - Acute staphylococcal endocarditis - often associated with abscess formation and tissue destruction as well as vegetation formation
   - Subacute (typically streptococcal, etc.) endocarditis - tend to be more associated with vegetations alone without severe tissue destruction
   - Culture-negative endocarditis
   - Non-infective endocarditis (e.g. marantic/malignant, Libman-Sacks)
2. TOE-DCR in AF
   - Not needed if patient anticoagulated >4/52 (‘blind DCR’)
   - Can cardiovert in the absence of clot, or else anticoagulate for four weeks prior to blind DCR
   - Most common spot is the left atrial appendage - can occasionally get ‘smoke’ in the LAA which is itself an indication for anticoagulation
   - TOE is also used to guide the Watchman procedure
3. Intraoperative TOE
   - Allows for device implantation to within 1mm of accuracy (e.g. MitraClip, [[transcatheter aortic valve implantation]]) 