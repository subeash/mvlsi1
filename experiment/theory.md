## Theory

<div class="heading">
    Introduction to MOS Capacitor
</div><!-- Write the section content inside a paragraph element, we can also include images with &lt;img&gt; tag -->

<div class="content" >                            
        
<p> <p align="justify" class="content">The Metal-Oxide-Semiconductor (MOS) structure, universally referred as the “MOS”, besides forming the basis of the working of the MOS Field Effect Transistor (MOSFET) which is the backbone of the integrated circuits, lends itself as a diagnostic tool for determining the quality of the process used in the fabrication of an integrated circuit. Maintaining the quality and reliability of gate oxides is one of the most critical and challenging tasks in any semiconductor fabrication. Electrical characterization and monitoring is critical for maintaining gate oxide uniformity. Many electrical characterization techniques have been developed over the years to characterize gate dielectric quality. However, the most commonly used tool for studying gate oxide quality in detail is the Capacitance-Voltage (C-V) technique. C-V test results offer a wealth of device and process information, including bulk and interface charges and many MOS device parameters.<p>
<p align="justify" class="content">The importance of C-V measurement techniques is that a large number of device parameters can be extracted from the high frequency C-V curves that is described here and also the quasi-static C-V. These parameters can provide critical device and process information. One can divide the parameters roughly into three groups. The first group includes typical MOS device parameters such as flat band voltage, threshold voltage, etc. The next group, oxide charge parameters, includes interface trap charge density, mobile ion charge density, etc. The third group consists of doping-related parameters. The following parameters can be extracted from MOS capacitor measurements:</p>

<p align="justify" class="content">
Oxide (dielectric) thickness <br />

Charges in the oxide <br />

Oxide breakdown strength <br />

Conductivity type <br />

Doping concentration <br />

Doping profile in the silicon <br />

Work function differences <br />

Interface trap densities <br />

Properties of electron and hole traps <br />

Minority carrier lifetime in silicon <br /></p><br />

<p align="justify" class="content">In order to extract the above parameters several capacitance-voltage (C-V) measurement techniques have been developed. These include (i) High Frequency C-V Measurement, (ii) Low Frequency or Quasi-static C-V Measurement, (iii) Pulsed C-V measurement, and (iv) Capacitance-time (C-t) measurement. Also, using C-t data, carrier generation lifetime and recombination lifetime can be extracted. In particular, various current-voltage (I-V) characterization methods have been developed, including the following:</p>

<p align="justify" class="content">
Time-Dependent Dielectric Breakdown (TDDB) <br /> <br />

Charge to Breakdown (QBD) <br /> <br />

Tunnelling Current (Fowler-Nordheim or Direct Tunnelling) <br /> <br />

Stress-Induced Leakage Current (SILC) <br /> <br /></p>

<h2 align="left" ><u>MOS CAPACITOR</u>: Experiment Manual</h2>

<p align="justify" class="content">The MOS capacitor (see figure 1) is often used as a test structure due to its simple fabrication procedure. The structure can yield important information regarding the properties of the dielectric used, underlying silicon and dielectric/silicon interface. Simply stated, the MOS structure, since it is a sandwich of metal-insulator-semiconductor (MIS), constitutes a capacitor whose capacitance varies in response to the total voltage applied. This variation is due to the semiconductor which can be depleted of its majority carriers to a certain depth by the repulsive electric field forces created by the voltage applied to the metal (gate) and effectively adding another insulating layer of variable thickness to the oxide above it.</p>

<div class="content" >                            
<p><center><img style="width:251px;height:139px;" src="images/mos1.jpg" alt="" /></center></p>
</div>

<h2 align="left" ><u>Classification of insulator charges</u></h2>

<p align="justify" class="content">There are four general types of charges associated with the SiO2-Si system. They are interface trap charge, fixed oxide charge, oxide trap charge, and mobile oxide charge. The interface trap charge Qit is the charge, which is due to (1) structural, oxidation-induced defects, (2) metal impurities, or (3) incomplete bonds and absorption of foreign material at the silicon surface. The interface trap charge can be positive or negative charges and located at the Si/SiO2 interface. An incomplete silicon bond will create an interface trap. The density of the interface trap charge can be reduced when the surface is thermally oxidized. This property of the Si/SiO2 system is unique and is one of the major reasons for using thermally grown SiO2 for gate oxide applications. See Figure 2 for different types of charges in a MOS structure.</p>

<div class="content" >                            
<p><center><img style="width:262px;height:150px;" src="images/ins1.jpg" alt="" /></center></p>
</div>

<p align="justify" class="content">Typical values for Qit lie in the range of 1x1010 to 3x1011 cm-2, depending on the orientation of the silicon crystal and on the process history. The interface trap can be positively or negatively charged depending whether the trap is acceptor or donor type. An acceptor-type trap becomes negatively charged when it gains an extra electron and becomes neutral when it loses the extra electron. A donor-type trap becomes positively charged when it losses an electron and neutral when it regains the lost electron.</p> <br />

<p align="justify" class="content">The fixed oxide charge Qf is a positive charge, due primarily to structural defects in the oxide layer less that 25 Å from the Si/SiO2 interface. This charge is immobile under an electric field. However, it is affected by temperature above 500oC and by the ambient atmosphere. Typical values for Qf are in the order of 1010-1011 charges per cm-2, depending on process conditions. Qf is not affected by the thickness of the oxide. However, it increases when the structure is exposed to high energy radiation. The density of the fixed oxide charge can be reduced by high temperature annealing.</p> <br />

<p align="justify" class="content">The oxide trap charge Qot is due to imperfections throughout the bulk of the oxide layer. It can be positive or negative depending whether holes or electrons are trapped in the bulk of the oxide. Trapping may result from ionizing radiation, or other similar processes and the threshold voltage can shift in either direction.</p> <br />

<p align="justify" class="content">The mobile oxide charge Qm is the most significant charge component in the insulator. It is due to ionised impurities such as sodium (Na+) and, to a less extent, potassium (K+) and lithium (Li+). The alkali ions, and in particular Na, are difficult to control. The effect of these various charges associated with the SiO2/Si system can be determined by using different C-V measurements. For instance, HF C-V measurement is used to determine the effective interface charge Qeff, by assuming all the insulator charge located at the silicon surface. The effective interface charge will cause the similar shift in the C-V curve as that of the actual insulator charge of unknown distribution whereas the Quasi-static C-V method can be used to determine the distribution of the interface trapped charge throughout the band gap.</p> <br />

<p align="justify" class="content">Therefore, the capacitance, starting from its maximum which is for fields attracting the majority carriers to the semiconductor’s surface (the “accumulation” mode) decreases steadily as the field is reversed to cause “depletion” of them near the surface until the oppositely charged minority carriers are attracted in large numbers to the oxide interface to shield the depletion layer from further increases in the field. At that point (1) the depletion thickness stops increasing, and (2) its capacitance is compromised by a leakage resistance due to the traffic of the minority carriers from the bulk to/from the inversion layer.</p> <br />

<p align="justify" class="content">In a MOS structure the device starts conducting through the inversion layer, i.e., it turns on. In the accumulation and depletion modes the minority carriers due to their small number cannot affect the C-V characteristics (see Figure 3). However, after the onset of inversion and particularly at low frequencies when the depletion capacitance has high impedance they can effectively short it with the leakage resistance they introduced in parallel and bring the measured capacitance back up to the oxide capacitance value. At high frequencies (1 MHz and above) this effect is minimal as well as the complications introduced by interface states between the semiconductor and the oxide. Therefore, high frequency C-V measurements are preferred when the minority carriers and their interaction with interface states are not of interest.</p> <br />

<div class="content" >                            
<p><center><img style="width:310px;height:174px;" src="images/ins2.jpg" alt="" /></center></p>
</div>


<p align="justify" class="content">in this experiment, a C-V measurement setup built using an inexpensive 1 MHz capacitance meter (Agilent E4980A) is shown to be effectively used to evaluate the quality of the MOS structures processed in our Micro Fabrication laboratory. The tools required are standard GPIB interfaced instruments which are controlled by a personal computer which serves for data acquisition and data processing as well as control. Such setups are replacing non-computer interfaced equipment in electrical engineering laboratories and can be used to serve not only as electronic test bench but for in-situ tools for electronic design automation, design verification, device characterization, and SPICE model parameter extraction as an integral part of measurement laboratory.</p> <br />



<p align="justify" class="content">For MOS C-V measurements the sample needs to be biased at voltage which will be stepped from accumulation to inversion, and a small signal sinusoidal source (about 10 mV in amplitude) for capacitance determination. See diagrams for the detail of the experimental setup.</p> <br />



<p align="justify" class="content">A home developed data analysis software, originally written in C for automated extraction of MOS capacitor parameters. In the following procedure for high frequency (HF) C-V measurement is described. The measured C-V data is directly fed into appropriate columns from a Agilent E4980A via a GPIB interface card. The dielectric properties that can be extracted from HF C-V measurements are average doping concentration, effective interface charge and threshold voltage.</p> <br />



<p align="justify" class="content">The Extraction Procedure <br /> <br />

(1) Square of the inverse-capacitance of an MOS structure is expected to be vary linearly with the applied bias voltage in the depletion region; <br /><br /> 

(2) Its slope yields the doping concentration;<br /><br /> 

(3) Its intersection point with the maximum capacitance asymptote yields the flat band voltage, VFB; and<br /><br /> 

(4) Its intersection point with the minimum capacitance asymptote yields the onset of heavy inversion or the threshold voltage, VT. </p> <br />


<h2 align="left" >Analysis Techniques</h2>

<p align="justify" class="content">Many of the above mentioned parameters are extractable from one or more of the following: <br /><br />

1. High frequency C-V curves. <br />
2. Low frequency or quasi-static C-V <br />
3. Conductance-voltage (G-V) curves often taken at various frequencies. <br />

<p align="justify" class="content">For example, a typical parameter of interest is the interface trap density, Dit, as a function of energy in the silicon band gap. A low concentration or interface traps is indicative of a high quality interface between the oxide and semiconductor.<p>

<p align="justify" class="content">Possible methods for finding Dit and their relative merits are: <br /> <br />

1. G-V data. This is the most accurate technique developed, but it is more involved to implement than its alternatives and yields results only over part of the band gap.<br />
2. Comparison of an experimental quasi-static curve to an experimental 1 MHz curve. This yields data over a wider portion of the band gap and eliminates the need for any theoretical comparison.<br />
3. Comparison of an experimental quasi-static curve to the theoretical quasi-static curve. The results cover the widest range in the band gap, but the issue of converting the plot of capacitance vs. gate voltage to capacitance vs. surface potential in the silicon must be addressed.<br /></p>

<h2 align="left" >Discussions and Conclusions</h2>

<p align="justify" class="content">The measurement setup and the MOS characterization procedures outlined in this manual may be used to characterize the distribution of the doping density, oxide thickness, flat band and threshold voltages and the interface and oxide charge. The C-V data obtained are used to extract several MOS diode parameters.</p>



</div>

 <script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3.2.2/es5/tex-mml-chtml.js"></script>    
 
