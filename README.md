# BJT Biasing Configurations Program

This Python program allows you to calculate and analyze various BJT (Bipolar Junction Transistor) biasing configurations. It supports the following biasing configurations:

1. Fixed Bias Configuration
2. Emitter Bias Configuration
3. Voltage Divider Bias Configuration
4. Collector Feedback Bias Configuration

## How to Use

1. Run the program by executing the Python script.
2. Choose one of the available biasing configurations by entering the corresponding number.
3. Enter the required parameters (e.g., Vcc, Vbe, Rb, Beta, Rc, Re, Rf, R1, R2) as prompted.
4. The program will calculate and display the collector current (Ic), base current (Ib), and collector-emitter voltage (Vce) for the chosen configuration.
5. You can choose to design multiple biasing circuits or exit the program.

## Biasing Configurations

### 1. Fixed Bias Configuration
   - This configuration sets the base current (Ib) using a base resistor (Rb).
   - Ic = Beta * Ib
   - Vce = Vcc - Ic * Rc

### 2. Emitter Bias Configuration
   - This configuration uses both a base resistor (Rb) and an emitter resistor (Re).
   - Ic = Beta * Ib
   - Vce = Vcc - Ic * (Rc + Re)

### 3. Voltage Divider Bias Configuration
   - This configuration uses voltage dividers (R1 and R2) to set the base voltage (Vb).
   - Ie = Ve / Re
   - Ib = Ie / (Beta + 1)
   - Ic = Beta * Ib
   - Vce = Vcc - Ic * (Rc + Re)

### 4. Collector Feedback Bias Configuration
   - This configuration uses a feedback resistor (Rf) to control the base current (Ib).
   - Ic = Beta * Ib
   - Vce = Vcc - Ic * (Rc + Re)


[B HARIHARASUDHAN]
