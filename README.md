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

supply ramp VS vout : 

<img width="994" height="824" alt="image" src="https://github.com/user-attachments/assets/4b980c51-0d71-4ca9-94ab-95852b22ea65" />


Vref ramp in CM range 600m to 900m :

<img width="1671" height="722" alt="image" src="https://github.com/user-attachments/assets/b1d1a48d-50d0-4a82-8f21-bf266a18cb07" />

AC responce :

<img width="1912" height="763" alt="image" src="https://github.com/user-attachments/assets/5b810f8d-6423-4369-bdc9-8c60b8f9a934" />

PM and GM

<img width="1917" height="722" alt="image" src="https://github.com/user-attachments/assets/60e90f9c-1a68-4191-b16a-17a58c62676c" />

