# Lighting Calculator

[![Status](https://img.shields.io/badge/status-work%20in%20progress-orange)](https://github.com/modernplace/lighting-calculator)
[![License: GPL v3](https://img.shields.io/badge/license-GPLv3-blue.svg)](./LICENSE)
[![HTML](https://img.shields.io/badge/frontend-HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS](https://img.shields.io/badge/styles-CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/logic-JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Modern Place](https://img.shields.io/badge/by-Modern%20Place-111111)](https://www.modern.place/)
[![Calculator](https://img.shields.io/badge/live-LED%20Lighting%20Calculator-2ea44f)](https://www.modern.place/led-lighting-calculator/)

A lightweight lighting calculator by [Modern Place](https://www.modern.place/) for estimating **light spread in metres** based on **beam angle** and **mounting height / distance from light**.

This project is part of Modern Place’s broader effort to make lighting specification simpler through practical digital tools, better UX, and forward-looking AI-enhanced customer education.

---

## Table of Contents

- [Overview](#overview)
- [Feature Highlights](#feature-highlights)
- [Live Links](#live-links)
- [How It Works](#how-it-works)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Use Cases](#use-cases)
- [Roadmap](#roadmap)
- [About Modern Place](#about-modern-place)
- [License](#license)

---

## Overview

The **Lighting Calculator** is a simple front-end tool designed to help users quickly estimate the spread of light from a fixture using two core inputs:

- **Beam Angle**
- **Height of Room or Distance From Light**

The output is a calculated **Light Spread** value in **metres**, making the tool useful for lighting planning, product education, and early-stage fixture selection.

---

## Feature Highlights

- Clean, lightweight front-end calculator
- Fast beam-angle based light spread estimation
- Designed for practical real-world lighting decisions
- Simple UI for customer-facing or embedded use
- Localization-ready structure via `i18n`
- Easy foundation for future lighting tools and calculators
- Built to support a modern lighting brand with digital-first, AI-forward content strategy

---

## Live Links

- **Customer-facing calculator:** [Modern Place LED Lighting Calculator](https://www.modern.place/led-lighting-calculator/)
- **Brand website:** [Modern Place](https://www.modern.place/)

---

## How It Works

The calculator uses predefined beam-angle spread multipliers to estimate how wide a light beam will project over a given distance.

### Inputs

- **Beam Angle**  
  Adjustable from **10° to 160°**
- **Height of Room or Distance From Light**  
  Entered in **metres**

### Output

- **Light Spread**  
  Returned in **metres**

### Example

A wider beam angle produces a broader light spread at the same mounting height, while a narrower beam angle creates a tighter, more focused projection.

This makes the calculator helpful for:

- Choosing the right beam angle
- Planning fixture placement
- Comparing lighting effects before installation
- Supporting product education and online conversion

---

## Project Structure

```text
lighting-calculator/
├── .vscode/
├── api/
│   ├── light.js
│   ├── main.min.js
│   └── style.light.css
├── i18n/
│   └── localisation.js
├── templates/
│   └── layout/
│       └── css/
├── lightingcalculator.html
└── LICENSE
