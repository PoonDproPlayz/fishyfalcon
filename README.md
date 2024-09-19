# FishyFalcon
A quad motor 3D printer board that supports spi or uart control on stepstick drivers and external driver functionality it is based around the STM32 Blackpill and the Pi Pico.<br />
### Features
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• SPI or UART on all 4 motors<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• External driver support through the AO3400 mosfet<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• Dual driver control through only 3 pins<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• Sensorless homing (not tested yet)
# Bill Of Materials
| Component Name  | No. Required | Total Price | Remarks | Link |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| 7.62mm Screw Terminal 4P | 1 | $ 0.2115 | Power in | [https://www.lcsc.com/product-detail/Barrier-Terminal-Blocks_Cixi-Kefa-Elec-KF7-62-4P_C707826.html](https://www.lcsc.com/product-detail/Barrier-Terminal-Blocks_Cixi-Kefa-Elec-KF7-62-4P_C707826.html) |
| 0.2uF SMD capacitor | 4 | $ 0.50 | C0603 | [https://www.lcsc.com/product-detail/Multilayer-Ceramic-Capacitors-MLCC-SMD-SMT_Meritek-MA0603XR204K160_C3855511.html](https://www.lcsc.com/product-detail/Multilayer-Ceramic-Capacitors-MLCC-SMD-SMT_Meritek-MA0603XR204K160_C3855511.html) |
| 2x3 2.54mm male pins | 4 | $ 0.44 | Diag configuration | [https://www.lcsc.com/product-detail/Pin-Headers_CJT-Changjiang-Connectors-A2541WV-2x3P_C225518.html](https://www.lcsc.com/product-detail/Pin-Headers_CJT-Changjiang-Connectors-A2541WV-2x3P_C225518.html) |
| 3x3 2.54mm male pins | 4 | $ 0.88 | SPI/UART configuration | [https://www.lcsc.com/product-detail/Pin-Headers_HCTL-PZ254-3-03-Z-2-5-G0_C7429377.html](https://www.lcsc.com/product-detail/Pin-Headers_HCTL-PZ254-3-03-Z-2-5-G0_C7429377.html) |
| JST XH 2P | 4 | $ 0.36 | Endstops | [https://www.lcsc.com/product-detail/Wire-To-Board-Connector_span-style-background-color-ff0-JST-span-B2B-XH-A-LF-SN_C158012.html](https://www.lcsc.com/product-detail/Wire-To-Board-Connector_span-style-background-color-ff0-JST-span-B2B-XH-A-LF-SN_C158012.html) |
| JST XH 4P | 4 | $ 0.42 | Driver out | [https://www.lcsc.com/product-detail/Wire-To-Board-Connector_span-style-background-color-ff0-JST-span-B4B-XH-A-LF-SN_C144395.html](https://www.lcsc.com/product-detail/Wire-To-Board-Connector_span-style-background-color-ff0-JST-span-B4B-XH-A-LF-SN_C144395.html) |
| AO3400A | 12 | $ 1.07 | SOT-23 Mosfet for external driver | [https://www.lcsc.com/product-detail/MOSFETs_Alpha-Omega-Semicon-AO3400A_C20917.html](https://www.lcsc.com/product-detail/MOSFETs_Alpha-Omega-Semicon-AO3400A_C20917.html) |
| 10K SMD Resistor | 4 | $ 0.22 | R1206 1/4W Enable pin resistor | [https://www.lcsc.com/product-detail/Chip-Resistor-Surface-Mount_FH-Guangdong-Fenghua-Advanced-Tech-RS-06K103JT_C118075.html](https://www.lcsc.com/product-detail/Chip-Resistor-Surface-Mount_FH-Guangdong-Fenghua-Advanced-Tech-RS-06K103JT_C118075.html) |
| 0Ω SMD Resistor | 12 | $ 0.39 | R1206 Check if your mosfet needs a differnt value resistor | [https://www.lcsc.com/product-detail/Chip-Resistor-Surface-Mount_Vishay-Intertech-RCA12060000ZSEA_C4126934.html](https://www.lcsc.com/product-detail/Chip-Resistor-Surface-Mount_Vishay-Intertech-RCA12060000ZSEA_C4126934.html) |
|  |  |  |  |  |
|  |  |  |  |  |
|  |  |  |  |  |
|  |  |  |  |  |
|  |  |  |  |  |
|  |  |  |  |  |
|  |  |  |  |  |
|  |  |  |  |  |
|  |  |  |  |  |
|  |  |  |  |  |
|  |  |  |  |  |

# Credits
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• **69420exp** For his idea on Dual driver control through only 3 pins<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• **Annex Engineering** For their pinouts<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• **comradef191** (Discord:f191) For the jumper configurations for the stepstick/polulu style drivers<br />
