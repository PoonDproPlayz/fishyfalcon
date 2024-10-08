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
| 0.2uF SMD capacitor | 4 | $ 0.54 | C0805 | [https://www.lcsc.com/product-detail/Multilayer-Ceramic-Capacitors-MLCC-SMD-SMT_CCTC-TCC0805X7R204K500DT_C344170.html](https://www.lcsc.com/product-detail/Multilayer-Ceramic-Capacitors-MLCC-SMD-SMT_CCTC-TCC0805X7R204K500DT_C344170.html) |
| 2x3 2.54mm male pins | 4 | $ 0.44 | Diag configuration | [https://www.lcsc.com/product-detail/Pin-Headers_CJT-Changjiang-Connectors-A2541WV-2x3P_C225518.html](https://www.lcsc.com/product-detail/Pin-Headers_CJT-Changjiang-Connectors-A2541WV-2x3P_C225518.html) |
| 3x3 2.54mm male pins | 4 | $ 0.88 | SPI/UART configuration | [https://www.lcsc.com/product-detail/Pin-Headers_HCTL-PZ254-3-03-Z-2-5-G0_C7429377.html](https://www.lcsc.com/product-detail/Pin-Headers_HCTL-PZ254-3-03-Z-2-5-G0_C7429377.html) |
| JST XH 2P | 4 | $ 0.36 | Endstops | [https://www.lcsc.com/product-detail/Wire-To-Board-Connector_span-style-background-color-ff0-JST-span-B2B-XH-A-LF-SN_C158012.html](https://www.lcsc.com/product-detail/Wire-To-Board-Connector_span-style-background-color-ff0-JST-span-B2B-XH-A-LF-SN_C158012.html) |
| JST XH 4P | 4 | $ 0.42 | Driver out | [https://www.lcsc.com/product-detail/Wire-To-Board-Connector_span-style-background-color-ff0-JST-span-B4B-XH-A-LF-SN_C144395.html](https://www.lcsc.com/product-detail/Wire-To-Board-Connector_span-style-background-color-ff0-JST-span-B4B-XH-A-LF-SN_C144395.html) |
| AO3400A | 12 | $ 1.07 | SOT-23 Mosfet for external driver | [https://www.lcsc.com/product-detail/MOSFETs_Alpha-Omega-Semicon-AO3400A_C20917.html](https://www.lcsc.com/product-detail/MOSFETs_Alpha-Omega-Semicon-AO3400A_C20917.html) |
| 10K SMD Resistor | 4 | $ 0.22 | R1206 1/4W Enable pin resistor | [https://www.lcsc.com/product-detail/Chip-Resistor-Surface-Mount_FH-Guangdong-Fenghua-Advanced-Tech-RS-06K103JT_C118075.html](https://www.lcsc.com/product-detail/Chip-Resistor-Surface-Mount_FH-Guangdong-Fenghua-Advanced-Tech-RS-06K103JT_C118075.html) |
| 0Ω SMD Resistor | 12 | $ 0.39 | R1206 Check if your mosfet needs a differnt value resistor | [https://www.lcsc.com/product-detail/Chip-Resistor-Surface-Mount_Vishay-Intertech-RCA12060000ZSEA_C4126934.html](https://www.lcsc.com/product-detail/Chip-Resistor-Surface-Mount_Vishay-Intertech-RCA12060000ZSEA_C4126934.html) |
| JST XH 6P | 4 | $ 0.65 | External driver out | [https://www.lcsc.com/product-detail/Wire-To-Board-Connector_span-style-background-color-ff0-JST-span-B6B-XH-AM-LF-SN_C161873.html](https://www.lcsc.com/product-detail/Wire-To-Board-Connector_span-style-background-color-ff0-JST-span-B6B-XH-AM-LF-SN_C161873.html) |
| 63v 330 or 470uF electrolytic cap | 4 | $ 1.71 | Stepper caps | [https://www.lcsc.com/product-detail/Aluminum-Electrolytic-Capacitors-Leaded_SamYoung-Electronics-NXA63V470M12-5-20-5-0TP_C346981.html](https://www.lcsc.com/product-detail/Aluminum-Electrolytic-Capacitors-Leaded_SamYoung-Electronics-NXA63V470M12-5-20-5-0TP_C346981.html) |
| 10A ATO fuse | 2 | $ 0.45 | Power in fuse | [Aliexpress](https://aliexpress.com/item/1005005797789486.html)  [LCSC](https://www.lcsc.com/product-detail/Fuse-Holders_XFCN-XF-506P_C492610.html) |
| 1x20 2.54 female pins | 2-4 | $ 0.76 | Blackpill/pico socket | [https://www.lcsc.com/product-detail/Female-Headers_JILN-22850120ANG1SYA01_C429947.html](https://www.lcsc.com/product-detail/Female-Headers_JILN-22850120ANG1SYA01_C429947.html) |
| 1x8 2.54 female pins | 8 | $ 0.53 | Stepstick socket | [https://www.lcsc.com/product-detail/Female-Headers_Liansheng-FH-00882_C2685213.html](https://www.lcsc.com/product-detail/Female-Headers_Liansheng-FH-00882_C2685213.html) |
| 1x3 2.54 male pins | 10 | $ 1.52 | Dual driver and motor voltage selection | [https://www.lcsc.com/product-detail/Wire-To-Board-Connector_MOLEX-22032031_C505002.html](https://www.lcsc.com/product-detail/Wire-To-Board-Connector_MOLEX-22032031_C505002.html) |
| 1x2 2.54 male pins | 4 | $ 0.60 | Diag and vref pins | [https://www.lcsc.com/product-detail/span-style-background-color-ff0-Female-span-Headers_Shenzhen-Kinghelm-Elec-KH-2-54FH-1X2P-H8-5_C2905414.html](https://www.lcsc.com/product-detail/span-style-background-color-ff0-Female-span-Headers_Shenzhen-Kinghelm-Elec-KH-2-54FH-1X2P-H8-5_C2905414.html)|
| STM32F4x1 Blackpill | 1 | $ 3.05 | MCU(Choose one) | [https://www.aliexpress.com/item/1005006127461676.html](https://www.aliexpress.com/item/1005006127461676.html) |
| Pi Pico | 1 | $ 2.66 | MCU(Choose one) | [https://th.aliexpress.com/item/1005003708090298.html?gatewayAdapt=glo2tha](https://aliexpress.com/item/1005003708090298.html) |
| MC34063ADR | 1 | $ 1.30 | SOIC-8 Adjustable dc-dc converter | [https://www.lcsc.com/product-detail/DC-DC-Converters_Texas-Instruments-MC34063ADR_C100023.html](https://www.lcsc.com/product-detail/DC-DC-Converters_Texas-Instruments-MC34063ADR_C100023.html) |
| 0.33Ω SMD Resistor | 1 | $ 0.29 | 0603 resistor | [https://www.lcsc.com/product-detail/Chip-Resistor-Surface-Mount_UNI-ROYAL-Uniroyal-Elec-0603WAJ033KT5E_C247018.html](https://www.lcsc.com/product-detail/Chip-Resistor-Surface-Mount_UNI-ROYAL-Uniroyal-Elec-0603WAJ033KT5E_C247018.html) |
| 470pf SMD Cap | 1 | $ 0.26 | 0603 Cap | [https://www.lcsc.com/product-detail/Multilayer-Ceramic-Capacitors-MLCC-SMD-SMT_FH-Guangdong-Fenghua-Advanced-Tech-0603B471K500NT_C1620.html](https://www.lcsc.com/product-detail/Multilayer-Ceramic-Capacitors-MLCC-SMD-SMT_FH-Guangdong-Fenghua-Advanced-Tech-0603B471K500NT_C1620.html) |
| 1N5819 Diode | 1 | $ 0.42 | Schottkey Diode | [https://www.lcsc.com/product-detail/Schottky-Diodes_STMicroelectronics-1N5819_C110032.html](https://www.lcsc.com/product-detail/Schottky-Diodes_STMicroelectronics-1N5819_C110032.html) |
| 220uH SMD inductor | 1 | $ 0.41 | SMD inductor | [https://www.lcsc.com/product-detail/Power-Inductors_YJYCOIN-CD54YP0504-221M_C492674.html](https://www.lcsc.com/product-detail/Power-Inductors_YJYCOIN-CD54YP0504-221M_C492674.html) |
| 1uH SMD inductor | 1 | $ 0.19 | L0603 inductor | [https://www.lcsc.com/product-detail/Inductors-SMD_Sunlord-SDFL1608Q1R0KTF_C22037.html](https://www.lcsc.com/product-detail/Inductors-SMD_Sunlord-SDFL1608Q1R0KTF_C22037.html) |
| 3.83K SMD resistor | 1 | $ 0.10 | 0603 resistor | [https://www.lcsc.com/product-detail/Chip-Resistor-Surface-Mount_UNI-ROYAL-Uniroyal-Elec-0603WAF3831T5E_C22982.html](https://www.lcsc.com/product-detail/Chip-Resistor-Surface-Mount_UNI-ROYAL-Uniroyal-Elec-0603WAF3831T5E_C22982.html) |
| 100uf 63v cap | 2 | $ 0.53 | 100uf tht cap | [https://www.lcsc.com/product-detail/Aluminum-Electrolytic-Capacitors-Leaded_CX-Dongguan-Chengxing-Elec-KM107M063G13RR0VH2FP0_C45675.html](https://www.lcsc.com/product-detail/Aluminum-Electrolytic-Capacitors-Leaded_CX-Dongguan-Chengxing-Elec-KM107M063G13RR0VH2FP0_C45675.html) |
| 470uf 50v cap | 1 | $ 0.54 | 470uf tht cap | [https://www.lcsc.com/product-detail/Aluminum-Electrolytic-Capacitors-Leaded_CX-Dongguan-Chengxing-Elec-GR477V050G20RR0VH4FP0_C3312.html](https://www.lcsc.com/product-detail/Aluminum-Electrolytic-Capacitors-Leaded_CX-Dongguan-Chengxing-Elec-GR477V050G20RR0VH4FP0_C3312.html) |
| 1.2k SMD resistor  | 1 | $ 0.66 | 0603 SMD resistor | [https://www.lcsc.com/product-detail/Chip-Resistor-Surface-Mount_Viking-Tech-AR03DTCX1201_C319998.html](https://www.lcsc.com/product-detail/Chip-Resistor-Surface-Mount_Viking-Tech-AR03DTCX1201_C319998.html) |

Total(Excluding shipping/tax etc.) ≈ $ 12.8

# Dual Driver Setting
| Setting | Instructions |
| ------------- | ------------- |
| ![dual driver mode](https://github.com/PoonDproPlayz/fishyfalcon/blob/main/Images/Dual_driver_mode.png)|Bridge the following pins with jumpers to drive driver 1 and 2 together and driver 3 and 4 together |
| ![Single driver mode](https://github.com/PoonDproPlayz/fishyfalcon/blob/main/Images/Individual_driver_mode.png)|Bridge the following pins with jumpers to individually drive each motor |

Left side is driver 1 and 2 right is 3 and 4. Each 3x3 block has DIR, STEP, EN in order from left to right

# Motor Voltage Selection

| Setting | Instructions |
| ------------- | ------------- |
|![VM as driver power](https://github.com/PoonDproPlayz/fishyfalcon/blob/main/Images/VM_for_motors.png)| Bridge the following pins with jumpers to supply the motor with the VM DC input |
|![VM as driver power](https://github.com/PoonDproPlayz/fishyfalcon/blob/main/Images/VB_for_motors.png)| Bridge the following pins with jumpers to supply the motor with the VB DC input |

# Assembly
[PCB Assembly](https://github.com/PoonDproPlayz/fishyfalcon/blob/main/Docs/Assembly.md)<br />
[Board Mounting](https://github.com/PoonDproPlayz/fishyfalcon/blob/main/Docs/Mounting%20the%20board.md)

# Credits
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• **69420exp** For his work on Dual driver control and part of the schematics<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• **Annex Engineering** For their pinouts<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• **comradef191** (Discord:f191) For the jumper configurations for the stepstick/polulu style drivers and the extensive work on the CAD models<br />
