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
   
     + ![image](https://user-images.githubusercontent.com/121993909/212549362-eee30c73-bcf0-473c-a7be-82a7ef1905fa.png)

  Step 4 - Thin Oxide and Polysilicon Gate
    * A thin oxide is deposited followed by polysilicon. These layers are removed where they are not wanted.
  
     + ![image](https://user-images.githubusercontent.com/121993909/212549498-392c9bac-716d-4d5e-9778-5aba08f2448e.png)

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
      [image](https://user-images.githubusercontent.com/121993909/212550674-d0710046-b499-4f82-befc-767d6b529423.png)

</details>

<details><summary> Assignment </summary>
  
  #### DSM & UDSM Technology
  
  + **[DSM & UDSM Technology](https://drive.google.com/file/d/1lK00QBuAJEa49GRfjY-l8cqMtb9dnChr/view?usp=share_link)**
  
</details>
