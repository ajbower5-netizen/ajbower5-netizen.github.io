---
title: Component Selection Example
---

## Examples

### Style 1

> This is the example found in the assignment, uses more html

*Table 1: Example component selection*

**Butten**

| **Solution**                                                                                                                                                                                      | **Pros**                                                                                                                                    | **Cons**                                                                                            |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| <img width="640" height="640" alt="image" src="https://github.com/user-attachments/assets/6fba08c0-3eb7-4721-9348-0563ebb3f782" /> <br>Option 1.<br> 30-17 RED<br>$20.35/each <br>\* [Link to product](https://www.digikey.com/en/products/detail/grayhill-inc/30-17-RED/2417137)                 | \* Inexpensive[^1]<br>\* Compatible with PSoC<br>\* Meets surface mount constraint of project                                               | \* Requires external components and support circuitry for interface<br>\* Needs special PCB layout. |
| <img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/114883a0-3d63-4ed4-8a9c-e11d4d61e3cd" />
)<br>\* Option 2. <br>\* MAVS22A02FE3JR0V <br>\* $15.59/each <br>\* [Link to product](https://www.digikey.com/en/products/detail/knitter-switch/MAVS22A02FE3JR0V/22607972) | \* Outputs a square wave <br>\* Stable over operating temperature <br> \* Direct interface with PSoC (no external circuitry required) range | * More expensive <br>\* Slow shipping speed                                                         |
| <img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/fcf6c5a5-26fa-4330-80e9-230cb6796490" />
)<br>\* Option 3. <br>\* 3432 <br>\* $2.50/each <br>\* [Link to product](http://www.digikey.com/product-detail/en/636L3I001M84320/CTX936TR-ND/2292940) | \* Outputs a square wave <br>\* Stable over operating temperature <br> \* Direct interface with PSoC (no external circuitry required) range | * More expensive <br>\* Slow shipping speed                                                         |

**Choice:** Option 2: CTX936TR-ND surface mount oscillator

**Rationale:** A clock oscillator is easier to work with because it requires no external circuitry in order to interface with the PSoC. This is particularly important because we are not sure of the electrical characteristics of the PCB, which could affect the oscillation of a crystal. While the shipping speed is slow, according to the website if we order this week it will arrive within 3 weeks.


*Table 2: Example component selection*

**Servo Motor**

| **Solution**                                                                                                                                                                                      | **Pros**                                                                                                                                    | **Cons**                                                                                            |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| <img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/cb60fa34-97cd-4d9c-8cc0-0bfdb8fa9212" /> <br>Option 1.<br> CN0023<br>$20.35/each <br>\* [Link to product]([http://www.digikey.com/product-detail/en/636L3I001M84320/CTX936TR-ND/2292940](https://www.digikey.com/en/products/detail/grayhill-inc/30-17-RED/2417137))                 | \* Inexpensive[^1]<br>\* Compatible with PSoC<br>\* Meets surface mount constraint of project                                               | \* Requires external components and support circuitry for interface<br>\* Needs special PCB layout. |
| <img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/894c576a-9cb1-45b8-8450-41293f764665" />
<br>\* Option 2. <br>\* 900-00005 <br>\* $17.95/each <br>\* [Link to product](http://www.digikey.com/product-detail/en/636L3I001M84320/CTX936TR-ND/2292940) | \* Outputs a square wave <br>\* Stable over operating temperature <br> \* Direct interface with PSoC (no external circuitry required) range | * More expensive <br>\* Slow shipping speed                                                         |
| <img width="688" height="675" alt="image" src="https://github.com/user-attachments/assets/f5dadd0a-bc71-47dd-8579-ce37357b730f" />
<br>\* Option 3. <br>\* Deegoo-FPV MG995 Metal Gear Digital Servos, 2-Pack <br>\* $13.98 for 2 <br>\* [Link to product](https://www.amazon.com/dp/B0D7M3BBL2?lv=shuf&crid=3Q0BAZ9VMEE7Y&keywords=servo%2Bmotor&sprefix=servo%2Bmotor%2Caps%2C192&th=1&dib_tag=se&dib=eyJ2IjoiMSJ9.Vd0le04U5HEn6F5FTOqf3NZUio8AlbPOcNYl6K9qjZCFdjZ-86Uf_VUW2kQvW5lEkKBASMPt48w_hvz_ZKEd0b98d_bJPX3GE_DsjerZF52DEv42lapNeH8mmhSib2Oun_1prqIwyNgb75FJjebvuonsNj9Gfu3RtY_B5E8jXg5t2j1dD_BfRmutLHijj1Ay-uPGGKrLCrts0llxFLMgQ7Ec_W-iaFDOt_WikPXdNw5h_ALm_L1ybSQhKAFjqpMsuUl1EJtG8wOjO0M0__76OLKVLd8cosWYgi4FyujYN8A.0kKpV2PRGojCPBZDg21vC8NbbwmfUIvxmfVHn4JixOU&qid=1792618809&sr=8-9&channelId=500&ref_=sr_1_9&plpRedirect=mhFallback) | \* Outputs a square wave <br>\* Stable over operating temperature <br> \* Direct interface with PSoC (no external circuitry required) range | * More expensive <br>\* Slow shipping speed                                                         |

**Choice:** Option 2: CTX936TR-ND surface mount oscillator

**Rationale:** A clock oscillator is easier to work with because it requires no external circuitry in order to interface with the PSoC. This is particularly important because we are not sure of the electrical characteristics of the PCB, which could affect the oscillation of a crystal. While the shipping speed is slow, according to the website if we order this week it will arrive within 3 weeks.


*Table 3: Example component selection*

**H Bridge**

| **Solution**                                                                                                                                                                                      | **Pros**                                                                                                                                    | **Cons**                                                                                            |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| <img width="640" height="640" alt="image" src="https://github.com/user-attachments/assets/6fba08c0-3eb7-4721-9348-0563ebb3f782" /> <br>Option 1.<br> 30-17 RED<br>$11.38/each <br>\* [Link to product](https://www.digikey.com/en/products/detail/sunfounder/CN0023/18668611)                 | \* Inexpensive[^1]<br>\* Compatible with PSoC<br>\* Meets surface mount constraint of project                                               | \* Requires external components and support circuitry for interface<br>\* Needs special PCB layout. |
| <img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/60d128ba-52ab-4a7d-ba5b-09bc7d829a5b" />
<br>\* Option 2. <br>\* 900-00005 <br>\* $17.95/each <br>\* [Link to product](http://www.digikey.com/product-detail/en/636L3I001M84320/CTX936TR-ND/2292940) | \* Outputs a square wave <br>\* Stable over operating temperature <br> \* Direct interface with PSoC (no external circuitry required) range | * More expensive <br>\* Slow shipping speed                                                         |
| ![](image3.png)<br>\* Option 3. <br>\* CTX936TR-ND surface mount oscillator <br>\* $1/each <br>\* [Link to product](http://www.digikey.com/product-detail/en/636L3I001M84320/CTX936TR-ND/2292940) | \* Outputs a square wave <br>\* Stable over operating temperature <br> \* Direct interface with PSoC (no external circuitry required) range | * More expensive <br>\* Slow shipping speed                                                         |

**Choice:** Option 2: CTX936TR-ND surface mount oscillator

**Rationale:** A clock oscillator is easier to work with because it requires no external circuitry in order to interface with the PSoC. This is particularly important because we are not sure of the electrical characteristics of the PCB, which could affect the oscillation of a crystal. While the shipping speed is slow, according to the website if we order this week it will arrive within 3 weeks.


*Table 4: Example component selection*

**DC Motor**

| **Solution**                                                                                                                                                                                      | **Pros**                                                                                                                                    | **Cons**                                                                                            |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| <img width="640" height="640" alt="image" src="https://github.com/user-attachments/assets/6fba08c0-3eb7-4721-9348-0563ebb3f782" /> <br>Option 1.<br> 30-17 RED<br>$20.35/each <br>\* [Link to product]([http://www.digikey.com/product-detail/en/636L3I001M84320/CTX936TR-ND/2292940](https://www.digikey.com/en/products/detail/grayhill-inc/30-17-RED/2417137))                 | \* Inexpensive[^1]<br>\* Compatible with PSoC<br>\* Meets surface mount constraint of project                                               | \* Requires external components and support circuitry for interface<br>\* Needs special PCB layout. |
| ![](image3.png)<br>\* Option 2. <br>\* CTX936TR-ND surface mount oscillator <br>\* $1/each <br>\* [Link to product](http://www.digikey.com/product-detail/en/636L3I001M84320/CTX936TR-ND/2292940) | \* Outputs a square wave <br>\* Stable over operating temperature <br> \* Direct interface with PSoC (no external circuitry required) range | * More expensive <br>\* Slow shipping speed                                                         |
| ![](image3.png)<br>\* Option 3. <br>\* CTX936TR-ND surface mount oscillator <br>\* $1/each <br>\* [Link to product](http://www.digikey.com/product-detail/en/636L3I001M84320/CTX936TR-ND/2292940) | \* Outputs a square wave <br>\* Stable over operating temperature <br> \* Direct interface with PSoC (no external circuitry required) range | * More expensive <br>\* Slow shipping speed                                                         |

**Choice:** Option 2: CTX936TR-ND surface mount oscillator

**Rationale:** A clock oscillator is easier to work with because it requires no external circuitry in order to interface with the PSoC. This is particularly important because we are not sure of the electrical characteristics of the PCB, which could affect the oscillation of a crystal. While the shipping speed is slow, according to the website if we order this week it will arrive within 3 weeks.



### Style 2

> Also acceptable, more markdown friendly

**External Clock Module**

1. XC1259TR-ND surface mount crystal

    ![](image1.png)

    * $1/each
    * [link to product](http://www.digikey.com/product-detail/en/ECS-40.3-S-5PX-TR/XC1259TR-ND/827366)

    | Pros                                      | Cons                                                             |
    | ----------------------------------------- | ---------------------------------------------------------------- |
    | Inexpensive                               | Requires external components and support circuitry for interface |
    | Compatible with PSoC                      | Needs special PCB layout.                                        |
    | Meets surface mount constraint of project |

1. CTX936TR-ND surface mount oscillator

    ![](image3.png)

    * $1/each
    * [Link to product](http://www.digikey.com/product-detail/en/636L3I001M84320/CTX936TR-ND/2292940)

    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    | Outputs a square wave                                             | More expensive      |
    | Stable over operating temperature                                 | Slow shipping speed |
    | Direct interface with PSoC (no external circuitry required) range |

**Choice:** Option 2: CTX936TR-ND surface mount oscillator

**Rationale:** A clock oscillator is easier to work with because it requires no external circuitry in order to interface with the PSoC. This is particularly important because we are not sure of the electrical characteristics of the PCB, which could affect the oscillation of a crystal. While the shipping speed is slow, according to the website if we order this week it will arrive within 3 weeks.
