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
| JST XH 6P | 4 | $ 0.65 | External driver out | [https://www.lcsc.com/product-detail/Wire-To-Board-Connector_span-style-background-color-ff0-JST-span-B6B-XH-AM-LF-SN_C161873.html](https://www.lcsc.com/product-detail/Wire-To-Board-Connector_span-style-background-color-ff0-JST-span-B6B-XH-AM-LF-SN_C161873.html) |
| 63v 330 or 470uF electrolytic cap | 4 | $ 1.71 | Stepper caps | [https://www.lcsc.com/product-detail/Aluminum-Electrolytic-Capacitors-Leaded_SamYoung-Electronics-NXA63V470M12-5-20-5-0TP_C346981.html](https://www.lcsc.com/product-detail/Aluminum-Electrolytic-Capacitors-Leaded_SamYoung-Electronics-NXA63V470M12-5-20-5-0TP_C346981.html) |
| 10A ATO fuse | 2 | $ 0.45 | Power in fuse | [Aliexpress](https://th.aliexpress.com/item/1005005797789486.html?spm=a2g0o.productlist.main.113.46e4FyWqFyWqRg&algo_pvid=8082f12f-0c4f-4b94-bf32-0519158d965a&algo_exp_id=8082f12f-0c4f-4b94-bf32-0519158d965a-56&pdp_npi=4%40dis%21THB%2147.45%2134.14%21%21%219.78%217.04%21%402102f64217267951116064460ecb86%2112000034387804504%21sea%21TH%216003091004%21ABX&curPageLogUid=Qp1bEZ2w7e2J&utparam-url=scene%3Asearch%7Cquery_from%3A)[LCSC](https://www.lcsc.com/product-detail/Fuse-Holders_XFCN-XF-506P_C492610.html) |
| 1x20 2.54 female pins | 2-4 | $ 0.76 | Blackpill/pico socket | [https://www.lcsc.com/product-detail/Female-Headers_JILN-22850120ANG1SYA01_C429947.html](https://www.lcsc.com/product-detail/Female-Headers_JILN-22850120ANG1SYA01_C429947.html) |
| 1x8 2.54 female pins | 8 | $ 0.53 | Stepstick socket | [https://www.lcsc.com/product-detail/Female-Headers_Liansheng-FH-00882_C2685213.html](https://www.lcsc.com/product-detail/Female-Headers_Liansheng-FH-00882_C2685213.html) |
| 1x3 2.54 male pins | 10 | $ 1.52 | Dual driver and motor voltage selection | [https://www.lcsc.com/product-detail/Wire-To-Board-Connector_MOLEX-22032031_C505002.html](https://www.lcsc.com/product-detail/Wire-To-Board-Connector_MOLEX-22032031_C505002.html) |
| STM32F4x1 Blackpill | 1 | $ 3.05 | MCU(Choose one) | [https://www.aliexpress.com/item/1005006127461676.html](https://www.aliexpress.com/item/1005006127461676.html) |
| Pi Pico | 1 | $ 2.66 | MCU(Choose one) | [https://th.aliexpress.com/item/1005003708090298.html?gatewayAdapt=glo2tha](https://th.aliexpress.com/item/1005003708090298.html?gatewayAdapt=glo2tha) |
Total(Excluding shipping/tax etc.) ≈ $ 12.8

# Credits
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• **69420exp** For his idea on Dual driver control through only 3 pins<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• **Annex Engineering** For their pinouts<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• **comradef191** (Discord:f191) For the jumper configurations for the stepstick/polulu style drivers<br />
