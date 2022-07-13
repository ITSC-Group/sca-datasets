# SCA Datasets
Collection of metadata of different Side Channel Attack datasets.
If you find a new dataset, feel free to add it by creating a pull request.

## Main datasets

| Name | Traces | Features | Device | Algorithm | Countermeasures | Keys | Aquisition | Papers | URL |
|---|---|---|---|---|---|---|---|---|---|
| ASCAD v1 fixed key | 50000 / 10000 | 100000? | ATMEGA8515 | AES128 | 1st order XOR Boolean Masking | fixed | EM | https://link.springer.com/article/10.1007/s13389-019-00220-8 | see versions below |
| ASCAD v1 variable key | 50000 / 10000 | 100000? | ATMEGA8515 | AES128 | 1st order XOR Boolean Masking | random | EM |https://link.springer.com/article/10.1007/s13389-019-00220-8 | https://github.com/ANSSI-FR/ASCAD/tree/410b92bab3bc69502b43c5cc9ccdec74794870be/ATMEGA_AES_v1/ATM_AES_v1_variable_key|
| ASCAD v2 |  |  |  |  |  |  |  |  |
| DPA v2 |  |  | SASEBO GII FPGA |  |  |  |  |  |
| DPA v4.1 |  |  |  |  |  |  |  |  |
| DPA v4.2 |  |  |  |  |  |  |  |  |
| AES HD |  |  | SASEBO GII FPGA |  |  |  |  |  |
| AES HD MM|  |  | SASEBO GII FPGA |  |  |  |  |  |
| AES RD | 50000? | 3500 | 8-bit Atmel AVR | AES128 | Random delay interrupt | 1 fixed | Power | https://www.iacr.org/archive/ches2009/57470156/57470156.pdf | https://github.com/ikizhvatov/randomdelays-traces |
| AT128-N |  |  |  |  |  |  |  |  |
| AT128-F |  |  |  |  |  |  |  |  |
| CHES CTF 2018 |  |  |  |  |  |  |  |  |
| WolfSSL Ed25519 |  |  |  |  |  |  |  |  |
| μNaCl Curve 25519 |  |  |  |  |  |  |  |  |
| Curve25519 CSWAP |  |  |  |  |  |  |  |  |
| Curve25519 CSPOINTER |  |  |  |  |  |  |  |  |

## Versions
| Main dataset | Version | URL |
|---|---|---|
| ASCAD v1 fixed key | Official government release | https://www.data.gouv.fr/s/resources/ascad/20180530-163000/ASCAD_data.zip |
| ASCAD v1 fixed key | Preprocessed 700 features |  https://github.com/ANSSI-FR/ASCAD/tree/master/ATMEGA_AES_v1/ATM_AES_v1_fixed_key |
