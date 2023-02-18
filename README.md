# Intel Ckt Training
This repo will be used of deposition of training documentations.

## Table of contents
+ **[ Day 1 - Overview of VLSI Design ](https://github.com/TengBoonHuei/intel_ckt_training#day-1)**
  <details><summary> Theory </summary>
  
  [Theory - Overview of VLSI Design](https://github.com/TengBoonHuei/intel_ckt_training/blob/main/README.md#theory---overview-of-vlsi-design)
  
  </details>
    
  <details><summary> Assignments </summary>
    
  [Assignments - Prerequisite Assignments](https://github.com/TengBoonHuei/intel_ckt_training/blob/main/README.md#prerequisite-assignments)
 
  </details>

+ **[Day 2 - Analog VLSI Design Flow & CMOS Manufacturing Process](https://github.com/TengBoonHuei/intel_ckt_training/blob/main/README.md#day-2)**
  <details><summary> Theory </summary>
  
  [Theory - Analog VLSI Design Flow & CMOS Manufacturing Process](https://github.com/TengBoonHuei/intel_ckt_training/blob/main/README.md#theory---analog-vlsi-design-flow--cmos-manufacturing-process)
  
  </details>
  
  <details><summary> Assignment </summary>
  
  [Assignment - Draw Circuit from Layouts](https://github.com/TengBoonHuei/intel_ckt_training/blob/main/README.md#fabrication-process--layout)
  
  </details>  
  
+ **[Day 3 - CMOS Fabrication Process in DSM & UDSM Technology](https://github.com/TengBoonHuei/intel_ckt_training/blob/main/README.md#day-3)**
  <details><summary> Theory </summary>
  
  [Theory - CMOS Fabrication Process in DSM & UDSM Technology](https://github.com/TengBoonHuei/intel_ckt_training/blob/main/README.md#theory---cmos-fabrication-process-in-dsm--udsm-technology)
  
  </details>
  
  <details><summary> Assignment </summary>
  
  [Assignment - DSM & UDSM Technology](https://github.com/TengBoonHuei/intel_ckt_training/blob/main/README.md#dsm--udsm-technology)
  
  </details>
  
+ **[Day 4 - Metal-Oxide-Semicondutor Structure](https://github.com/TengBoonHuei/intel_ckt_training#day-4)**
  <details><summary> Theory </summary>
  
  [Theory - Metal-Oxide-Semiconductor Structure](https://github.com/TengBoonHuei/intel_ckt_training/blob/main/README.md#theory---metal-oxide-semiconductor-mos-structure)
  
  </details>
  
  <details><summary> Assignment </summary>
  
  [Assignment - Metal-Oxide-Semiconductor Structure](https://github.com/TengBoonHuei/intel_ckt_training/blob/main/README.md#metal-oxide-semiconductor-mos-structure)
  
  </details>
  
+ **[Day 5 - Metal-Oxide-Semicondutor Feild-Effect Transistor](https://github.com/TengBoonHuei/intel_ckt_training/blob/main/README.md#day-5)**
  <details><summary> Theory </summary>
  
  [Theory - Metal-Oxide-Semiconductor Feild-Effect Transistor](https://github.com/TengBoonHuei/intel_ckt_training/blob/main/README.md#theory---metal-oxide-semiconductor-feild-effect-transistor-mosfet)
  
  </details>
  
+ **[Day 6 - MOSFET Intrinsic Capacitance](https://github.com/TengBoonHuei/intel_ckt_training/blob/main/README.md#day-6)**
  <details><summary> Theory </summary>
  
  [Theory - MOSFET Intrinsic Capacitance](https://github.com/TengBoonHuei/intel_ckt_training/blob/main/README.md#theory---mosfet-intrinsic-capacitances)
  
  </details>
  
  <details><summary> Assignment </summary>
  
  [Assignment - MOSFET with Capacitor](https://github.com/TengBoonHuei/intel_ckt_training/blob/main/README.md#mosfet-with-capacitor)
  
  </details>
  
+ **[Day 7 - CMOS Inverter](https://github.com/TengBoonHuei/intel_ckt_training/blob/main/README.md#day-7)**
  <details><summary> Theory </summary>
  
  [Theory - CMOS Inverter](https://github.com/TengBoonHuei/intel_ckt_training/blob/main/README.md#theory---cmos-inverter)
  
  </details>
  
  <details><summary> Assignment </summary>
  
  [Assignment - CMOS inverter simulation](https://github.com/TengBoonHuei/intel_ckt_training/blob/main/README.md#cmos-inverter-simulation)
  
  </details>
  
+ **[Day 8 - MOSFET Parameter Extraction, Scaling, Short Channel Effects and PVT Variations](https://github.com/TengBoonHuei/intel_ckt_training/blob/main/README.md#day-8)**
  <details><summary> Theory </summary>
  
  [Theory - MOSFET Parameter Extraction, Scaling, Short Channel Effect & PVT Variations](https://github.com/TengBoonHuei/intel_ckt_training/blob/main/README.md#theory---mosfet-parameter-extraction-scaling-short-channel-effects--pvt-variations)
  
  </details>
  
  <details><summary> Assignment </summary>
  
  [Assignment - Parameter Extractions](https://github.com/TengBoonHuei/intel_ckt_training/blob/main/README.md#parameter-extraction)
  
  </details>
  
+ **[Day 9 - Combinational Digital Logic Circuits](https://github.com/TengBoonHuei/intel_ckt_training/blob/main/README.md#day-9)**
  <details><summary> Theory </summary>
  
  [Theory - Combinational Digital Logic Circuits]()
  
  </details>
  
  <details><summary> Assignment </summary>
  
  [Assignment - Combinational Logic Circuit Simulation]()
  
  </details>
  
## Day 1
## Theory - Overview of VLSI Design

<details><summary> Chip-to-wafer </summary>
  
### **Chip-to-wafer**
#### Packaged Chip
* Die is placed at the center of the chip (package).
* Wire bonding is the method of interconnecting the die to the external world.
* The package's function is to connect the silicon die to the circuit board.
* The package are encapsulated, so to protect the die inside the chip.
* Evolution and different types of Packaged Chip, example:
  ![image](https://user-images.githubusercontent.com/121993909/211232190-d5a756e7-5c60-453d-aa2a-c1f1d014273c.png)

#### Die and Wafer
* generally die size is (1x1)mm or (1x2)mm
* wafer diameter is around 12 inch ~ 300 mm
* a single wafer contains 10’s of thousands die  

</details>

<details><summary> Overview of Inside the Die </summary>


### **Overview of Inside the Die**
![image](https://user-images.githubusercontent.com/121993909/211232757-c48ace28-45d5-4a7d-9f51-a21b1f451c03.png)
* Memory & Memory Controller
  * SRAM or DRAM
  * Memory Controller
  
* Digital
  * Made by standard cells using semi-custom VLSI design flow.
  * Eg. Gates, MUX, Decoder, Counters, FSMs
  
* Analog and RF
  * Made by custom VLSI flow
  * Eg. VCO, LDO, Op-Amp, LPF/HPF, ADC/DAC
   </details>

<details><summary> Moore’s Law </summary>

* Moore’s Law defines the number of transistors in a dense integrated circuit doubles every 2 years
* Every two years, the feature size is reduced by 1/sqrt(2) times

</details>

<details><summary> VLSI Design Methodology </summary>

### Critical factors of design execution:
  
  * functionality, performance & quality
  * low cost
  * faster time-to-market
  
### **VLSI Design Methodology**
  
Two types of VLSI Design Styles:
  
1. Field-Pragrammable Gate Array (FPGA)
    * faster prototyping and cost-effective, basically use in prototyping and testing
    * typically consists of input/output buffers, array of configurable logic blocks (CLBs) and programmable interconnect

2. Application Speciic Intergrated Circuit (ASIC)
    * Permanent circuitry. Once the application specific circuit is taped-out into silicon, it cannot be changed.
    * Higher cost as need to start design from scratch. 
    * More power efficient, power consumption of ASICs can be very minutely controlled and optimized.
  
</details>

<details><summary> VLSI Design Quality </summary>

### **VLSI Design Quality**
#### Importamt criteria to measure the design quality:
1. Testability
  
    * Generation of good test vector
    * Availability of good test fixture at speed
</details>

<details><summary> Package Technology </summary>


### **Package Technology**
* VLSI chips can fail if various packaging constraints and parasitic are not included in the design phase 
* number of ground planes, power planes and the bonding pads greatly affect the behaviours of on-chip power and ground buses
* length of bonding wire and lead length of the package can create serious issue  
     </details>

<details><summary> CAD Tools </summary>

### **CAD Tools**
* essential for timely development of integrated circuits
* CAD technology for VLSI chip design can be categorized into the following areas:
    * High-level synthesis
  
  </details>
  
<details><summary> Assignment </summary>

### **Prerequisite Assignments**
  * [RC Circuit](https://drive.google.com/file/d/1x5PnTjW8ha-spVDT3cuYXojVoWyKdVjv/view?usp=share_link)
  * [Digital Circuits](https://drive.google.com/file/d/1Ww-4ZigmUcCJQGWNldrs159sRDHLK9hX/view?usp=share_link)
  * [Electrical Circuits]()
  * [Semiconductor Devices]()
  
</details>
  
## Day 2
## Theory - Analog VLSI Design Flow & CMOS Manufacturing Process

<details><summary> Analog IC Design Process </summary>

### **Analog IC Design Process**
  
![image](https://user-images.githubusercontent.com/121993909/211451557-032a642c-2d99-4425-823c-051fa9349c8f.png)
  
#### Electrical Design
  * Electrical design requires active and passive deice electrical models for:
    * Creating the design
    * Verifying the design
    * Determining the robustness of the design

#### Physical Design
  * Physical design the the process of representing the electrical design in a layout.
  * Physical design needs:
    * Entering various geometries
    * Folow Design Rule Checks (DRC)
    * Check Layout versus Schematic (LVS)
    * Extract Parasitic
  
#### Test Design
  * Test design is the process of coordinating, planning, and implementing the measurement of the analog and integrated circuit performance.
  * Type of test:
    * Functional
    * Parametric
    * Static
    * Dynamic
</details>
  
<details><summary> CAD tools & PDK for Analog IC Design </summary>
  
  ### **CAD Tools and PDK for Analog IC Design**
  
  ![image](https://user-images.githubusercontent.com/121993909/211453646-cca9f344-42c6-480d-b121-a4d0f558df7d.png)
</details>

<details><summary> CMOS Fabrication Process </summary>
  
  ### **CMOS Fabrication Process**
  
  #### CMOS Fabrication Process
  1. Wafer Formation (sand-to-silicon)
      * Controlled amount of impurities are added to the pure molten silicon in a heating crucible.
      * a seed crystal is dipped into the melt to initiate crystal growth.
      * the seed are rotated at a certain rate to withdraw the molten silicon vertically to form a fixed diameter ingot.
      * ingot are then sliced into ~1mm thick wafers.
  
  2. Photolitography
      * The wafer is coated with the photoresist and subjected to selective illumination through the photomask.
      * A photomask is constructed with chromium covered quartz glass. A UV light source is used to expose the photoresist (exposed area are hardening).
      * A developer solvent is then used to dissolve the soluble unexposed photoresist, leaving island of insoluble exposed photoresist.
        ![image](https://user-images.githubusercontent.com/121993909/211456680-2676ea80-8eb8-434c-b140-42276780911f.png)

  3. Well & Channel Formation
      #### 4 types of CMOS Technology Process
        * N-well process
  
          ![image](https://user-images.githubusercontent.com/121993909/211458587-90e4fdb4-d372-44ec-9403-d651bcf753ef.png)

        * P-well process
  
          ![image](https://user-images.githubusercontent.com/121993909/211458630-47d24354-31e0-4151-92c3-f3017092e81b.png)

        * Twin-well process
  
          ![image](https://user-images.githubusercontent.com/121993909/211458652-82472e26-341b-4735-bee2-e906be7ddfd9.png)

        * Triple-will process
  
          ![image](https://user-images.githubusercontent.com/121993909/211458673-05f294da-a2a1-4048-bfd9-bd940f188c7e.png)
      
  4. Silicon Dioxide (SiO2) Deposition
      #### Wet Oxidation: oxidizing atmosphere contains water vapor.
        * Temperature between 900C to 1000C
        * Rapid process
      
      #### Dry Oxidation: oxidizing atmosphere with pure oxigen.
        * Temperature ~1200C to achieve acceptable growth rate.
        * form better quality oxide layer.
  
      #### Atomic Layer Deposition (ALD)
        * mixing of chemicals on top of the surface to form oxide layer.
  
  5. Isolation
      * Individual devices in CMOS process need to be isolated from one another to prevent unexpected interactions.
  
  6. Gate Oxide Creation
      * Formation of thin gate oxide layer on the surface of the gate region.
  
  7. Gate and Drain/Source Formation
      * Formation of thin gate oxide and thick feild oxide.
      * Deposition and Patterning polysilicon to create the gates.
      * Etch away the exposed gate oxide and implant the p-diff and n-diff at where the region of p/n channels.
  
  8. Contacts and Metallization
      * Contact cuts are made to source, drain and gate according to the contact mask. 
  
  9. Passivation
      * Adding a protective glass layer that prevents the ingress of contaminants.
  
  10. Metrology
      * A process of measuring the parameters like the photomask pattern, critical dimension (CD), and image placement are matching between all the metal layers.
</details>

<details><summary> Cross-Sectional Illustration of CMOS Fabrication Process </summary>
  
  ### **Cross-Sectional Illustration of CMOS Fabrication Process**
  
  Step 1: Substrate
  * Start the process with P-substrate.
  
    ![image](https://user-images.githubusercontent.com/121993909/211505785-f35ec678-d11c-453c-8ba9-0d5776c6d554.png)

  Step 2: Oxidation
  * Oxidation with high-purity oxygen and hydrogen at 1000C temperature.
  
    ![image](https://user-images.githubusercontent.com/121993909/211506617-c753dc8a-4b44-497e-a399-5af8d536016c.png)

  Step 3: Photoresist
  * Foring a layer of light-sensitive polymer that hardens when exposed to light.
  
    ![image](https://user-images.githubusercontent.com/121993909/211507494-1e0d3c3d-f4d8-4402-b43c-b7768ff05010.png)

  Step 4: Masking
  * Photoresist is exposed to UV rays through the n-well mask.
  
    ![image](https://user-images.githubusercontent.com/121993909/211507742-e66adc40-0d9c-4db4-b382-38909893eb28.png)

  Step 5: Photoresist removal
  * A part of the photoresist under unexposed region are removed by using the basic or acidic solution.
  
    ![image](https://user-images.githubusercontent.com/121993909/211508289-8fe4d504-ad35-47f5-82df-0765973abb2b.png)

  Step 6: Removal of SiO2 using acid etching
  * Removal of SiO2 oxidation layer through the open area by using hydrofluoric acid.
  
    ![image](https://user-images.githubusercontent.com/121993909/211508824-0177af3f-9fc6-4b15-bb96-9e6a31431599.png)

  Step 7: Removal of photoresist
  * Removal of photoresist
  
    ![image](https://user-images.githubusercontent.com/121993909/211509071-0201e29a-1881-4504-9d86-8457bebe5483.png)

  Step 8: Formation of N-well
  * By using ion implantation or diffusion process to form N-well.
  
    ![image](https://user-images.githubusercontent.com/121993909/211509539-fb589210-54a2-4dfe-a5bc-03626094b17a.png)

  Step 9: Removal of SiO2
  * Using the hydrofluoric acid to remove the remaining SiO2.
  
    ![image](https://user-images.githubusercontent.com/121993909/211509901-f9bf73f6-94f8-47df-ae8d-0325d593c019.png)

  Step 10: Deposition of Polysilicon
  * Chemical Vapor Deposition (CVD) process is used to deposit a very thin layer of gate oxide.
  * Followed by deposition of polysilicon layer.
  
    ![image](https://user-images.githubusercontent.com/121993909/211510643-bd58acef-9abe-4b04-ac94-2a3a35ae3587.png)

  Step 11: Removing the layer barring a small area for the "Gate"
  * Except the two small region required for forming the gates of PMOS and NMOS, the remaining layers are stripped off.
  
    ![image](https://user-images.githubusercontent.com/121993909/211511146-11085dd3-053d-471e-88e9-76f4f1639d2e.png)

  Step 12: Oxidation Process
  * Oxidation layer is formed on top of the surface, thin oxide layer at the gate region and the rest are thick oxide layer.
  
    ![image](https://user-images.githubusercontent.com/121993909/211512114-1437492f-f518-4495-8c70-82cbb379d858.png)

  Step 13: Masking and N-diffusion
  * By using masking process to open the small gaps for N-diffusion.
  
    ![image](https://user-images.githubusercontent.com/121993909/211512655-42e63b28-d756-4813-afe3-d92bb82d5520.png)

  * The n-type dopants are diffused or ion implanted to form the NMOS terminal.
  
    ![image](https://user-images.githubusercontent.com/121993909/211513092-a262785b-5e9c-4d3d-8098-3dd306036399.png)

  Step 14: Oxide stripping
  * The remaining oxidation layer are stripped off.
  
  Step 15: Masking and P-diffusion.
  * Similar to step 13, the P-diffusion regions are implanted with p-type dopants to form P-MOS terminal.
  
    ![image](https://user-images.githubusercontent.com/121993909/211514476-20234e1f-f3dc-455b-b8cf-64611de5a9de.png)

  Step 16: Thick field oxide formation
  * Forming thick-field oxide in all region except the PMOS and NMOS terminals.
  
    ![image](https://user-images.githubusercontent.com/121993909/211514947-ba64c7ed-51b9-40cf-931a-2d4ac772d30b.png)
  
  Step 17: Contact creation
  * Contact creation
  
    ![image](https://user-images.githubusercontent.com/121993909/211517947-de8ad7af-e7bc-4907-a59d-907ec960632c.png)
  
  Step 18: Metallization
  * Aluminium (Al) or Copper (Cu) deposited on the wafer.
  
    ![image](https://user-images.githubusercontent.com/121993909/211518849-4a19f47d-c2fa-4ebb-83ea-1bbe9335ddbb.png)

</details>

<details><summary> Assignment </summary>
  
  ### Fabrication Process & Layout

  + **[Fabrication Process & Layout](https://drive.google.com/file/d/1CxdaA5OUX5YnXoWtph7iwB4jn6LFVT-K/view?usp=share_link)**

</details>

## Day 3
## Theory - CMOS Fabrication Process In DSM & UDSM Technology
<details><summary> Isolation Process </summary>
  
  #### LOCOS vs STI Isolation Technique
  
  1. Local Oxidation of Silicon (LOCOS) Isolation:
      * Traditional isolation technique used in submicron process.
      * Limitation: bird's beak effect causing lost in surface area.
      * Advantage: simple process flow, high oxide quality

  2. Sallow Trench Isolation (STI):
      * Preffered isolation technique for deep-submicron process.
      * Advantage: avoids Bird's beak shape characteristic and allows forming a smaller isolation region.
      * Disadvantage: more complicated technique and large number of process steps.

</details>

<details><summary> DSM CMOS Fabrication Process </summary>
  
  #### Deep Submicron (DSM) CMOS Fabrication Process
  
  Step 1 - P/N-Well Creation
  * p-well & n-well implantation followed by deep diffusion
      
      ![image](https://user-images.githubusercontent.com/121993909/212548760-ecde54b4-105e-4a15-8cf4-25ac564f580e.png)

  Step 2 - Sallow Trench Isolation
  * Sallow trench isolation (STI) electrically isolates one region/transistor from another.
  
      ![image](https://user-images.githubusercontent.com/121993909/212548976-afd16819-5a27-44bd-a74c-5e38ee1f8d1f.png)

  Step 3 - Treshold Shift and Anti-Punch through Implants
  * P threshold implant is used to make the NMOS harder to invert and the PMOS easier resulting in threshold voltages balance around zero volts.
  * An implant can be applied to create a higher-doped region beneath the channels to prevent the punch-through from the drain depletion region extending to source depletion region.
   
      ![image](https://user-images.githubusercontent.com/121993909/212549362-eee30c73-bcf0-473c-a7be-82a7ef1905fa.png)

  Step 4 - Thin Oxide and Polysilicon Gate
  * A thin oxide is deposited followed by polysilicon. These layers are removed where they are not wanted.
  
      ![image](https://user-images.githubusercontent.com/121993909/212549498-392c9bac-716d-4d5e-9778-5aba08f2448e.png)

  Step 5 - Lightly Doped Source and Drain
  * A lightly-doped implant is used to create a lightly-doped source and drain next to the channel of the MOSFETs.
  
      ![image](https://user-images.githubusercontent.com/121993909/212549609-38b3032b-745c-4b8c-86f5-963f4a3c68e9.png)

  Step 6 - Sidewall Spacer
  * Deposit sidewall spacer to prevent the part of the source and drain next to the channel from being heavily doped.
  
      ![image](https://user-images.githubusercontent.com/121993909/212549850-90165d87-5757-40e0-b253-53bb977cb73f.png)

  Step 7 - Implantation of Heavily Doped Source and Drain
  * Heavily dope provides the complete sources and drains
  * Also forms an ohmic contact into the well and substrate.
  
      ![image](https://user-images.githubusercontent.com/121993909/212550051-16b57aa9-7ca5-45d4-bda0-a2c6bd5c26b9.png)

  Step 8 - Siliciding (Silicide and Polycide)
  * This step is to reduce the resistance of the bulks diffusion and polysilicon and forms an ohmic contact with material on which it is deposited.
  
      ![image](https://user-images.githubusercontent.com/121993909/212550227-b0c6a480-ac0f-4c2e-836a-a673cebed36d.png)

  Step 9 - Intermediate Oxide Layer
  * An oxide layer is used to cover the transistors and to planarize the surface.
  
      ![image](https://user-images.githubusercontent.com/121993909/212550368-8ca050a4-08df-419b-83dd-fb7d95ce9668.png)

  Step 10 - First Level Metal
  * Tungsten(W) plug are built through the lower intermidiate oxide layer to provide contact between the devices, wells, and substrate to the first-level metal.
  
      ![image](https://user-images.githubusercontent.com/121993909/212550556-1c104747-6092-4f0b-80fa-7ec01ad77d74.png)
  
  Step 11 - Second Level Metal
  * Repeat the previos step to built second & third-level metal.
  
      ![image](https://user-images.githubusercontent.com/121993909/212550674-d0710046-b499-4f82-befc-767d6b529423.png)

</details>

<details><summary> Diferences between Submicron, DSM, UDSM </summary>
  
  ![image](https://user-images.githubusercontent.com/121993909/212551124-7807e4aa-a4e8-49ec-8e5c-a2a3d9408756.png)

</details>

<details><summary> Assignment </summary>
  
  #### DSM & UDSM Technology
  
  + **[DSM & UDSM Technology](https://drive.google.com/file/d/1lK00QBuAJEa49GRfjY-l8cqMtb9dnChr/view?usp=share_link)**
  
</details>

## Day 4
## Theory - Metal-Oxide-Semiconductor (MOS) Structure
<details><summary> Ideal MOS Structure </summary>
  
  #### Metal-Oxide-Semiconductor (MOS)
  * MOS is simply a capacitor built up by a dielectric layer which sandwiched between the metal and the semiconductor layers.
  
    ![image](https://user-images.githubusercontent.com/121993909/212722507-90274be6-b040-4b30-b055-a5751f8bd84b.png)
  
  * MOS do not have current-voltage relationship, but only with capacitance-voltage relationship.
  * At V(gate) > V(threshold), the capacitance is inverse proportional to frequency.
  
    ![image](https://user-images.githubusercontent.com/121993909/212722648-e4ecf3c4-96f5-4f62-bd63-9ec7d23b2fcf.png)
  
  #### Ideal MOS Junction / Capacitor
  * Ideal characteristics
  
    ![image](https://user-images.githubusercontent.com/121993909/212722726-53937105-0b60-4ea5-a0b7-77534974ce33.png)

  #### Three deference MOS operation modes
  1. Acumulation Mode, V < 0
  * When negative voltage applied at the Gate terminal, causing the accumulation of majority carrier (holes) at the interface.
  * Charge at the surface is directly proportional to the negative voltage.
                             
    ![image](https://user-images.githubusercontent.com/121993909/212722239-0ed35f62-d7f3-482a-912e-8fee7857def9.png)
                       
  2. Depletion Mode, 0 < V < Vt
  * Semiconductor surface form a depletion region, the surface charge is negative and gradually increase with inrease of voltage.
  * The voltage at which the surface carrier concentration is exactly equal to bulk carrier conentration is called weak inversion/treshold voltage.
  * This is the inversion point where the depletion mode ends and strong inversion started.
    
    ![image](https://user-images.githubusercontent.com/121993909/212726227-4817718c-21da-4a22-8453-6a0dcf92bca1.png)

  3. Strong Inversion Mode, V >= Vt
  * At threshold voltage, a channel form at the surface of the semiconductor due to inversion charge.
  * Before threshold voltage, the charge comes from negatively charged ionized acceptor.
  * After threshold voltage, more charge comes from the electrons rather than depleting the holes.
  
    ![image](https://user-images.githubusercontent.com/121993909/212727418-e3a47033-3150-49ad-8395-c1721130b1da.png)

  
</details>

<details><summary> Non-Ideal MOS Structure </summary>
  
  #### Non-Ideal MOS Structure Effects
  1. Effect of fixed charge, Qf
  * Fixed charge is the charge has no movement and will not vary with voltage.
  * Applying negative voltage at the gate, the surface charge at the silicon will be zero (flat-band condition).
  
  2. Effect of metal-semiconductor work function different, ɸms
  * Both metal and semicondutor are made with different type of materials, hence they have different work function.
  * Work function means the minimum energy required to remove an eletron from a solid material surface into a point in the vacuum.
  * To remove the electrons from the P-substrate semicondutor surface, we have to provide a negative voltage to the gate.
  
</details>

<details><summary> Assignment </summary>
  
  #### Metal-Oxide-Semiconductor (MOS) Structure
  
  + **[Metal-Oxide-Semiconductor Structure](https://drive.google.com/file/d/1J2FEnV60zrcpUA5jj_AzRldoylW38_u3/view?usp=share_link)**
  
</details>

## Day 5
## Theory - Metal-Oxide-Semiconductor Feild-Effect Transistor (MOSFET)
<details><summary> MOSFET Stucture </summary>

  ### Metal-Oxide-Semiconductor Field-Effect Transistor (MOSFET)
  
  #### MOSFET Structure
  * MOSFET Structure in Top, Front and 3D views.
  
    ![image](https://user-images.githubusercontent.com/121993909/213101900-6c56f7dc-0082-47d7-a194-a522a1e7b419.png)
       
</details>
  
<details><summary> MOSFET Operation </summary>
  
  ### MOSFET Operation
  
  Case 1: Cutoff
  * Gate voltage lower than threshold voltage, Vgs < Vt.
  * No channel form between source and drain.
  
  Case 2: Linear Operation
  * Gate voltage slightly above threshold voltage, Vgs - Vt >= Vds.
  * N-channel start to form between drain and source.
  * Current flow from drain to source, Id.
  * Id increase linearly with Vgs increase.
  
  Case 3: Saturation Mode
  * Gate voltage much more higher than threshold voltage, Vgs - Vt < Vds
  * At saturation point, the curent from drain to source is saturated even the Vds keep increasing.
  
    ![image](https://user-images.githubusercontent.com/121993909/213120881-7a9710b9-abce-46b5-b15e-eeec7c1e04b6.png)

</details>
  
<details><summary> Id to Vgs Characteristics </summary>
  
  #### NMOS Id-Vgs Charateristics
  
  ![image](https://user-images.githubusercontent.com/121993909/213132077-307de05e-e434-4a1d-b77c-41c252c19efd.png)
  
  #### PMOS Id-Vgs Characteristics
  
  ![image](https://user-images.githubusercontent.com/121993909/213131904-79bbb255-5d76-4fd6-8781-6adabc4ce913.png)

  #### Relationship of Id-Vgs
  
  ![image](https://user-images.githubusercontent.com/121993909/213133854-236c86a2-975d-4ca8-8d18-90aad7266d2b.png)
  
</details>
  
<details><summary> Id-Vds Characteristics </summary>
  
  #### Relationship of Id-Vds
  
  ![image](https://user-images.githubusercontent.com/121993909/213139307-abac3c6f-c242-4a3d-a4ac-4d45da8b1462.png)
  
</details>
  
<details><summary> Channel Length Modulation (Punch-Through Effect) </summary>
  
  #### Channel Length Modulation and Punch-Through Effect

  * In real MOSFET, when Vds keep increasing, the depletion region at drain terminal will extended towards the source terminal.
  * This causing the channel length decreases, and Id increase with Vds increases.
  * An extreme case of channel length modulation is called punch-through where the channel length reduce to zero.
  * Punch-through causing rapidly increase in current, Id with inreasing in drain-source voltage, Vds.
  
    ![image](https://user-images.githubusercontent.com/121993909/213145906-2b773870-acf5-4e9a-be11-c9f0ba8a4733.png)

  * The chart below represent the characteristics of the channel length modulation.
  * When the Vds is higher than Vgs - Vt, the drain current (Id) no longer saturated. And the current is inreasing with the Vds instead.
  
    ![image](https://user-images.githubusercontent.com/121993909/213148857-31cb0ed6-c2c2-4035-86e3-53aa636d51a6.png)
  
</details>

## Day 6
## Theory - MOSFET Intrinsic Capacitances
<details><summary> MOSFET Intrinsic Capacitance </summary>
  
  #### Cutoff Region Intrinsic Capacitance
  
  * Cgso: gate-source overlap capacitance
  * Cgdo: gate-drain overlap capacitance
  * Cgso = Cgdo = Cox * W * Ld
  * Cdb: drain-bulk reverse bias junction capacitance
  * Csb: source-bulk reverse bias junction capacitance
  * Cgb: gate-bulk oxide capacitance (High value)
  * No channel capacitance
  
    ![image](https://user-images.githubusercontent.com/121993909/215365536-971f5765-784b-4cc1-a81e-8bf1c6bd2824.png)

  #### Linear Region Intrinsic Capacitance
  
  * Cgso: gate-source overlap capacitance
  * Cgdo: gate-drain overlap capacitance
  * Cgso = Cgdo = Cox * W * Ld
  * Cdb: drain-bulk reverse bias junction capacitance
  * Csb: source-bulk reverse bias junction capacitance
  * Cgdch: gate-channel oxide at drain side
  * Cgsch: gate-channel oxide at source side
  * Cgsch = Cgdch = 1/2(Cox * W * Leff)
  * Cch-b: channel-bulk capacitance
  
    ![image](https://user-images.githubusercontent.com/121993909/215365600-c3d51b90-16fa-4aba-9299-fecce7332ed4.png)

  #### Saturation Region Intrinsic Capacitance
  
  * Cgso: gate-source overlap capacitance
  * Cgdo: gate-drain overlap capacitance
  * Cgso = Cgdo = Cox * W * Ld
  * Cdb: drain-bulk reverse bias junction capacitance
  * Csb: source-bulk reverse bias junction capacitance
  * Cgsch: gate-channel oxide capacitance at source side
  * Cgsch = 2/3(Cox * W * Leff)
  * Cch-b: channel-bulk capacitance
    
    ![image](https://user-images.githubusercontent.com/121993909/215365654-be687b0e-0851-4cb6-becc-a7c5ba1a5665.png)

</details>

<details><summary> Assignment </summary>
  
  #### MOSFET with Capacitor
  
  + **[MOSFET with Capacitor](https://drive.google.com/file/d/17AOIVM4ptb-3r6g5jI1kalYb9TSbbGbs/view?usp=sharing)**
  
</details>

## Day 7
## Theory - CMOS Inverter
<details><summary> CMOS Inverter - Static Characteristics </summary>
  
  #### Properties CMOS Inverter from Switched Level view
  
  * Rail-to-rail swing: results in high noise margin
  * Logic level independent of device size
  * Low output impedance and less sensitive to noise
  * Extremely high input impedance
  * No direct path between supply and ground, static power ~ 0W.
  
    ![image](https://user-images.githubusercontent.com/121993909/216751015-ff55e564-f24f-4d65-8235-c4102d101884.png)

  #### CMOS Inverter Operation Region
  
  * CMOS Operation Characteristics
  
    ![image](https://user-images.githubusercontent.com/121993909/216752588-4c29e119-eb4d-47c3-adfc-4cff2787c901.png)

  #### MOSFET Strength Variation
  
  * CMOS Strength Analysis 
  
    ![image](https://user-images.githubusercontent.com/121993909/216752618-1ddd0e5c-b28a-4ca2-91ee-e9feeb9dda82.png)

  * Strong : 
    * increased width
    * less impedance
    * lower threshold voltage
    * less slope
  
  * Weak : 
    * decreased width
    * more impedance
    * higher threshold voltage
    * more slope
  
  #### Noise Margin
  
  * Inverter Noise Margin
    * Noise margin is the amount of noise that could be added to a worst-case output such that the signal can still be interpreted as a valid input.
    * How much noise the circuit can tolerate? So, the output voltage can get the correct logic.
  
    !![image](https://user-images.githubusercontent.com/121993909/216757940-cddd8baf-85e8-4ddf-a773-84edf4b08d77.png)
                         
</details>
  
<details><summary> CMOS Inverter - Dynamic Behavior </summary>
  
  #### CMOS Inverter Dynamic Behavior
  * High performance CMOS circuit should have less propagation delay, less rise and fall time.
  * Propagation delay of the CMOS inverter is determined by the time it takes to charge and discharge the load capacitance Cload through the P/N MOS transistors respectively.
  * If Cload increases:
    * Propagation delay (PD) increases
    * Output rise time (Trise) increases
    * Output fall time (Tfall) increases
  * Keeping load capacitance as low as possible can achieve a high performance CMOS circuits.
  
  
  #### Major Components of Load Capacitance
  * Intrinsic Capacitance
    * Cdbp, Cdbn : drain-buld capacitances
    * Cgdp, Cgdn : gate-drain overlap capacitance
  
  * Wiring Capacitance
    * Cw : Interconnect wiring capacitance
  
  * Fanout Capacitance
    * Cgsp, Cgsn : source-bulk reverse bias junction capacitance
  
  * Cload = Cint + Cwiring + Cfanout
  
    ![image](https://user-images.githubusercontent.com/121993909/216758976-dded7d1b-90db-4850-b077-7a1f828bcb06.png)
  
  
  #### Rise Time
  * The time required for the output voltage to rise from 10% to 90% of the supply voltage
    ![image](https://user-images.githubusercontent.com/121993909/216759087-edfd78ce-9714-4df8-bbed-88887ccf2d9e.png)

  
  #### Fall Time
  * The time required for the output voltage to fall from 90% to 10% of the supply voltage
    ![image](https://user-images.githubusercontent.com/121993909/216759092-597205cc-62a1-488d-aa5a-3f096dcbc06b.png)
  
  
  #### Propagation Delay (Tp)
  * Input to output delay during the signal transition at 50%.
  
    ![image](https://user-images.githubusercontent.com/121993909/216759324-b4da0b91-b53e-41b8-a01a-a82d9d4af27e.png)
  
  * Delay calculation
    * Tp = 0.69 * Cload * [(Rp + Rn) / 2]
  
      ![image](https://user-images.githubusercontent.com/121993909/216759447-87d226ee-8390-4dbf-98ba-0030f7d4f614.png)
  
  #### Ways to Minimized Propagation Delay
  1. Reduce Load Capacitance, Cload
  2. Increase the W/L ratio of transistors
  3. Increase Vdd
  
</details>

<details><summary> CMOS Inverter - Power Consumption </summary>
  
  #### Dynamic power dissipation due to charge/discharging of capacitance
  * Each time load capacitance get charged through PMOS, its voltage rise from 0 to VDD.
  * Due to this, certain amount of energy is drawn from the power supply.
  * Part of this energy dissipated on the PMOS device while the remainder stored in the load capacitor.
  * During the high-to-low transition, this capacitor is disharged, and the stored energy is dissipated in the NMOS device.
  * The values of the Energy Evdd taken from the supply during the transition is:
     ###### Evdd = Cload * VDD * VDD
  * Energy stored on the capacitor at the end of the transition:
     ###### Ec = (Cload * VDD * VDD) / 2
  * Only half of the energy supplied by the power source is stored on Cload. The other half has been dissipated in the PMOS transistor.
  * If the gate is switched on and off F(0-1) times per second, the power consumption equals:
     ###### Pdyn = Cload * VDD * VDD * F(0-1)
  
  
  #### Dissipation due to Direct Path Current
  * Energy consume per switching period:
     ###### Edp = VDD * Ipeak * Tsc
  * The average power consumption:
     ###### Pdp = Csc * VDD * VDD * F
  
    ![image](https://user-images.githubusercontent.com/121993909/216771484-f002010a-37ef-45dd-9168-261337331d61.png)

  
  #### Static Power Consumption
  * The static or steady state power dissipation of a circuit is expressed as:
     ###### Pstat = Istat * VDD
  * Ideally, Istat = 0 as the PMOS and NMOS device are never on simultaneously in the steady state operation.
  * But a leakage current flowing through the reverse biased diode junctions of the transistors located between source and drain and the substrate.
  * In general the leakage currents are very small and can be ignored. However the junction currents are caused by thermally generated carriers.
  * Sub-threshold Current: Drain-to-source current even when Vgs is smaller than the threshold voltage.
  
    ![image](https://user-images.githubusercontent.com/121993909/216771852-636dc284-b965-4f9e-b1d3-544dd5b8641c.png)
  
</details>

<details><summary> Assignment </summary>
  
  #### CMOS Inverter Simulation
  
  + **[CMOS inverter simulation](https://drive.google.com/file/d/1ILohBzicfGhWwGKnwLMhAIV9BYxlcPxh/view?usp=sharing)**
  
</details>
 
## Day 8
## Theory - MOSFET Parameter Extraction, Scaling, Short Channel Effects & PVT Variations
<details><summary> MOSFET Parameter Extraction </summary>
  
  #### Lerge Signal Model Parameters
  * MOSFET Level 1 Model Parameters:
    * Vt0       : Zero body biased threshold voltage
    * γ (GAMMA) : Body bias parameter
    * λ (LAMBDA): Channel length modulation parameter
    * Kn (KN)   : Tranconductance parameter
    * ϕ𝑓 (PHI)  : Surface Potential
  
  #### Calculation of Vt0 - Zero body biased threshold voltage
  * 𝐼𝐷(𝑆𝑎𝑡) = 𝑘𝑛/2 . (𝑉𝐺𝑆 − 𝑉𝑇)2 . (1 + λ𝑉𝐷𝑆)
  * 𝐼𝐷(𝑆𝑎𝑡) = 𝑘𝑛/2 . (𝑉𝐺𝑆 − 𝑉𝑇)2
  * sqrt(𝐼𝐷) = sqrt(𝑘𝑛/2) . (𝑉𝐺𝑆 − 𝑉𝑇)
  
    ![image](https://user-images.githubusercontent.com/121993909/217268659-9deed400-a6ca-46c7-bed6-e5d7e67879a9.png)
  
  #### Calculation of Gamma - Body bias parameter
  * γ = [(𝑉𝑇 * 𝑉𝑆𝐵) − 𝑉𝑇0] / [sqrt(|2ϕ𝐹| + 𝑉𝑆𝐵) − sqrt(|2ϕ𝐹|)]
  
    ![image](https://user-images.githubusercontent.com/121993909/217270392-5eb7cecd-9ba6-4754-a181-bc3f924e28c2.png)
  
  #### Calculation of Lambda - Channel length modulation parameter
  * 𝐼𝐷2 / 𝐼𝐷1 = (1 + λ𝑉𝐷𝑆2) / (1 + λ𝑉𝐷𝑆1)
  
    ![image](https://user-images.githubusercontent.com/121993909/217271922-086f2b1a-1e7b-4b14-9379-be2f4db84295.png)

</details>

<details><summary> MOSFET Scaling </summary>
  
  #### MOSFET Scaling
  * As transistors get smaller, their power density stays constants, so that the power use stays in proportion with area; both voltage and current scale down with length.
  * Reduction of the size (dimension of the MOSFET) commonly reffered to as scaling.
  * There are two basic types of size-reduction strategies:
    * Full Scaling (Constatnt-field scaling)
      - This scaling option attampts to preserve the magnitude of internal electric fields in the MOSFET, while the dimensions are scaled down by a factor of S.
      - The charge densities must be increased by a factor of S in order to maintain the feild conditions.
        
        ![image](https://user-images.githubusercontent.com/121993909/217484893-50fcd726-8cad-4139-aa18-330355b16bb3.png)

        ![image](https://user-images.githubusercontent.com/121993909/217484952-6b223ac1-85ed-49ef-9e4d-81c397f4a2a0.png)

    * Constant Voltage Scaling
      - In constant-voltage scaling, all dimensions of the MOSFET are reduced by a factor of S, as in full scaling. The power supply voltage and the terminal voltages remain unchanged.
      - The doping desities must be increased by a factor of S*S (squared) in order to preserve the charge-field relations.
  
        ![image](https://user-images.githubusercontent.com/121993909/217486587-c43f9b55-ef64-43e1-9767-a0b15f746301.png)

        ![image](https://user-images.githubusercontent.com/121993909/217486659-5fe96421-002a-43a4-81ba-547eb8e562c0.png)

  #### Summary of MOSFET Scaling
  * Constant Voltage Scaling may be preffered over Full Scaling in many practical cases because of the external voltage-level constrains.
  * It must be regcognized, however, that constant-voltage scaling increases the drain current density and the power density by a factor of S*S*S (cubed).
  * This large increase in current and power densities may eventually cause serious reliability problems for the scaled transistor, such as electromigration, hot-carrier degradation, oxide breakdown, and electrical over-stress.
  
</details>

<details><summary> Short Channel Effects </summary>
  
  #### Short Channel Effect
  * A MOSFET device is considered to be short when the channel length is the same order of magnitude as the depletion-layer widths (𝑥𝑑𝐷 ,
𝑥𝑑𝑆) of the source and drain junction.
  * Alternatively, a MOSFET can be defined as a short-channel device if the effective channel length 𝐿𝑒𝑓𝑓 is approximately equal to the source and drain junction depth 𝑥𝑗.
  * As the channel length L is reduced to increase both the operation speed and the number of components per chip, the so-called short-channel effect arise.
  
    ![image](https://user-images.githubusercontent.com/121993909/217550870-9ecd5600-70e7-4c42-b59b-bb0b6a2621c4.png)

  * The short channel effects are attributed to 2 physical phenomena:
    * the limitation imposed on electron drift characteristics in the channel
    * the modification of the threshold voltage due to the shortening channel length
  
  * In particular seven different short channel effects can be distinguished
    * drain-induced barrier lowering and punch through
    * mobility degradation or surface scattering
    * velocity saturation
    * impact ionization
    * hot electrons
    * sub-threshold conduction
    * Vt roll-off
  
  #### Drain Induced Barrier Lowering (DIBL)
  * In small-geometry MOSFETs, the potential barrier is controlled by both the gate-to-source voltage Vgs and the drain-to-source voltage Vds.
  * If the drain voltage is increased, the potential barrier in the channel decreases, leading to drain-incuded barrier lowering.
  * The reduction of the potential barrier eventually allows electrons flow between the source and drain, even if the gate-to-source voltage is lower than the threshold voltage.
  * The channel current that flows under this condition, Vgs < Vt0 is called the sub-threshold current.
                                                                   
    ![image](https://user-images.githubusercontent.com/121993909/217555288-78db669a-b40e-4286-85fa-0c60160b292d.png)

  #### Mobility Degradation
  * As channel length becomes smaller due to the lateral extension of the depletion layer into the channel region, the longitudinal electric feild component 𝐸𝑦 increases, and the surface mobility µ becomes field-dependent.
  * Since the carrier tranport in a MOSFET is confined within the narrow inversion layer, and the surface scattering (that is the collisions suffered by the electrons that are accelerated toward the interfaced by 𝐸𝑥) causes reduction of the mobility.
  * The electrons move with great difficulty parallel to the interface, so that the average surface mobility, even for small values of 𝐸𝑦, is about half as much as that of the bulk mobility.
                                                                  
    ![image](https://user-images.githubusercontent.com/121993909/217560206-e083282a-8801-41b8-a050-0d22bbe9ecc6.png)

  #### Velocity Saturation
  * At low 𝐸𝑦, the electron drift velocity 𝑣𝑑𝑒 in the channel varies linearly with the electric field intensity. However, as 𝐸𝑦 increases above 10^4 V/cm, the drift velocity tends to increase more slowly and approaches a saturation value of 𝑣𝑑𝑒𝑠𝑎𝑡 = 10^7 cm/s around 𝐸𝑦 = 10^5 V/cm at 300K.
  * The performance of the short-channel devices is also affected by the velocity saturation, which reduces the tranconductance in the saturation mode.
  * The drain current is limited by velocity saturation instead of pinch off. This occurs in short channel devices when the dimensions are scale without lowering the bias voltage.
  * The critical voltage 𝑉𝑐 is the drain-to-source voltage at which the critical electric field is reached 𝑉𝑐 = 𝐸𝑐 . 𝐿.
                                                                  
    ![image](https://user-images.githubusercontent.com/121993909/217563482-0ded5bae-3ab3-4d0d-bdf6-cfd7b69352a0.png)

  #### Impact Ionization
  * Electron-hole pair generated due to high longitudinal electric field by impact ionization.
  * Holes swept into bulk
  * Potential drop by hole current create a bulk-to-source forward bias
  * Additional electron injection and carrier flow into drain.
                                                                  
    ![image](https://user-images.githubusercontent.com/121993909/217735899-f58d9b52-0c62-47df-ba98-8946525e6918.png)

  #### Hot Carrier
  * Another problem related to high electric fields is caused by so-called hot electrons.
  * This high energy can accumulate with time and degrade the device performance by increasing Vt and affect adversely.
                                                                  
    ![image](https://user-images.githubusercontent.com/121993909/217736710-cb2c112c-e8c1-4bf6-bce7-c39b3e226da6.png)

  #### Sub-threshold Conduction
  * When the gate voltage is high, the transistor is strongly ON. When the gate voltage falls below Vt, the exponential decline in current appears as a straight line on the logarithmic scale.
  * This regime of Vgs < Vt is called weak inversion.
  * The sub-threshold leakage current increases significantly with Vds because of drain-induced barrier lowering.
  * There is a lower limit on Ids set by drain junction leakage that is exacerbated by the negative gate voltage.
  
    ![image](https://user-images.githubusercontent.com/121993909/217739476-e51fea7b-96a2-471e-8614-afa2d0fd8d9b.png)

</details>

<details><summary> Process, Voltage and Temperature (PVT) Variations </summary>
  
  #### Process Variation
  1. Variation in the process parameters:
  
    * Impurity concentration densities
    * Oxide thicknesses
    * Diffusion depth
  
  * These are caused by non-uniform conditinos during the deposition and/or the diffusion of the impurities.
  * This introduces the variation of the sheet resistances and threshold voltages of transistor.
  
  2. Variation in the dimensions:
  
    * Width and length variation of MOS Transistors, resistors and capacitors
    * Mismatches of emitter area in Bipolar devices.
  
  * These are caused by limited resolution of photolithographic process.
  * This changes this device performance in the circuit.
  
    ![image](https://user-images.githubusercontent.com/121993909/217742200-07079848-7111-4f98-ab8f-b79440ad5524.png)

  * 5 process corners
    * TT : NMOS and PMOS Typical
    * SS : NMOS and PMOS Slow
    * FF : NMOS and PMOS Fast
    * SF : NMOS Slow & PMOS Fast
    * FS : NMOS Fast & PMOS Slow
  
      ![image](https://user-images.githubusercontent.com/121993909/217742873-f6744a1c-e062-43c3-9fcc-8dd01be993dd.png)
  
  #### Voltage Variation
  * There are multiple reasons for voltage variation
    * IR drop caused by the current flow over the power grid network.
    * Supply noise caused by parasitic inductance in combination with resistance and capacitance. When the current is flowing through parasitic inductance,L it will cause the voltage bounce.
  
  #### Temperature Variation
  * Two fundamental parameters, carrier mobility µ and threshold voltage Vt varies with temperature.
  * Carrier mobility decrease with temperature 
      
      µ(𝑇) = µ(𝑇𝑟)(𝑇-𝑇𝑟)−𝑘µ
  
    Where T is the absolute temperature, 𝑇𝑟 is the room temperature and 𝑘µ is the fitting parameter with a typical value of 1.5
  
  * The magnitude of threshold voltage decreases nearly with the temperature and may be approximated by
  
      𝑉t(𝑇) = 𝑉t(𝑇𝑟) − 𝑘𝑣𝑡 (𝑇 − 𝑇𝑟)
  
      Where, 𝑘𝑣𝑡 is typically about 1-2 mV/K
  
  * 𝐼𝑜𝑛 at high Vdd decreases with temperature, sub-threshold leakage increases exponentially with temperature, BTBT increases slowly with temperature and gate leakage is almost independent with temperature.
  
      ![image](https://user-images.githubusercontent.com/121993909/217745777-9d17a2bf-6366-4dd1-8b8d-8e09747c6d7f.png)
  
</details>

<details><summary> Assignment - Parameter Extraction </summary>
  
  #### Parameter Extraction
  
  + **[Parameter Extraction](https://drive.google.com/file/d/1PkOz9F3cL_7TrYK7Q5wVCSJ0WdTkHfX4/view?usp=share_link)**

</details>

## Day 9
## Theory - Combinational Digital Logic Circuits
<details><summary> Complementary Logic Circuits </summary>
  
  #### Structure of Complementary Logic Circuit
  * Combination of two networks called pull-up network, PUN and pull-down network, PDN.
  * PUN provides connection between the output and the VDD when the output of the logic gate is meant to be HIGH.
  * PDN provides connection between the output and the GND when the output of the logic gate is meant to be LOW.
  * PUN is constructed using PMOS devices, and PDN is constructed using NMOS devices.
  
    ![image](https://user-images.githubusercontent.com/121993909/219842951-a902e0f5-4f9a-4339-8876-c5d3a32d752c.png)
  
  #### 2-Inputs NAND Gate
  * 2x pull-up parallel PMOS transistors and 2x pull-down series NMOS transistors
  * As PDN NMOS are connected in series, when output changed from 1->0, the high-to-low transition time, Tphl = 0.69 * 2Rn * Cload.
  * For PUN PMOS ccoeencted in parallel, there are two cases:
    * Both input = 0: Tplh = 0.69 * 1/2Rp * Cload
    * Either one input = 0: Tplh = 0.69 * Rp * Cload
  * To balance the charge/discharge time of both PUN and PDN, we need to increase the NMOS size to reduce the resistance and discharge time when output transition from high-to-low.
  
    ![image](https://user-images.githubusercontent.com/121993909/219843551-2692889d-4edd-49e2-9388-493d9f97d51d.png)

  #### 2-Inputs NOR Gate
  * 2x pull-up series PMOS transistors and 2x pull-down parallel NMOS transistors
  * As PUN PMOS are connected in series, when output changed from 0->1, the low-to-highh transition time, Tplh = 0.69 * 2Rp * Cload.
  * For PDN NMOS ccoeencted in parallel, there are two cases:
    * Both input = 1: Tphl = 0.69 * 1/2Rn * Cload
    * Either one input = 1: Tphl = 0.69 * Rn * Cload
  * To balance the charge/discharge time of both PUN and PDN, we need to increase the PMOS size to reduce the resistance and charge time when output transition from low-to-high.
  
    ![image](https://user-images.githubusercontent.com/121993909/219843714-a945170a-0ae6-4706-9dda-6636fc067eb5.png)

<details>

<details><summary> Assignment - Combinational Logic Circuits Simulation </summary>
  
  #### Combinational Logic Circuits Simulation
  
  + **[Combinational Logic Circuits Simulation]()**
  
</details>
