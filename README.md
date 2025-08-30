# LDO-low-drop-out-reegulator-

LDOs help maintain a stable output voltage even when the input voltage fluctuates or is higher than the desired output.

Types of Linear Regulators

1. Standard Linear Regulators: These are basic voltage regulators that maintain a constant output voltage.
2. Low Dropout Linear Regulators (LDOs): These are specialized regulators designed to work with a smaller difference between the input and output voltages.

Key Difference: Dropout Voltage

* Dropout Voltage: This is the minimum voltage required across the regulator to keep the output voltage stable.

For example, if you have a 3.3V regulator with a 1V dropout voltage, the input voltage must be at least 4.3V to ensure the output stays regulated at 3.3V.

watch video for more explaination:

https://youtu.be/kuY9KpJeZW0

Cadence design :

<img width="1088" height="687" alt="image" src="https://github.com/user-attachments/assets/9c6644b5-0c19-401d-8828-17eb565554fc" />

VDD change from 1.08 to 1.32 vs Vout:

<img width="1671" height="693" alt="image" src="https://github.com/user-attachments/assets/d696d63c-68b3-4050-9b49-974f4b13879b" />

Current load change against Vout : 

<img width="1670" height="709" alt="image" src="https://github.com/user-attachments/assets/2556e7c6-1dde-4577-9913-a13a4abba343" />

supply ramp VS vout with the CM input range 600m to 900m : 

![Uploading image.png…]()
