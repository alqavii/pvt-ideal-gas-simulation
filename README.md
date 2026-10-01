# Experiment P1: PVT Properties of an Ideal Gas (Simulation)

Virtual laboratory simulation for Experiment P1: PVT Properties of an Ideal Gas (MBCE114 / CMB133), Department of Chemical and Biological Engineering, University of Sheffield.

## Overview

This application simulates the capillary-tube Boyle's law apparatus with a trapped column of air sealed by a mercury plug, connected to a hand vacuum pump with an analog gauge ($\Delta P$).

## Governing Equations

- **Ideal Gas Law:**
  $$PV = nRT \implies Pv_{\text{mol}} = RT$$
- **Absolute Pressure in Closed Capillary (Equation 4):**
  $$P = P_{\text{amb}} + \Delta P + P_{\text{Hg}}$$
- **Mercury Seal Hydrostatic Pressure (Equation 5):**
  $$P_{\text{Hg}} = \rho_{\text{Hg}} \cdot g \cdot h_{\text{Hg}}$$
- **Trapped Gas Volume (Equation 6):**
  $$V = \frac{\pi d^2}{4} h \quad (d = 2.7\text{ mm})$$
- **Boyle's Law (Equation 7):**
  $$PV = c \quad (\text{fixed } T \text{ and } n)$$

## Features

- **Apparatus Controls:** Adjust vacuum hand pump under-pressure ($\Delta P$ from 0 to -400 mbar), squeeze pump lever, and vent valve V1.
- **Thermal Bath Conditions:** Ambient ($20^\circ\text{C}$), Hot Water Bath ($65^\circ\text{C}$), and Ice/Water Bath ($0^\circ\text{C}$).
- **Optical Scale Loupe:** High-magnification reticle to observe the lower mercury meniscus on the capillary millimeter scale.
- **Data Tables:** Tables 1, 2, and 3 matching the lab manual records with 1-click Excel TSV export.
- **Section 5 Results Plot:** Canvas plot of $PV$ vs $P$ across all three temperatures with linear regression ($PV = m \cdot P + c$) to verify zero slope (Boyle's law) and intercept ordering (Charles's law).
