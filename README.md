# Intel Ckt Training
This repo will be used of deposition of training documentations.

## Table of contents
+ **[ Day 1 - Overview of VLSI Design ](https://github.com/xinniteo/Intel_CKT_Training#day-1)**
  <details><summary> Theory </summary>
  
  [Theory - Overview of VLSI Design](https://github.com/xinniteo/Intel_CKT_Training/blob/main/README.md#theory---overview-of-vlsi-design)
 
## Day 1
## Theory - Overview of VLSI Design
<details><summary> Chip-to-wafer </summary>

### Packaged Chip

### **Chip-to-wafer**
#### Packaged Chip
* Die is the central part of chip
* Package is to connect the silicon die of the IC to the circuit board
* Evolution and different types of Packaged Chip, example:
* Evolution and different types of Packaged Chip, example:  
![00](https://user-images.githubusercontent.com/121996016/211218848-2589ce0a-61c6-4ebd-b7cd-7b9c6188c8c0.jpg)

  * SIP (System In Package): 
@@ -34,15 +35,16 @@
    * able to provide more interconnection pins than can be put on a dual in-line or flat package
    * ![04](https://user-images.githubusercontent.com/121996016/211218901-8f07ae64-801f-49c2-ad1b-ecc0a2f56317.png)

### Die and Wafer
#### Die and Wafer
* generally die size is (1x1)mm or (1x2)mm
* wafer diameter is around 12 inch ~ 300 mm
* a single wafer contains 10’s of thousands die  

   </details>

<details><summary> Overview of Inside the Die </summary>


### **Overview of Inside the Die**
![05](https://user-images.githubusercontent.com/121996016/211218924-a502ad35-b6fd-48c1-9249-28adcab0167b.png)
* Analog and RF
  * Made by custom VLSI flow
@@ -56,16 +58,19 @@
   </details>

<details><summary> Moore’s Law </summary>

### **Moore’s Law**

* Moore’s Law defines the number of transistors in a dense integrated circuit doubles every 2 years
  * Every two years, the feature size is reduced by 1/sqrt(2) times

   </details>

<details><summary> VLSI Design Methodology </summary>

### Despite of different design style, proper functionality, low cost and timely execution is much more important
### Two types of VLSI Design Styles:

### **VLSI Design Methodology**
#### Despite of different design style, proper functionality, low cost and timely execution is much more important
#### Two types of VLSI Design Styles:
1. Field programming gate array (FPGA)
* faster prototyping and cost-effective, basically use in prototyping and testing
* typically consists of input/output buffers, array of configurable logic blocks (CLBs) and programmable interconnect
@@ -100,8 +105,9 @@
   </details>

<details><summary> VLSI Design Quality </summary>

### Importamt criteria to measure the design quality:

### **VLSI Design Quality**
#### Importamt criteria to measure the design quality:
1. Testability  
  * Generation of good test vector
  * Availability of good test fixture at speed
@@ -123,7 +129,8 @@
   </details>

<details><summary> Package Technology </summary>


### **Package Technology**
* VLSI chips can fail if various packaging constraints and parasitic are not included in the design phase 
* number of ground planes, power planes and the bonding pads greatly affect the behaviours of on-chip power and ground buses
* length of bonding wire and lead length of the package can create serious issue  
@@ -138,7 +145,8 @@
     </details>

<details><summary> CAD Tools </summary>


### **CAD Tools**
* essential for timely development of integrated circuits
* CAD technology for VLSI chip design can be categorized into the following areas:
    * High-level synthesis
