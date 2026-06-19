# INVRECTIVER

## About The Project.

INVRECTIVER is a 12V DC to 230V AC inverter, but of course it does not end there.

After creating dangerous 230V AC, the circuit converts it back down, rectifies it and gives you 24V DC. So basically you get a completely pointless, extremely inefficient and massively overcomplicated 12V to 24V boost converter.

12V DC -> 230V AC -> 24V DC

Does this make any sense? probably not.

Is it cool? yes.



## WARNING

This board generates 230V AC.

It can shock you, destroy components, start a fire or do all of these things at the same time.

Do not touch the high voltage side while the board is powered. Use proper insulation, fuses and common sense. Building or using this project is entirely at your own risk.



## BOM

| Nr | Ref                                     | Value             | Footprint                                                | Qty |
| -: | --------------------------------------- | ----------------- | -------------------------------------------------------- | --: |
|  1 | C1                                      | 100nF             | C_0603_1608Metric                                        |   1 |
|  2 | C2                                      | 2200uF            | CP_Radial_D16.0mm_P7.50mm                                |   1 |
|  3 | C3                                      | 0.33uF            | C_0603_1608Metric                                        |   1 |
|  4 | C4                                      | 10uF              | CP_Radial_D5.0mm_P2.00mm                                 |   1 |
|  5 | R1, R4, R5                              | 100K              | R_2010_5025Metric                                        |   3 |
|  6 | R2, R3                                  | 51k               | R_2010_5025Metric                                        |   2 |
|  7 | R6, R7                                  | 470               | R_2010_5025Metric                                        |   2 |
|  8 | R8                                      | 1                 | R_2010_5025Metric                                        |   1 |
|  9 | D1                                      | GBU4M             | Diode_Bridge_Vishay_GBU                                  |   1 |
| 10 | U1                                      | TL494             | DIP-16_W7.62mm                                           |   1 |
| 11 | U2                                      | LM7824_TO220      | TO-220-3_Vertical                                        |   1 |
| 12 | Q1, Q2, Q3, Q4, Q5, Q6, Q7, Q8, Q9, Q10 | IRF3205           | TO-220-3_Vertical                                        |  10 |
| 13 | Q11                                     | TIP2955           | TO-218-3_Vertical                                        |   1 |
| 14 | T1                                      | 12-230            | Transformer_CHK_EI30-2VA_2xSec                           |   1 |
| 15 | T2                                      | Transformer_1P_1S | Transformer_37x44                                        |   1 |
| 16 | J1                                      | 12VDC             | TerminalBlock_Phoenix_MKDS-1,5-2_1x02_P5.00mm_Horizontal |   1 |
| 17 | J2                                      | 24V               | TerminalBlock_Phoenix_MKDS-1,5-2_1x02_P5.00mm_Horizontal |   1 |
