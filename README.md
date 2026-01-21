# RC Low-Pass Filter Analysis & Simulation

![MATLAB](https://img.shields.io/badge/MATLAB-R2023b-orange.svg)
![License](https://img.shields.io/badge/License-MIT-blue.svg)
![Status](https://img.shields.io/badge/Status-Maintained-green.svg)

## 📝 Overview

This repository contains a comprehensive analysis and simulation of a **First-Order RC Low-Pass Filter** implemented in MATLAB. The project includes scripts for calculating the transfer function, generating Bode plots (magnitude and phase), and analyzing the time-domain response to various input signals (step, sine, square wave).

The codebase is accompanied by technical documentation and fully commented scripts for educational and analytical purposes.

## 📚 Theory & Concept

An RC Low-Pass Filter is a circuit composed of a resistor ($R$) and a capacitor ($C$) that passes signals with a frequency lower than a selected cut-off frequency ($f_c$) and attenuates signals with frequencies higher than the cut-off frequency.

### Key Formulas

**1. Cut-off Frequency ($f_c$):**
$$f_c = \frac{1}{2\pi R C}$$

**2. Transfer Function ($H(s)$):**
$$H(s) = \frac{V_{out}(s)}{V_{in}(s)} = \frac{1}{1 + RCs}$$

Where:
* **R** = Resistance ($\Omega$)
* **C** = Capacitance ($F$)

