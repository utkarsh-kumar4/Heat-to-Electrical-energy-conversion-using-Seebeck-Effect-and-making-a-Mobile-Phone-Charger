# Heat to Electrical Energy Conversion Using Seebeck Effect and Mobile Phone Charger 🔥📱

## Introduction 🌟
This project explores how to convert heat into electrical energy using the Seebeck Effect and how to use that energy to charge a mobile phone. I employed Peltier modules to capture heat, used a Boost Converter to convert the energy into a usable 5V output, and stored excess heat energy in a thermal energy storage tank.

## Project Overview 🛠️

### 1. **Seebeck Effect and Peltier Modules**
The Seebeck Effect is a phenomenon where a temperature difference between two dissimilar conductors or semiconductors generates an electric voltage. The basic equation governing the Seebeck Effect is:

<div align="center">V = α⋅ΔT</div>

where:
- V is the generated voltage (in volts),
- α is the Seebeck coefficient (in volts per degree Celsius),
- ΔT is the temperature difference between the two sides of the Peltier module (in degrees Celsius).

This equation tells us that the greater the temperature difference, the higher the voltage generated.

### 2. **Boost Converter for Voltage Regulation**
A Boost Converter is an electronic circuit that increases the voltage from a lower level to a higher, more useful level. The output voltage Vout of a Boost Converter is related to the input voltage Vin and the duty cycle D by the equation:

<div align="center">Vout = Vin/(1 - D)</div>

where:
- Vout is the output voltage,
- Vin is the input voltage,
- D is the duty cycle (the fraction of time the switch is on during one cycle).

This equation shows that by adjusting the duty cycle D, we can control the output voltage.

### 3. **Thermal Energy Storage Tank**
The thermal energy storage tank stores surplus heat energy that can be used later when the temperature difference across the Peltier module is insufficient. The energy stored Q in a thermal energy storage tank is given by:

<div align="center">Q = m⋅c⋅ΔT</div>

where:
- Q is the stored energy (in joules),
- m is the mass of the storage material (in kilograms),
- c is the specific heat capacity of the material (in joules per kilogram per degree Celsius),
- ΔT is the temperature difference between the initial and final states (in degrees Celsius).

This stored energy can be used later to maintain the temperature difference across the Peltier module.

## How It Works ⚙️

1. **Heat Capture** 🔥: 
   - The Peltier module captures heat from a heat source (e.g., hot water, solar heat).
   - One side of the Peltier module is heated while the other is kept cooler, creating a temperature difference.

2. **Electricity Generation** ⚡:
   - This temperature difference causes the Seebeck Effect, generating a small voltage based on V = α⋅ΔT.

3. **Voltage Boosting** 🔋:
   - The Boost Converter steps up the low voltage to a stable 5V DC output, calculated using Vout = Vin/(1 - D).

4. **Mobile Phone Charging** 📱:
   - The 5V DC output is used to charge the mobile phone.

5. **Thermal Energy Storage** 🌡️:
   - Any excess heat is stored in the thermal energy storage tank, with the stored energy Q calculated using Q = m⋅c⋅ΔT.

## Diagram 🖼️
![Project Diagram](images/system-diagram.png)

### Explanation 📋:
- **Heat Source**: The origin of heat is hot water.
- **Peltier Module**: Converts heat into a small electrical voltage.
- **Boost Converter**: Increases the voltage to 5V DC.
- **Mobile Phone**: Receives the 5V DC for charging.
- **Thermal Storage Tank**: Stores excess heat for later use.

![Final Setup](images/final-setup.jpg)
