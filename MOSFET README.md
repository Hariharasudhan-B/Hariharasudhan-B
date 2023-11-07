# MOSFET Biasing Configurations Program

This Python program allows you to calculate and analyze various MOSFET (Metal-Oxide-Semiconductor Field-Effect Transistor) biasing configurations. It supports the following biasing configurations:

1. Fixed Bias Configuration
2. Voltage Divider Bias Configuration

## How to Use

1. Run the program by executing the Python script.
2. Choose one of the available biasing configurations by entering the corresponding number.
3. Enter the required parameters (e.g., Vdd, Id, Rs, R1, R2, Is, Rd) as prompted.
4. The program will calculate and display the relevant voltage levels for the chosen configuration.
5. You can choose to analyze multiple biasing circuits or exit the program.

## Biasing Configurations

### 1. Fixed Bias Configuration
   - This configuration calculates the voltage across the drain and source (Vds) for a MOSFET with fixed biasing parameters.
   - Vds = Vdd - (Id * Rs)

### 2. Voltage Divider Bias Configuration
   - This configuration calculates the voltage across the gate and source (Vgs) and the voltage across the drain and source (Vds) for a MOSFET with voltage divider biasing.
   - Vg is calculated using a voltage divider formula, and Vgs is then adjusted for the effect of the source current (Is).
   - Vds is calculated as Vdd - Id * (Rd + Rs)
   -
     [B HARIHARASUDHAN]
