
# Micro-3d-Printer
* title: "Micro-3d-Printer"
* description: "A user friendly cool stuff"
* Made by : raghib112

Total time: 34 hours 30 mins (Idk how accurate this is probably pretty close tho)

**Micro-3D-Printer** is a compact, budget-friendly 3D printer designed to stay under $300 while maintaining high functionality. It features a filament detection system to automatically pause printing when the filament runs out, ensuring smooth and uninterrupted prints. Built for efficiency and affordability, it’s ideal for makers looking for a reliable and cost-effective 3D printing solution.


### **Goals:**  
- Keep the total cost under **$300** while ensuring quality and reliability.  
- Implement **filament detection** to pause printing when filament runs out.  
- Design a **compact and efficient** 3D printer suitable for small workspaces.  
- Ensure **easy assembly and maintenance** for users.  
- Provide **consistent and high-quality prints** with minimal calibration.  

### **Requirements:**  
- **Frame:** Sturdy and lightweight material (e.g., aluminum structure ).  
- **Axis movement:** Precise stepper motors and smooth linear rails ( X, Y, Z axis ).  
- **Extruder & Hotend:** Reliable direct-drive or Bowden extruder with a standard nozzle.  
- **Filament Sensor:** Detects filament runout and pauses printing.  
- **Heated Bed:** For better adhesion and compatibility with various filaments.  
- **Electronics:** Efficient motherboard, stepper drivers, and power supply.  
- **Firmware:** Open-source firmware with support for advanced features.  
- **User Interface:** Simple and intuitive display for easy operation.

## BOM (Bill Of Materials)

| Working  | on |
|--|--|


## **Day - 1, ( 20/03/25 ) - Planning and breakdown idea**  

⏳ **Time Spent:** 4+ hours  

- Watched multiple YouTube videos on **how 3D printers work** and their components.  
- Read various articles to understand **FDM printing, mechanics, and common issues**.  
- Identified **filament detection** as a key problem to solve.  
- Goal: **Keep cost under $300** while ensuring quality.  
- Planned a **filament sensor** to pause printing when filament runs out.  
- Next: Research detection methods, sketch design, estimate costs.  


## **Day - 2, ( 21/03/25 ) - Findings and gather printer idea from exist one**  
⏳ **Time Spent:** 3+ hours  
- **Researching Existing Printers**: Studied features, components, and designs of popular 3D printers to understand how they operate.
- **Identifying Key Features**: Noted the most important features like print volume, filament types, print quality, and ease of use.
- **Documenting Findings**: Organized your notes on design elements, specifications, and potential improvements based on existing models.
- **Evaluating Technology**: Investigated technologies such as auto bed leveling, filament detection, multi-color printing, etc. And sooooo on...


## **Day - 3, ( 22/03/25 ) - Assembly frame structure**  
⏳ **Time Spent:** 2+ hours  

### Description
- Started to design the main skeleton of the printer. 

### Parts Breakdown

| No. | Part Name                   | Quantity |
|----|------------------------------|---------|
| 1  | 4020 L400 Profile            | 5       |
| 2  | 4020 L400 Profile            | 2       |
| 3  | Joining Plate 90 Degree      | 6       |
| 4  | Cast Corner Bracket          | 2       |
| 5  | T NUT M5 2020S               | 34      |
| 6  | B18.3.4M - 5 x 0.8 x 5 SBHCS | 34      |
| 7  | Filament Supporter           | 1       |



## **Day - 4, ( 23/03/25 ) - z axis assembly**  
⏳ **Time Spent:** 5+ hours  

### Description
- Designing printer Z-axis

### Parts Breakdown ( z-axis left & z-axis right)

| No. | Part Name                          | Quantity |
|----|----------------------------------|---------|
| 1  | stepper_am17hd44 52-02n         | 1 x 2 = 2       |
| 2  | stepper_am shaft                | 1 x 2 = 2       |
| 3  | Montura Motor Z Derecho         | 1 x 2 = 2       |
| 4  | 400 x Ø8 Rod                    | 1 x 2 = 2       |
| 5  | T8 lead screw                   | 1 x 2 = 2       |
| 6  | T8 lead screw nut               | 1 x 2 = 2       |
| 7  | Retenedor Eje Z Derecho         | 1 x 2 = 2       |
| 8  | Ball Bearing 8 x 16 x 5         | 1 x 2 = 2       |
| 9  | LM8UU                           | 2 x 2 = 4       |
| 10 | Flexible Coupling 5mm x 8mm     | 1 x 2 = 2       |
| 11 | Hexagon Nut ISO 4032 - M3 - D - N | 1 x 2 = 2       |
| 12 | DIN 912 M3 x 10 --- 10N         | 1 x 2 = 2       |
| 13 | DIN 912 M3 x 8 --- 8N           | 4 x 2 = 8       |



## **Day - 5, ( 24/03/25 ) - Z-axis limit switch & Y-axis assembly**  
⏳ **Time Spent:** 4+ hours  

### Description
- Firstly i started to design the printer Z-axis and then 
- Design the limit switch here
- After that started to design the Y-axis

### Parts Breakdown ( Z-axis Limit Switch)

| No.| Part Name                       | Quantity|
|----|---------------------------------|---------|
| 1  | Micro Limit Switch              | 1       |
| 2  | Soporte Switch Eje Z            | 1       |
| 3  | DIN 912 M2 x 10 --- 10N         | 2       |
| 4  | T NUT M5 2020S                  | 2       |
| 5  | B18.3.4M - 5 x 0.8 x 5 SBHCS    | 2       |

---
### Parts Breakdown ( Y-axis Assembly)
| No. | Part Name                                              | Quantity |
|----|-----------------------------------------------------|---------|
| 1  | Stepper motor                  | 1       |
| 3  | Perilla Nivelación de Cama Predeterminado    | 4       |
| 4  | M3 X 3-12 mm Length, Brass Knurled Insert_8 mm | 4       |
| 9  | Bearing, GT2 Idler Pulley, Configurable_20T W6 B3 Without T | 1 |
| 10 | Micro Limit Switch                           | 1       |
| 11 | Heatbed 220x220x3mm MK3 Aluminum v1.step_Predeterminado| 1 |
| 12 | SK8 Vertical Rod Support Fastener           | 4       |
| 13 | rod_450 x Ø8                                 | 2       |
| 14 | AM8 - Heat Bed Support - V1.0               | 1       |
| 15 | SCS8UU                                      | 4       |
| 16 | Ajuste vertical cama caliente_Predeterminado| 4       |
| 17 | SPRING                                      | 4       |
| 18 | Montura Motor Y_Predeterminado              | 1       |
| 19 | GT2 Timing Pulley 20 Tooth                  | 1       |
| 20 | Soporte Switch Y_Predeterminado             | 1       |
| 21 | Superficie de Impresión Borosilicato 220x220x3_Predeterminado| 1 |
| 22 | Posicionador superficie de impresión_Predeterminado| 4 |
| 23 | Montura Tensionador Eje Y_Predeterminado    | 1       |
| 24 | Tensionador Eje Y_Predeterminado            | 1       |
| 25 | Retenedor Correa Eje Y_Predeterminado       | 2       |
| 26 | Tapa Retenedor Correa Eje Y_Predeterminado  | 2       |
| 27 | Socket button head cap screw_am_B18.3.4M - 3 x 0.5 x 12 SBHCS --N| 20 |
| 28 | Hex nut style 1 gradeab_din-2P L_Hexagon Nut ISO 4032 - M3 - D - N| 5 |
| 29 | Socket head cap screw_din-2P L_DIN 912 M3 x 8 --- 8N| 4 |
| 30 | Socket head cap screw_din-2P L_DIN 912 M3 x 5 --- 5N| 1 |
| 31 | Socket head cap screw_din-2P L_DIN 912 M3 x 20 --- 20N| 1 |
| 32 | Socket head cap screw_din-2P L_DIN 912 M3 x 25 --- 18N| 1 |
| 33 | Socket csink head cap screw 10642_din-4P Bed_EN ISO 10642 - M3 x 30 - 18N| 4 |
| 34 | Hex nut style 1 gradeab_din-2P L_Hexagon Nut ISO 4032 - M2 - D - N| 2 |
| 35 | Socket head cap screw_din-2P L_DIN 912 M2 x 10 --- 10N| 2 |
| 36 | T NUT M5 2020S                                      | 16      |
| 37 | B18.3.4M - 5 x 0.8 x 5 SBHCS --N                    | 16      |


## **Day - 6, ( 25/03/25 ) - X-axis assembly**  
⏳ **Time Spent:** 3+ hours  

### Description
- Designing printer X-axis 

### Parts Breakdown ( X-axis Assembly)
| No. | Part Name                                        | Quantity |
|----|---------------------------------------------------|---------|
| 1  | Micro Limit Switch                                | 1       |
| 2  | Montura Eje X Izquierdo                           | 1       |
| 3  | stepper Motor                                     | 1       |
| 4  | GT2 Timing Pulley 20 Tooth (2mm x 6mm )           | 1       |
| 5  | 400 x Ø8 Rod                                      | 2       |
| 6  | Montura Eje X Derecho                             | 1       |
| 7  | Tensionador Eje X                                 | 1       |
| 8  | GT2 Idler Pulley, Configurable                    | 1       |
| 9  | LM8UU                                             | 4       |
| 10 | Hexagon Nut ISO 4032 - M3 - D - N                 | 11      |
| 11 | DIN 912 M3 x 30 --- 18N                           | 2       |
| 12 | DIN 912 M3 x 16 --- 16N                           | 9       |
| 13 | DIN 912 M3 x 20 --- 20N                           | 4       |
| 14 | DIN 912 M2 x 12 --- 12N                           | 2       |


## **Day - 7, ( 26/03/25 ) - Feed & Cooling Assembly**  
⏳ **Time Spent:** 4 hours  

### Description
- Here i design the feed and then started to work in the main fun fact so it not miss the filament anymore
-   Added an IR sensor at the filament entry point to detect if the filament is missing.
-   If filament is missing during printing, the sensor triggers:
    -   Automatic pausing of the print
    -   An alert sound.
    -   A popup notification to your phone.


### Parts Breakdown ( Feed Assembly)

| No. | Part Name                                | Quantity |
|-----|------------------------------------------|----------|
| 1   | Stepper Motor                            | 1        |
| 3   | Montura Extrusor                         | 1        |
| 4   | CR10 Extruder by Proma                   | 1        |
| 5   | B18.3.4M - 3 x 0.5 x 12 SBHCS --N        | 3        |
| 6   | T NUT M5 2020S                           | 4        |
| 7   | B18.3.4M - 5 x 0.8 x 5 SBHCS             | 4        |
---
### Parts Breakdown ( Cooling Fan Assembly)

### Description
- Designing cooling fan

| No. | Part Name                                        | Quantity |
|-----|--------------------------------------------------|----------|
| 1   | Radial Cooling Fan 5015 DC12V                    | 1        |
| 2   | E3D V6                                           | 1        |
| 3   | Montura Cabezal de Impresión                     | 1        |
| 4   | Base Cabezal de Impresión                        | 1        |
| 5   | Turbo cooling fan for nozzle cooling             | 1        |
| 6   | 5015 Fan Duct                                    | 1        |
| 7   | Tapa lateral Cabezal de Impresión Izquierda      | 1        |
| 8   | Retenedor Hotend Cabezal de Impresión            | 1        |
| 9   | Hexagon Nut ISO 4032 - M3 - D - N                | 12       |
| 10  | DIN 912 M3 x 30 --- 18N                          | 2        |
| 11  | DIN 912 M3 x 20 --- 20N                          | 5        |
| 12  | DIN 912 M3 x 12 --- 12N                          | 4        |


## **Day - 8, ( 27/03/25 ) - Control Panel, Power and Display**  
⏳ **Time Spent:** 3+ hours  
### Description
- For this i review many power supply for printer
- And which power supply will better for my printer. 
- And all basis thought it may good to go

### Control Panel

| ITEM NO. | PART NUMBER                | DESCRIPTION                   | QTY. |
|----------|----------------------------|-------------------------------|------|
| 1        | M3 X 3-12 mm               | Length, Brass Knurled Insert  | 2    |
| 2        | Montura Placa de Control   | Control Plate Bracket         | 1    |
| 3        | BTT E3 SKR MINI V3.0 PM r2 | Mainboard for 3D Printer      | 1    |
| 4        | Tapa Placa de Control      | Control Plate Cover           | 1    |
| 5        | DIN 912 M3 x 10 --- 10N    | M3 x 10 Screws                | 2    |
| 6        | DIN 912 M3 x 8 --- 8N      | M3 x 8 Screws                 | 4    |

### Display

| ITEM NO. | PART NUMBER                 | DESCRIPTION                | QTY. |
|----------|-----------------------------|--------------------------|------|
| 1        | Montura LCD                 | LCD Display Bracket      | 1    |
| 2        | Creality CR-10S LCD Board   | LCD Display Board        | 1    |
| 3        | DIN 912 M3 x 6 --- 6N       | M3 x 6 Screws            | 4    |
| 4        | T NUT M5 2020S              |                          | 4    |
| 5        | B18.3.4M - 5 x 0.8 x 5 SBHCS|                          | 4    |

### Power Supply Connecting Box

| ITEM NO. | PART NUMBER                        | DESCRIPTION                      | QTY. |
|----------|------------------------------------|----------------------------------|------|
| 1        | Power supply                       | Power Supply Assembly File       | 1    |
| 2        | Montura Fuente de Alimentacion     | Power Supply Bracket             | 1    |
| 3        | DIN 7991 - M3 x 8 --- 4.8N         | M3 x 8 Screws                    | 2    |
| 4        | DIN 912 M3 x 5 --- 5N              | M3 x 5 Screws                    | 3    |
| 5        | T NUT M5 2020S                     |                                  | 3    |
| 6        | B18.3.4M - 5 x 0.8 x 5 SBHCS       |                                  | 3    |


## **Day - 9, ( 28/03/25 ) - Preparing Final BOM**  
⏳ **Time Spent:** 3+ hours  
> This is quite pain to find right goods based on budget and availability.
> I search on Alibaba and Aliexpress
> And got the items also but it will take a bunch of time so decided to make a purchase from local market. 


## **Day - 10, ( 29/03/25 ) - Readme and Reviewing**  
⏳ **Time Spent:** 1+ hours  
- I updated the readme Overall and correct some stuffs   
