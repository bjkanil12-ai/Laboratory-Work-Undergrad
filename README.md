# Laboratory-Work-Undergrad
This repository serves as a portfolio demonstrating practical scientific/engineering skills and technical communication abilities developed throughout my degree.

---

## `1A Lab Report.pdf`: Boiling Heat Transfer

### What This File Shows
This report investigates the performance of a boiling heat transfer rig using Pentafluorobutane. It aims to identify the different boiling regimes (convection, nucleate, transition, and film boiling) by analysing the relationship between the applied heat flux and the resulting temperature difference between the heating element and the fluid (excess temperature, $\Delta T_{excess}$).

### Methodology
Experimental data for power input (W) and temperatures ($T_{Surface}$, $T_{fluid}$) were collected. The power was converted to heat flux ($Q"$) by dividing by the heater's surface area. This was plotted against $\Delta T_{excess}$ to create a "boiling curve." The Zuber equation was used to calculate the theoretical critical heat flux ($U_{max}$) for comparison.

### Key Findings
* **Experimental Critical Heat Flux ($Q"_{crit}$):** 236 kW/m²
* **Theoretical Critical Heat Flux ($U_{max}$):** 243.3 kW/m²
* **Heater Efficiency ($\eta$):** 97.0%
* **Maximum Heat Transfer Coefficient ($h_{max}$):** 7.92 kW/(m²K)
* The boiling curve clearly showed the different regimes, with heat flux peaking at the critical point before entering the transition and film boiling phases.

---

## `1B lab report.pdf`: Distillation Column Optimisationn

### What This File Shows
This experiment analyses the performance of an 8-plate distillation column used to separate an ethanol-water mixture. The goal was to determine the number of theoretical plates ($n_{min}$) and the overall column efficiency ($E$) at different boil-up rates (controlled by heater power from 0.6 kW to 1.0 kW).

### Methodology
First, a calibration curve correlating refractive index to ethanol mole percentage (mol%) was created. Samples were taken from the reboiler (bottoms) and distillate (top) at different power settings. The Antoine equation and Raoult's Law were used to calculate the average relative volatility ($\alpha_{avg}$) for each condition. Finally, the Fenske equation was used to calculate the minimum theoretical plates ($n_{min}$), and the efficiency was found using $E = n_{min} / 8$.

### Key Findings
* The column efficiency was found to be very low across all power settings, indicating significant deviation from ideal operation.
* **At 0.6 kW:** $n_{min}$ = 0.443, resulting in the highest efficiency of **5.53%**.
* **At 1.0 kW:** $n_{min}$ = 0.066, resulting in the lowest efficiency of **0.82%**.
* The results showed that increasing the boil-up rate (power) decreased the separation efficiency of this specific column.

---

## `2B - Heat Pump (2).pdf`: Heat Pump (Thermoelectric Device)

### What This File Shows
This report analyses the performance of a thermoelectric (Peltier) device, which uses the Peltier effect to function as a solid-state heat pump and refrigeration system. The experiment measures the Coefficient of Performance (COP) for both heating and cooling modes.

### Methodology
The device was run at three different Peltier currents (3 Amps, 4 Amps, 5 Amps). For each current, the heater power ($Q_{in}$), cooling power ($Q_{out}$), and work input ($W_{cycle}$) were recorded across a range of temperature differences ($\Delta T$) between the hot and cold reservoirs. The $COP_{HP}$ (Heat Pump) and $COP_{Ref}$ (Refrigeration) were calculated and plotted against $\Delta T$.

### Key Findings
* For all currents, the $COP$ (both heating and refrigeration) decreases as the temperature difference ($\Delta T$) increases.
* **Heat Pump ($COP_{HP}$):** The 4 Amp setting was most efficient at low $\Delta T$ (peaking at $COP_{HP} \approx 1.95$), but the 5 Amp setting became more efficient at $\Delta T > 16 K$.
* **Refrigeration ($COP_{Ref}$):** The 3 Amp setting was the most efficient across the entire $\Delta T$ range, showing a near-linear decrease from a $COP_{Ref}$ of ~1.85 at $\Delta T = 0 K$.
* The heater power ($Q_h$) showed a strong negative linear correlation with $\Delta T$ for all currents.

---

## `3A Lab Report.pdf`: Fluidised Bed

### What This File Shows
This experiment characterises the properties of an air-fluidised bed containing Aluminium Oxide powder. The primary objectives were to determine the superficial velocity at minimum fluidisation ($u_{mf}$), the voidage at minimum fluidisation ($\epsilon_{mf}$), and the average particle diameter ($d_p$). The experiment also investigated the heat transfer coefficient ($h$) within the bed.

### Methodology
Air was passed through the bed at increasing and decreasing flow rates, and the pressure drop ($\Delta P$) was recorded. A log-log plot of $\Delta P$ vs. superficial velocity ($u$) was created to graphically determine the $u_{mf}$. This value was then used with the Carman-Kozeny and Ergun equations to solve for $\epsilon_{mf}$ and $d_p$. Heat transfer was measured by recording temperatures at different flow rates and heater voltages (15V and 25V).

### Key Findings
* **Superficial Velocity at Minimum Fluidization ($u_{mf}$):** **0.129 m/s**
* **Voidage at Minimum Fluidization ($\epsilon_{mf}$):** **0.468**
* **Average Particle Diameter ($d_p$):** **297 $\mu$m**
* The calculated particle size corresponds to **Grade 56 Aluminium Oxide**.
* The heat transfer coefficient ($h$) increased with both superficial velocity and heater power, with values ranging from **63.0 W/m²K** (at 15V, low flow) to **237.6 W/m²K** (at 25V, high flow).
