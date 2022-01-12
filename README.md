# Battery Testing Consortium (BTC)
The Battery Testing Consortium (BTC) has been developed within the High Voltage and Energy Storage Lab at Oxford Brookes University to provide accurate and comprehensive cell data to Formula Student Electric teams. Through the BTC, we aim to provide FS teams with information for improved and informed decisions for cell selection, pack architecture design, thermal cooling requirements, and end of life predictions. A range of tests are completed to provide a comprehensive electrochemical lithium-ion characterisation for modelling, validation, and battery management parameterisation.

This repository provides one open-source sample dataset of the larger consortium dataset. To join the consortium, visit the [HVES website].

## Total Consortium Cells
|Cell|Chemistry|Nom. Voltage [V]|Nom. Capacity [Ah]|Energy Density [Wh/kg]|
|---|---|---|---|---|
| Samsung 25R  | NMC  | 3.6  | 2.5  | 206  |
|  LG HG2 |  NMC | 3.6  | 3  |  236 |
|  Sony VTC6 | NMC  | 3.6  |  3 |  232 |
|  Melasta SLPB6542126| LCO  | 3.7  | 3.9  | 191  |
|  Melasta SLPB8542126 | LCO  | 3.7  | 5.2  | 189  |
|  Melasta SLPB8346143 | LCO  | 3.7  | 6.3  | 196  |
|  Melasta SLPBB142124  | LCO  | 3.7  | 6.8  | 202  |
|  Melasta SLPB8870175 | LCO  | 3.7  | 12  | 197  |
|  Melasta SLPB7336128HV | NMC  | 3.8  | 3.7  | 204  |
|  Melasta SLPB9542124HV | NMC  | 3.8  | 5.95  | 215  |
|  Melasta SLPBB042126HV | NMC  |  3.8 | 7.5  | 228 |
|  Melasta SLPB7579207HV| NMC  | 3.8  | 15.4  | 227  |


## Notes
* For all tests dated before September 25th, 2021: Offset thermocouple measurements by 1.5°C (i.e. 30°C -> 28.5°C).
* Unless stated otherwise, all cells are stored in a controlled climate at 15°C.


## Consortium Overview
An abriged overview describing the tests completed and data organisation can be found in [here].


## Contact / Issues
For issues and bugs, please open an [issue]. All feedback is welcome.
To get involved or discuss testing methods, please contact hves@brookes.ac.uk.


[issue]: https://github.com/Oxford-Brookes-HVES/BTC/issues
[here]: https://github.com/Oxford-Brookes-HVES/BTC/blob/main/BTC-Overview.pdf
[HVES website]: https://hves.brookes.ac.uk/btc/
