# TU Wien | 307.511-2026S  Aircraft Design 2 | Group 1

## Group Members
- [ ] Diego Medeiros Dalla Costa
- [ ] Nikita Starikov
- [ ] Michael Riedl
- [ ] Matthias Frenzl

## Quicklinks
- [ ] [AD2 - Final Report Group 1 (Overleaf)](https://www.overleaf.com/project/69b1be71f6877b9e88aff68b)
- [ ] [Google Drive](https://drive.google.com/drive/folders/13KR6O2V4UuHsem6PENUwRDxKRzNBrr3V)
- [ ] [TUWEL](https://tuwel.tuwien.ac.at/course/view.php?id=80421)

## Delivery Dates
- [ ] Delivery 1: April 16
- [ ] Delivery 2: May 21
- [ ] Presentation: June 22
- [ ] Final Report: July 9

## [Archive]
- [ ] [AD 1 - Final Report Group 6 (Overleaf)](https://www.overleaf.com/project/6960d3aa7cf8ca69d6b32604)
- [ ] AD 1 - Final Report Group n (Overleaf)

## Deliverables (i.e., Report Content)

#### Overall Guidelines

- Justify all decisions/assumptions made during your design.
- Display your results graphically for easier visualization/comparison between design options.
- Add any detailed calculation steps and/or sections of code to appendices.
- If AI is used during the project, it must be acknowledged and documented which prompts were used and how the answers were critically assessed.

---

> The following list describes the required content. Additional analyses and own initiatives are rewarded according to the grading criteria.
>
> **Attention:** The analyses in this semester only need to be carried out for the most limiting variant, however the limiting version may change depending on which analysis is being made!

####  1. Introduction

Write a small contextualization for the project (what is the objective?) and list the relevant specifications given for the assignment.

####  2. Short Review of Results from Aircraft Design I

Please provide the main results from the previous semester, it should include:

- Design masses: MTOM, OEM and Fuel mass along with preliminary Payload vs. Range diagram,
- $C_L$, $C_D$ and $L/D$ assumptions,
- Final $P/W$ vs. $W/S$ diagram, highlighting the selected values for the baseline and stretch designs,
- LH2 system volumes (and masses if already computed),
- 3-side view of the aircraft configuration.

####  3. Initial Drag Estimation

In this chapter the revision of the parasite drag must be carried out using the three methods described in lecture and available in the handout. Discuss which method better estimates the parasite drag in your opinion and adopt a new value for $C_{D_0}$ based on your new results. How does it compare with your initial guess from ACDI?

Following the determination of the parasite drag, compute the drag polar for cruise, take-off and landing configurations by adding the lift-induced drag and any additional drag due to high-lift devices, landing gear, compressibility, etc.

Determine your $L/D$ ratio for the conditions: Cruise, Take-Off and Landing using a $L/D$ vs. $C_L$ diagram. Do the values match your assumption from ACDI? If there are large discrepancies, verify that the aircraft is able to meet the requirements in the $P/W$ vs. $W/S$ diagram by adjusting it to the new values.

####  4. Design Airspeeds and V-n Diagram

Determine and/or compute the design speeds for the baseline aircraft (provide justifications):

- $V_{MO}$ and $M_{MO}$
- $V_C$ and $M_C$
- $V_D$ and $M_D$

Once the speeds are known, please provide a graph of the design speeds vs. altitude.

The V-n diagram for the following conditions must be reported:

- Maneuver envelope (clean and landing configuration)
- Gust loads at: Sea level, ceiling altitude and altitude where peak loads occur (three different graphs!)

Maneuver and gust envelopes may be shown in parallel or overlapped. Note that in case of LH2 aircraft, the mass variation is small and therefore computations may be carried out in a simplified way based on the MTOM.

####  5. Load & Balance

Calculate the mass of the main components of the aircraft, according to the methods presented in the slides of "Detailed Mass Estimation". Using Torenbeek or geometric information, compute the center of gravity location for each component with respect to a reference point. Note that components may be divided into two main groups:

- Fuselage group
- Wing group

With the known masses and centers of gravity, determine the stability limits for the aircraft on ground and in air:

- Longitudinal stability on ground (rearmost and high CG),
- Minimum and maximum nose gear load,
- Tilting stability on ground (foremost and high CG),
- Neutral point at cruise condition.

Once the limits are known, plot the loading (potato) diagrams for the aircraft for the most critical conditions expected (e.g. Design mission, transfer mission, etc.). It should include at least:

- Pax loading (front and back),
- Cargo loading (front and back),
- Fuel loading.

In case of violation of the limits, the wing positioning may be adjusted.

At the end, add to a table the conditions for the foremost and rearmost CG variation during loading, and their respective positions.

####  6. Lift Distribution and Detailed Drag Estimation

In this section the main objective is to obtain the lift distribution of the wing and calculate a more detailed breakdown of the drag components via XFLR5 and analytical relations.

The wing's lift distribution must be used to estimate the starting location of the stall progression and to verify that the risk of loss of roll control is low.

A $C_L$ vs. $C_D$ polar with the drag build-up is to be presented, it shall include contributions from:

- Wing parasite drag,
- Fuselage,
- HTP and VTP,
- Trim drag,
- Induced drag,
- Nacelles,
- Compressible drag.

Once the aerodynamic polar for the clean aircraft is known, compute the $L/D$ vs. $C_L$ and $L/D$ vs. $M$ polar for different flight altitudes at the initial cruise weight.

####  7. High-Lift Devices

The High-Lift Devices (HLD) must be chosen and sized to meet the specifications made in ACDI for the Take-Off and Landing assessments.

Based on the wing's planform, regions for application of the HLD must be assigned. A flap system (plain, slotted, double slotted or Fowler flap) and a slat system (standard LE slat, Krüger flap, no leading edge device) must be chosen.

Compute the $C_L$ vs. $\alpha$ curves for take-off and landing configurations using the method presented in class, as well as the $C_L$ vs. $C_D$ and $L/D$ vs. $C_L$ polars.

Please summarize in tables the main parameters for the calculations:

- $C_{L_\alpha}$, $\alpha_0$, $C_{L_{max}}$ and $\Delta\alpha_{C_{L_{max}}}$ without HLD
- Surface areas and dimensions: $S_F/S$, $S_S/S$, $c_F/c$, $c_S/c$
- $\Delta C_{L_{max,F}}$ and $\Delta C_{L_{F,\varphi}}$
- $\Delta C_{L_{max,S}}$
- $\Delta C_{D_{flaps}}$ (including sub-components)

The following figures are mandatory (polars for the three configurations in one plot — clean, take-off and landing):

- Wing planform with flaps/slats assignments
- $C_L$ vs. $\alpha$
- $C_L$ vs. $C_D$ (with and w/o LG)
- $L/D$ vs. $C_L$ (with and w/o LG)

Please add a short discussion about the results.

#### 8. PEMFC Ancillary System — Power Requirements

Please include the analyses made to compute the required power for the ancillaries of the PEMFC according to the slides (*2024 01 08 PEMFC Ancillary Power v3*). Explain and justify any assumptions and variables that are specific to the operation of your aircraft.

#### 9. Performance Assessment

This section includes analysis of the performance of your aircraft.

##### Flight Conditions (Handout 1)

- **Level diagrams** for different altitudes starting from sea-level. Conditions:
    - MTOW, max climb ($TR_{throttle} = 0.9$)
    - MTOW, max cruise ($TR_{throttle} = 0.8$)
- **Specific excess thrust (SET) and excess power (SEP)** for climb. Plotted for different altitudes against true airspeed.
- **Optimum airspeeds** (minimum, max SET, max SEP, maximum) to be plotted together with the upper equilibrium airspeed in level flight as a function of altitude ($H$ vs. TAS).
- **Specific air range (SAR) and flight durations (SE)**, using ICA weight. Plotted for different altitudes over true airspeed.
- **Flight envelope** ($H$ vs. TAS) for ICA weight and cruise thrust throttle ratio.

##### Flight Segments (Handout 2)

- Integral climb performance shall be calculated for the fastest climb at ICA.
- Final payload-range diagram based on flight performance results.

####  10. Direct Operating Costs

Present the estimated annual costs to operate your aircraft using the general parameters defined in the lecture slides. Expected diagrams/graphs and tables:

- Payload-Range diagram overlapped with CASK vs. Range. *Tip: use two y-axes.*
- Table listing main categories and respective annual costs, CASK, percentage of total DOC and estimated seat cost (DOC only) + share of engine price to total aircraft price.
- Break-even passenger count assuming a revenue rate of € 0.10/km and operating range margin assuming a 75% load factor.

####  11. Conclusion

Final discussion on your project. What were the lessons learned throughout the course? Which aspect/analysis had most impact on the design? What are the main uncertainties regarding your design? How could your aircraft be improved?
