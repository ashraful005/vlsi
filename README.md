**Powerplanning in ICC2**

At top-level, power is delivered in the order below:
Pads --> Rings --> Stripes --> Rails

<img width="344" alt="image" src="https://github.com/user-attachments/assets/80570535-5ac2-4ab3-9334-9caa9dae5099" />

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

**Why PG regions are created?**

PG regions are created to control the structure of powerplan at different portion's of the design. Because different areas of the design requires different PG structure.


**Standard Cell Layout:**

<img width="466" alt="image" src="https://github.com/user-attachments/assets/05b9e7c3-33b7-42a3-a008-771fb0f5f779" />

