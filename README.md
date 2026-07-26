# Hydrogen Production Process Simulation using DWSIM

A process simulation of **Hydrogen Production from Natural Gas** developed using **DWSIM**, demonstrating the complete process flow from feed preparation to hydrogen purification. The project models major unit operations involved in industrial hydrogen production, including steam methane reforming and gas separation.

---

## 📌 Project Overview

Hydrogen is an essential feedstock for petroleum refineries, ammonia production, methanol synthesis, and emerging fuel cell technologies. This project simulates an industrial hydrogen production process using **DWSIM**, an open-source chemical process simulator.

The simulation includes feed compression, steam generation, chemical conversion, cooling, and gas separation to produce hydrogen while tracking material and energy balances throughout the process.

---

## 🎯 Objectives

- Simulate hydrogen production using DWSIM.
- Perform mass and energy balance calculations.
- Model major chemical engineering unit operations.
- Analyze hydrogen yield and process performance.
- Understand industrial hydrogen production workflows.

---

## ⚙️ Process Description

The simulation follows the typical hydrogen production route:

1. Methane feed preparation
2. Water pumping and steam generation
3. Mixing of methane and steam
4. Feed compression
5. Steam Methane Reforming (SMR)
6. Product cooling
7. Water-Gas Shift (WGS) reaction
8. Final cooling
9. Hydrogen purification using component separation

---

## 🏭 Unit Operations Included

| Unit Operation | Function |
|---------------|----------|
| Pump | Pressurizes water feed |
| Compressor | Compresses methane feed |
| Heater | Generates steam and heats process streams |
| Mixer | Combines methane and steam |
| Conversion Reactor | Performs chemical reactions |
| Cooler | Reduces product temperature |
| Component Separator | Separates hydrogen from product gases |
| Material Streams | Transfers process fluids |
| Energy Streams | Tracks heat and work requirements |

---

## ⚗️ Chemical Reactions

### Steam Methane Reforming (SMR)

\[
CH_4 + H_2O \rightarrow CO + 3H_2
\]

This highly endothermic reaction produces synthesis gas (syngas).

---

### Water-Gas Shift Reaction (WGS)

\[
CO + H_2O \rightarrow CO_2 + H_2
\]

The shift reactor converts carbon monoxide into additional hydrogen.

---

## 🧪 Components Used

- Hydrogen (H₂)
- Methane (CH₄)
- Water (H₂O)
- Carbon Monoxide (CO)
- Carbon Dioxide (CO₂)
- Nitrogen (N₂)

---

## 📊 Simulation Features

- Steady-state process simulation
- Material balance calculations
- Energy balance calculations
- Process stream analysis
- Reactor modeling
- Hydrogen separation
- Heat duty calculations
- Compressor work estimation

---

## 📈 Expected Outputs

The simulation provides:

- Hydrogen production rate
- Stream compositions
- Temperature profiles
- Pressure profiles
- Reactor conversion
- Heat duties
- Utility requirements
- Hydrogen purity
- Methane conversion

---

## 🛠️ Software Used

- **DWSIM** (Chemical Process Simulator)

---

## 📂 Repository Structure

```
Hydrogen-Production-DWSIM/
│
├── Hydrogen production.dwxmz
├── README.md
└── images/
    └── flowsheet.png   (optional)
```

---

## 🚀 How to Run

1. Install the latest version of **DWSIM**.
2. Clone this repository:

```bash
git clone https://github.com/yourusername/Hydrogen-Production-DWSIM.git
```

3. Open the `.dwxmz` file in DWSIM.
4. Run the simulation.
5. Analyze the process streams and unit operation results.

---

## 📚 Learning Outcomes

Through this project, you can understand:

- Industrial hydrogen production
- Steam methane reforming
- Water-gas shift reaction
- Process simulation using DWSIM
- Material and energy balance
- Unit operation modeling
- Chemical process optimization

---

## 🔮 Future Improvements

- Pressure Swing Adsorption (PSA) for higher hydrogen purity
- Heat exchanger network optimization
- Process economic analysis
- Carbon capture integration
- Sensitivity analysis
- Process optimization using Aspen Plus

---

## 👨‍💻 Author

**Anurag Prasad**

B.Tech, Chemical & Biochemical Engineering  
Indian Institute of Technology Patna

---

## 📜 License

This project is intended for educational and academic purposes.
