# Intel Ckt Training
This repo will be used of deposition of training documentations.

## Table of contents
+ **[ Day 1 - Overview of VLSI Design ](https://github.com/TengBoonHuei/intel_ckt_training#day-1)**
  <details><summary> Theory </summary>
  
  [Theory - Overview of VLSI Design](https://github.com/TengBoonHuei/intel_ckt_training/blob/main/README.md#theory---overview-of-vlsi-design)
 
## Day 1
## Theory - Overview of VLSI Design

<details><summary> Chip-to-wafer </summary>
  
### Packaged Chip

### **Chip-to-wafer**
#### Packaged Chip
* Die is placed at the center of the chip (package).
* Wire bonding is the method of interconnecting the die to the external world.
* The package's function is to connect the silicon die to the circuit board.
* The package are encapsulated, so to protect the die inside the chip.
* Evolution and different types of Packaged Chip, example:
  ![image](https://user-images.githubusercontent.com/121993909/211232190-d5a756e7-5c60-453d-aa2a-c1f1d014273c.png)

### Die and Wafer
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

### **Moore’s Law**

* Moore’s Law defines the number of transistors in a dense integrated circuit doubles every 2 years
* Every two years, the feature size is reduced by 1/sqrt(2) times

   </details>

<details><summary> VLSI Design Methodology </summary>

### Critical factors of design execution:
  * functionality, perormance & quality
  * low cost
  * faster time-to-market
  
### Two types of VLSI Design Styles:

### **VLSI Design Methodology**
#### Two types of VLSI Design Styles:
1. Field-Pragrammable Gate Array (FPGA)
  * faster prototyping and cost-effective, basically use in prototyping and testing
  * typically consists of input/output buffers, array of configurable logic blocks (CLBs) and programmable interconnect

2. Application Speciic Intergrated Circuit (ASIC)
  * Permanent circuitry. Once the application specific circuit is taped-out into silicon, it cannot be changed.
  * Higher cost as need to start design from scratch. 
  * More power efficient, power consumption of ASICs can be very minutely controlled and optimized.
   </details>

<details><summary> VLSI Design Quality </summary>

### Importamt criteria to measure the design quality:

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
