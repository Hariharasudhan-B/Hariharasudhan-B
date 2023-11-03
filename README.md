# Common-Emitter Transistor Calculator

This Python script calculates key parameters of a common-emitter transistor circuit.

## Prerequisites

- Python 3.x
- No additional libraries required

## How to Use

1. Run the script in your Python environment.
2. Enter the following parameters when prompted:
   - Vcc: Collector supply voltage (V)
   - Rb: Base resistor value (Ohms)
   - Vbe: Base-emitter voltage (V)
   - Beta: Transistor's current gain
   - Rc: Collector resistor value (Ohms)

## Code Explanation

- The script calculates base current (Ib), collector current (Ic), and collector-emitter voltage (Vce) based on user input and the transistor's characteristics.

## Example

```bash
$ python transistor_calculator.py
Vcc=12
Rb=1000
Vbe=0.7
Beta=100
Rc=2200

