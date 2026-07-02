# Compact-Chevron-Heat-Exchanger
# What is this?
This project is focused on designing and optimizing a highly efficient, cost-effective cross-flow plate heat exchanger. I went with a cross-flow configuration because it offers a great surface-area-to-volume ratio while keeping the overall footprint compact.

# The Design
To kick the convective heat transfer up a notch, I incorporated a chevron groove design into the plates to intentionally induce a turbulent flow regime.

# Simulation & Testing
Once the topology was shared and the distinct hot and cold fluid volumes were isolated, I set up the thermal-hydraulic analysis:
* **Meshing:** Used Hex8 elements for solid computational accuracy.
* **Boundary Conditions:** Hot fluid inlet at 80°C and cold fluid inlet at 30°C.
* **Data Tracking:** Logged the outlet temperatures for every test run to calculate the overall thermal efficiency.

# The Optimization Loop
I didn't just test one setup. I ran an iterative process across different materials (Copper, Aluminum, Stainless Steel) and sizes (8, 10, and 12-plate configurations).

To find the absolute best design, I ran a multi-objective optimization balancing three weighted factors:
* **Thermal Efficiency** (40% weight)
* **Manufacturing Cost** (40% weight)
* **Compactness / Number of Plates** (20% weight)

# The Final Result
The optimization hit a sweet spot with a 10-plate Aluminum chevron-grooved heat exchanger. This final configuration achieved a solid 62% thermal effectiveness while perfectly balancing cost and size constraints.
