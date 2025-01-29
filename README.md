**Powerplanning in ICC2**

At top-level, power is delivered in the order below:
Pads --> Rings --> Stripes --> Rails


**Some common steps of powerplanning:**
1. Create power ports/pads
2. Create power/ground nets
3. Connect ports/pads to power/ground nets
4. Create rails
5. Define pg mesh for M2 to M7 layers (only core region)
6. Define different pg strategy 
7. There are some checks after creating pg mesh 
8. Define master rule for via creation(via creation was disabled during pg mesh creation)
9. Create pg vias


**Why PG regions are created? **
PG regions are created to control the structure of powerplan at different portion's of the design. Because different areas of the design requires different PG structure.
