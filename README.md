# Keychain-PCB-v1

This project is a simple USB powered PCB keychain that lights up when plugged into a computer. It has zaero storage or data. The goal of this V1 was to learn the basics of USB power, schematics, and PCB layout without adding unnecessary complexity (im a bit rusty) 

The board uses USB 5V to power an LED through a resistor. The USB data lines are left unconnected on purpose. The keychain is meant to hang on my large, annoying set of keys and includes my personalized information on the back. If I ever lose them, whoever finds them knows who to return them to.

## BOM
| Item       | Description             | Quantity | Unit Price ($) | Total Price ($) | URL                                                                 | Running Total ($ w/ Tax) | Total w/ Shipping ($) |
|------------|-------------------------|----------|----------------|-----------------|----------------------------------------------------------------------|---------------------------|------------------------|
| C130115    | White SMD LED 0805      | 5        | 0.03           | 0.16            | https://www.lcsc.com/product-detail/C130115.html                     | 0.18                      | 16.78                  |
| C2076063   | 1 kΩ Resistor 0603      | 5        | 0.52           | 2.60            | https://www.lcsc.com/product-detail/C2076063.html                    | 2.94                      |                        |
| PCB        | PCB Manufacturing       | 5        | 0.44           | 2.20            | https://jlcpcb.com/                                                  | 2.49                      | 8.10                   |
| **Total**  |                         |          |                |                 |                                                                      |                           | **24.88**              |

### Rendered PCB
<p align="center">
  <img src="https://github.com/user-attachments/assets/67903d46-914f-4622-a309-406cb042df3b" width="400">
  <img src="https://github.com/user-attachments/assets/51e553e5-0311-493a-b316-a6d51e7083c9" width="400">
</p>

### Schematic
<p align="center">
  <img src="https://github.com/user-attachments/assets/81a5dd21-4a75-4edb-bf1c-8e0d61c9e63a" width="400">
  <img width="400" height="500" alt="image" src="https://github.com/user-attachments/assets/8e3dbd1f-46d7-4843-9c93-cb991eb85dae" />

</p>
