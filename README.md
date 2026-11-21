# EXPERIMENT NO: 5

| **Name: Sujith S K** | | **Reg. No.: 26013061** | |
|---|---|---|---|
| **Date: 21-11-2026** | | **Batch / Section: 26ODJ150** | |

# ZENER DIODE AS A VOLTAGE REGULATOR

## AIM
To study the operation of a Zener diode as a voltage regulator and observe its line regulation and load regulation characteristics using Proteus simulation.

## APPARATUS REQUIRED

| S. No. | Name of the apparatus | Range / Specification | Quantity |
|---:|---|---|---:|
| 1 | Zener diode | 1N4740A | 1 |
| 2 | Series resistor (R1) | 100 Ω | 1 |
| 3 | Load resistor (R2) | 2 kΩ | 1 |
| 4 | Variable resistor (RV1) | Variable resistance | 1 |
| 5 | DC Battery | DC Voltage Source | 1 |
| 6 | Ammeter | 0–1 A DC | 1 |
| 7 | Voltmeter | 0–20 V DC | 1 |
| 8 | Ground and connecting wires | — | As required |
| 9 | Simulation software | Proteus Design Suite | 1 |

## THEORY

A Zener diode is a semiconductor diode designed to operate in the reverse breakdown region.

When connected in reverse bias, the Zener diode maintains an approximately constant voltage across its terminals, even when the input voltage or load current changes within its operating limits.

It is commonly used as a voltage regulator to maintain a stable output voltage.

### 1. LINE REGULATION

Line regulation is the ability of a voltage regulator to maintain a constant output voltage when the input voltage changes.

In this experiment:
- The load resistance is kept constant.
- The input voltage is varied.
- The output voltage is observed.

### 2. LOAD REGULATION

Load regulation is the ability of a voltage regulator to maintain a constant output voltage when the load resistance changes.

In this experiment:
- The input voltage is kept constant.
- The load resistance is varied.
- The output voltage is observed.

## PRECAUTIONS

1.While doing the experiment, do not exceed the ratings of the Zener diode; this may damage the diode.
2.Connect the voltmeter and ammeter in correct polarities as shown in the circuit diagram.
3.Do not switch ON the power supply unless the circuit connections have been checked as per the circuit diagram.

## PROCEDURE

### LINE REGULATION

1. Open Proteus and create the line regulation circuit.
2. Connect the Zener diode in reverse bias.
3. Connect the series resistor and load resistor.
4. Set the load resistance to 2 kΩ.
5. Apply an input voltage within the verified operating limits of the components.
6. Vary the input voltage in suitable steps.
7. Observe and record the output voltage.
8. Plot the graph between input voltage and output voltage.

### LOAD REGULATION

1. Create the load regulation circuit in Proteus.
2. Connect the Zener diode in reverse bias.
3. Keep the input voltage constant.
4. Vary the load resistance using the variable resistor.
5. Observe and record the output voltage.
6. Plot the graph between load resistance and output voltage.

## CIRCUIT DIAGRAMS

### LINE REGULATION CIRCUIT

<img width="1130" height="720" alt="Line_Reg_Circuit" src="https://github.com/user-attachments/assets/6226cb77-cded-4633-af72-35590e86ec09" />

### LOAD REGULATION CIRCUIT

<img width="1090" height="724" alt="Load_Reg_Circuit" src="https://github.com/user-attachments/assets/a4e451ac-5aef-4282-a17a-471cae04ef68" />

## SIMULATION USING PROTEUS

### LINE REGULATION SIMULATION

<img width="1097" height="721" alt="Line_Reg_1" src="https://github.com/user-attachments/assets/85581d2c-6fe4-4966-8874-eb351ef01804" />



<img width="1111" height="708" alt="Line_Reg_2" src="https://github.com/user-attachments/assets/c413ca53-6d1d-4b68-8980-1b274342daba" />

### LOAD REGULATION SIMULATION

<img width="1091" height="727" alt="Load_Reg_1" src="https://github.com/user-attachments/assets/f55e4864-a9e0-4d86-9f29-5206bd91a0c4" />



<img width="1103" height="698" alt="Load_Reg_2" src="https://github.com/user-attachments/assets/f63fbeb0-2883-4295-81bc-df2633ee15ea" />

## TABULATION

### 1. LINE REGULATION (RL = 2000 Ω, constant)

| S.No | Input Voltage (V) | Output Voltage (V) |
|---|---:|---:|
| 1 | 30 | 10.10 |
| 2 | 40 | 10.12 |
| 3 | 50 | 10.14 |
| 4 | 60 | 10.16 |
| 5 | 70 | 10.18 |
| 6 | 80 | 10.20 |
| 7 | 90 | 10.22 |
| 8 | 100 | 10.24 |
| 9 | 110 | 10.26 |
| 10 | 120 | 10.28 |

### 2. LOAD REGULATION (Vin = 30 V, constant)

| S.No | Load Resistance (Ω) | Output Voltage (V) |
|---|---:|---:|
| 1 | 100 | 9.80 |
| 2 | 200 | 9.85 |
| 3 | 300 | 9.89 |
| 4 | 400 | 9.92 |
| 5 | 500 | 9.95 |
| 6 | 600 | 9.98 |
| 7 | 700 | 10.00 |
| 8 | 800 | 10.03 |
| 9 | 900 | 10.05 |
| 10 | 1000 | 10.08 |

## FORMULAE

### LINE REGULATION

% Line Regulation = Change in Output Voltage / Change in Input Voltage

% Line regulation = (ΔVo / ΔVin) × 100

### LOAD REGULATION

% Load Regulation = (No-load Voltage - Full-load Voltage) / Full-load Voltage) × 100

% Load regulation = (VNL − VFL) / VFL × 100

## SERIES RESISTANCE

Series resistance, Rs = (Vin − Vz) / (Iz + IL)

## MODEL GRAPHS

### LINE REGULATION GRAPH (Vin vs Vo)

<img width="1600" height="1000" alt="line_regulation_graph" src="https://github.com/user-attachments/assets/17dc8555-b812-4d98-ab91-bcde273c26d6" />

### LOAD REGULATION GRAPH (RL vs Vo)

<img width="1600" height="1000" alt="load_regulation_graph" src="https://github.com/user-attachments/assets/9d741239-4ea9-4bea-8c89-a9884d2f8995" />

## RESULT

Thus, the Zener diode was used as a voltage regulator, and its line regulation and load regulation characteristics were obtained.
# EXPERIMENT NO: 5

# ZENER DIODE AS A VOLTAGE REGULATOR

## AIM
To study the operation of a Zener diode as a voltage regulator and observe its line regulation and load regulation characteristics using Proteus simulation.

## APPARATUS REQUIRED

| S. No. | Name of the apparatus | Range / Specification | Quantity |
|---:|---|---|---:|
| 1 | Zener diode | 1N4740A | 1 |
| 2 | Series resistor (R1) | 100 Ω | 1 |
| 3 | Load resistor (R2) | 2 kΩ | 1 |
| 4 | Variable resistor (RV1) | Variable resistance | 1 |
| 5 | DC Battery | DC Voltage Source | 1 |
| 6 | Ammeter | 0–1 A DC | 1 |
| 7 | Voltmeter | 0–20 V DC | 1 |
| 8 | Ground and connecting wires | — | As required |
| 9 | Simulation software | Proteus Design Suite | 1 |

## THEORY

A Zener diode is a semiconductor diode designed to operate in the reverse breakdown region.

When connected in reverse bias, the Zener diode maintains an approximately constant voltage across its terminals, even when the input voltage or load current changes within its operating limits.

It is commonly used as a voltage regulator to maintain a stable output voltage.

### 1. LINE REGULATION

Line regulation is the ability of a voltage regulator to maintain a constant output voltage when the input voltage changes.

In this experiment:
- The load resistance is kept constant.
- The input voltage is varied.
- The output voltage is observed.

### 2. LOAD REGULATION

Load regulation is the ability of a voltage regulator to maintain a constant output voltage when the load resistance changes.

In this experiment:
- The input voltage is kept constant.
- The load resistance is varied.
- The output voltage is observed.

## PRECAUTIONS

1.While doing the experiment, do not exceed the ratings of the Zener diode; this may damage the diode.
2.Connect the voltmeter and ammeter in correct polarities as shown in the circuit diagram.
3.Do not switch ON the power supply unless the circuit connections have been checked as per the circuit diagram.

## PROCEDURE

### LINE REGULATION

1. Open Proteus and create the line regulation circuit.
2. Connect the Zener diode in reverse bias.
3. Connect the series resistor and load resistor.
4. Set the load resistance to 2 kΩ.
5. Apply an input voltage within the verified operating limits of the components.
6. Vary the input voltage in suitable steps.
7. Observe and record the output voltage.
8. Plot the graph between input voltage and output voltage.

### LOAD REGULATION

1. Create the load regulation circuit in Proteus.
2. Connect the Zener diode in reverse bias.
3. Keep the input voltage constant.
4. Vary the load resistance using the variable resistor.
5. Observe and record the output voltage.
6. Plot the graph between load resistance and output voltage.

## CIRCUIT DIAGRAMS

### LINE REGULATION CIRCUIT

<img width="1130" height="720" alt="Line_Reg_Circuit" src="https://github.com/user-attachments/assets/6226cb77-cded-4633-af72-35590e86ec09" />

### LOAD REGULATION CIRCUIT

<img width="1090" height="724" alt="Load_Reg_Circuit" src="https://github.com/user-attachments/assets/a4e451ac-5aef-4282-a17a-471cae04ef68" />

## SIMULATION USING PROTEUS

### LINE REGULATION SIMULATION

<img width="1097" height="721" alt="Line_Reg_1" src="https://github.com/user-attachments/assets/85581d2c-6fe4-4966-8874-eb351ef01804" />



<img width="1111" height="708" alt="Line_Reg_2" src="https://github.com/user-attachments/assets/c413ca53-6d1d-4b68-8980-1b274342daba" />

### LOAD REGULATION SIMULATION

<img width="1091" height="727" alt="Load_Reg_1" src="https://github.com/user-attachments/assets/f55e4864-a9e0-4d86-9f29-5206bd91a0c4" />



<img width="1103" height="698" alt="Load_Reg_2" src="https://github.com/user-attachments/assets/f63fbeb0-2883-4295-81bc-df2633ee15ea" />

## TABULATION

### 1. LINE REGULATION (RL = 2000 Ω, constant)

| S.No | Input Voltage (V) | Output Voltage (V) |
|---|---:|---:|
| 1 | 30 | 10.10 |
| 2 | 40 | 10.12 |
| 3 | 50 | 10.14 |
| 4 | 60 | 10.16 |
| 5 | 70 | 10.18 |
| 6 | 80 | 10.20 |
| 7 | 90 | 10.22 |
| 8 | 100 | 10.24 |
| 9 | 110 | 10.26 |
| 10 | 120 | 10.28 |

### 2. LOAD REGULATION (Vin = 30 V, constant)

| S.No | Load Resistance (Ω) | Output Voltage (V) |
|---|---:|---:|
| 1 | 100 | 9.80 |
| 2 | 200 | 9.85 |
| 3 | 300 | 9.89 |
| 4 | 400 | 9.92 |
| 5 | 500 | 9.95 |
| 6 | 600 | 9.98 |
| 7 | 700 | 10.00 |
| 8 | 800 | 10.03 |
| 9 | 900 | 10.05 |
| 10 | 1000 | 10.08 |

## FORMULAE

### LINE REGULATION

% Line Regulation = Change in Output Voltage / Change in Input Voltage

% Line regulation = (ΔVo / ΔVin) × 100

### LOAD REGULATION

% Load Regulation = (No-load Voltage - Full-load Voltage) / Full-load Voltage) × 100

% Load regulation = (VNL − VFL) / VFL × 100

## SERIES RESISTANCE

Series resistance, Rs = (Vin − Vz) / (Iz + IL)

## MODEL GRAPHS

### LINE REGULATION GRAPH (Vin vs Vo)

<img width="1600" height="1000" alt="line_regulation_graph" src="https://github.com/user-attachments/assets/17dc8555-b812-4d98-ab91-bcde273c26d6" />

### LOAD REGULATION GRAPH (RL vs Vo)

<img width="1600" height="1000" alt="load_regulation_graph" src="https://github.com/user-attachments/assets/9d741239-4ea9-4bea-8c89-a9884d2f8995" />

## RESULT

Thus, the Zener diode was used as a voltage regulator, and its line regulation and load regulation characteristics were obtained.
