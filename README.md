# Automobile & Electric Vehicles – Task 2

## EV Powertrain Architecture, Motor Types and Battery Management System (BMS)

This project is based on *Automobile & Electric Vehicles – Task 2*.

The main objective of this task is to understand EV powertrain architecture, electric motor types, inverter and motor controller, Battery Management System (BMS), battery safety and basic range calculation.

---

## 1. EV Powertrain Architecture

### Energy Flow

Charging Port → On-Board Charger → Battery Pack → Inverter → Motor → Reduction Gear → Wheels

### Main Components

- *Battery Pack* – Stores electrical energy in DC form.
- *BMS (Battery Management System)* – Monitors voltage, current and temperature and helps protect the battery.
- *Inverter* – Converts DC power from the battery into AC power for the motor.
- *Electric Motor* – Converts electrical energy into mechanical energy.
- *Reduction Gear* – Transfers suitable speed and torque to the wheels.
- *Wheels* – Receive torque and move the vehicle.

### Power Flow

*Battery DC → Inverter → AC Motor → Mechanical Energy → Reduction Gear → Wheels*

---

## 2. Electric Motor Types Used in EVs

| Motor Type | Main Features |
|---|---|
| BLDC Motor | High efficiency, compact and low maintenance |
| PMSM Motor | High efficiency, high power and torque density |
| Induction Motor | Robust, reliable and durable |

### PMSM

PMSM stands for *Permanent Magnet Synchronous Motor*.

It is commonly used in electric vehicles because of its high efficiency and good power and torque performance.

---

## 3. Inverter and Motor Controller

The inverter is an important power-electronics component of an EV.

Its main function is to:

- Convert DC power from the battery into AC power.
- Control the speed of the motor.
- Control the torque of the motor.
- Supply controlled electrical power to the traction motor.

---

## 4. Battery Management System (BMS)

BMS stands for *Battery Management System*.

### Main Functions

- Monitor battery voltage.
- Monitor battery current.
- Monitor battery temperature.
- Balance battery cells.
- Estimate battery state.
- Protect the battery from unsafe conditions.
- Support safe charging and discharging.

### Battery Safety

The BMS helps reduce battery safety risks by continuously monitoring important battery parameters.

It can help protect against:

- Overcharging
- Over-discharging
- Over-current
- Over-temperature
- Abnormal battery conditions

---

## 5. Thermal Runaway

Thermal runaway is a serious battery safety condition in which a battery cell can undergo rapid self-heating.

BMS and battery thermal-management systems help reduce this risk through:

- Continuous monitoring
- Temperature control
- Cell balancing
- Protection during abnormal conditions
- Fault detection and isolation

---

## 6. EV Range Calculation

A simple range calculation can be represented as:

*Range ≈ Usable Battery Energy ÷ Energy Consumption per km*

### Example

For a 45 kWh battery and 489 km certified range:

*Energy per km = 45 ÷ 489*

*Energy per km ≈ 0.092 kWh/km*

or

*≈ 9.2 kWh/100 km*

Actual range can vary depending on:

- Driving speed
- Driving style
- Road conditions
- Temperature
- HVAC usage
- Vehicle load

---

## 7. Case Study – Tata Nexon.ev

### Selected Vehicle

*Tata Nexon.ev 45*

### Specifications

| Parameter | Value |
|---|---|
| Motor Type | Permanent Magnet Synchronous Motor (PMSM) |
| Motor Power | 106 kW |
| Motor Torque | 215 Nm |
| Battery | 45 kWh |
| Certified Range | 489 km (MIDC) |

### Why PMSM?

PMSM provides high efficiency and good power and torque performance, making it suitable for electric vehicle applications.

---

## 8. Conclusion

An EV powertrain is an integrated system consisting of the battery, BMS, inverter, electric motor, reduction gear and wheels.

The battery stores electrical energy, the BMS monitors and protects the battery, the inverter controls electrical power, and the motor converts electrical energy into mechanical energy to drive the vehicle.

Understanding these components provides a basic foundation for studying electric vehicle technology.

---

## 9. Project Files

- README.md – Project documentation
- EV_Powertrain_Diagram.png – EV powertrain block diagram
- EV_Task_2_Report.pdf – Complete Task 2 report

---

## 10. References

- Automobile & Electric Vehicles – Task 2 learning material
- Tata.ev – Nexon.ev specifications
- NPTEL – Electric Vehicles course
- EV powertrain and BMS learning resources
