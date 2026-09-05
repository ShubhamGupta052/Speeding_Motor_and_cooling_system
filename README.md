# ⚙️ Speed Monitoring and Cooling System in Industrial Machinery

A **LabVIEW-based industrial monitoring and control system** designed to monitor motor speed and machine temperature while automatically controlling a cooling fan based on predefined operating conditions.

The project simulates an industrial machine environment and demonstrates how LabVIEW can be used for **real-time monitoring, threshold-based decision making, and automated control**.

---

## 🚀 Features

- 📊 Real-time **Motor Speed / RPM monitoring**
- 🌡️ Machine **Temperature monitoring**
- 📈 Graphical motor-speed gauge
- 🟢 Automatic **FAN ON / FAN OFF** control
- 🔥 Machine heating status indication
- ⚠️ High-speed condition detection
- 📋 Temperature classification:
  - Low
  - Normal
  - High
- 🖥️ Industrial-style LabVIEW Front Panel
- 🔄 Continuous monitoring using a While Loop
- 🧪 Simulated machine parameters for testing

---

## 🎯 Project Objective

The objective of this project is to develop a simple industrial monitoring system capable of:

1. Monitoring motor speed.
2. Monitoring machine temperature.
3. Detecting abnormal operating conditions.
4. Automatically activating the cooling fan when required.
5. Providing clear visual feedback to the operator.

---

## 🛠️ Technology Used

- **LabVIEW**
- Graphical Programming
- While Loop
- Case Structure
- Shift Registers
- Comparison Functions
- Select Functions
- Boolean Logic
- Arithmetic Operations

  ## ⚙️ System Working

The system continuously monitors the simulated motor operating conditions.

### 1. Motor Speed Monitoring

The motor speed is displayed using:

- Numerical RPM indicator
- Analog speed gauge

The measured/simulated speed is continuously compared with predefined thresholds.

Based on the speed condition, the system determines whether cooling action is required.

---

### 2. Temperature Monitoring

The machine temperature is continuously calculated and displayed in degrees Celsius.

The temperature condition is classified into three levels:

```text
              Machine Temperature
                       │
          ┌────────────┼────────────┐
          ▼            ▼            ▼
         Low         Normal         High
- String Formatting
- Timing Functions
- Data Visualization
```
## LabVIEW Implementation

The system is implemented using several core LabVIEW programming concepts.

### Programming Structures

- While Loop for continuous monitoring
- Shift Register for maintaining values between loop iterations
- Comparison functions for threshold detection
- Arithmetic functions for parameter calculations
- Select functions for control decisions
- Case Structure for machine-condition handling
- Boolean logic for FAN control
- Timing functions for controlled execution
- String conversion for displaying temperature information

## Control Logic

The basic control flow of the system is:

```text
Simulated Machine Parameters
            ↓
      Motor Speed / RPM
            ↓
    Threshold Comparison
            ↓
     Machine Condition
            ↓
      Cooling Decision
        ↙          ↘
    FAN ON        FAN OFF
            ↓
     Update Indicators
            ↓
       Repeat Loop
```
