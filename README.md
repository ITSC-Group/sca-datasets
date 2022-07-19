# SCA Datasets
Collection of metadata of different Side Channel Attack datasets.
If you find a new dataset, feel free to add it by creating a pull request.

## Main datasets

| Name | Traces (training / attack) | Features (original / reduced) | Device | Algorithm | Countermeasures | Keys | Aquisition | Papers | URL |
|---|---|---|---|---|---|---|---|---|---|
| ASCAD v1 fixed key | 50000 / 10000 | 100000? / 700 | ATMEGA8515 | AES-128 | 1st order XOR Boolean Masking | Fixed | EM | [JOC 2020](https://doi.org/10.1007/s13389-019-00220-8) | see versions below |
| ASCAD v1 variable key | 200000 / 100000 | 100000? / 1400 | ATMEGA8515 | AES-128 | 1st order XOR Boolean Masking | Random | EM | [JOC 2020](https://doi.org/10.1007/s13389-019-00220-8) | [github](https://github.com/ANSSI-FR/ASCAD/tree/410b92bab3bc69502b43c5cc9ccdec74794870be/ATMEGA_AES_v1/ATM_AES_v1_variable_key) |
| ASCAD v2 | 800000 | 1000000 | STM32 Cortex M4 | AES-128 | 2nd order Boolean Masking and shuffling | Random | Power | [preprint 2021/592](https://eprint.iacr.org/2021/592.pdf) | See versions below |
| DPA v1 | 80000 |  |  | DES |  | Fixed |  |  | See versions below|
| DPA v2 | 1000000/640000 |  | SASEBO GII FPGA | AES-128 | None | Random in template, 32 fixed in test | Power |  | [website](https://www.dpacontest.org/v2/download.php) |
| DPA v4.1 |  |  |  |  |  |  |  |  |
| DPA v4.2 |  |  |  |  |  |  |  |  |
| AES HD |  |  | SASEBO GII FPGA | AES-128 |  | Fixed |  |  | [website](http://aisylabdatasets.ewi.tudelft.nl/aes_hd.h5) |
| AES HD MM|  |  | SASEBO GII FPGA |  |  |  |  |  |
| AES RD | 50000? | 3500 | 8-bit Atmel AVR | AES-128 | Random delay interrupt | 1 fixed | Power | [CHES 2009](https://www.iacr.org/archive/ches2009/57470156/57470156.pdf) | [github](https://github.com/ikizhvatov/randomdelays-traces) |
| AT128-N |  |  |  |  |  |  |  |  |
| AT128-F |  |  |  |  |  |  |  |  |
| CHES CTF 2018 AES | 4x10000 / 2x1000 |  | STM32 | AES-128 |  | Fixed |  |  | See versions below |
| CHES CTF 2018 DSA |  |  |  |  | DSA | Fixed |  |  |  |
| CHES CTF 2018 RSA |  |  |  |  | RSA | Fixed |  |  |  |
| WolfSSL Ed25519 |  |  |  |  |  |  |  |  |
| μNaCl Curve 25519 |  |  |  |  |  |  |  |  |
| Curve25519 CSWAP |  |  |  |  |  |  |  |  |
| Curve25519 CSPOINTER |  |  |  |  |  |  |  |  |
| CHES Challenge 2020 fixed key |  |  | software | Clyde-128 | different ISW masking methods | Fixed | Power | [preprint 2022/471](https://eprint.iacr.org/2022/471.pdf) |  |
| CHES Challenge 2020 variable key |  |  | software | Clyde-128 | different ISW masking methods | Random | Power | [preprint 2022/471](https://eprint.iacr.org/2022/471.pdf) |  |

## Versions
| Main dataset | Version | URL |
|---|---|---|
| ASCAD v1 fixed key | Official government release | https://www.data.gouv.fr/s/resources/ascad/20180530-163000/ASCAD_data.zip |
| ASCAD v1 fixed key | Preprocessed 700 features |  https://github.com/ANSSI-FR/ASCAD/tree/master/ATMEGA_AES_v1/ATM_AES_v1_fixed_key |
| ASCAD v2 | Official government release | https://files.data.gouv.fr/anssi/ascadv2/ |
| ASCAD v2 | Preprocessed |  |
| DPA contest v1 | Attacking the SecmatV1 SoC in ASIC, used for the contest |  |
| DPA contest v1 | Attacking the SecmatV3 SoC in ASIC |  |
| DPA contest v1 | Attacking the SecmatV3 SoC in FPGA (Altera Stratix) |  |
| CHES CTF 2018 AES | Official CTF files with 42000 traces requiring google login | https://chesctf.riscure.com/2018/content?show=training |
| CHES CTF 2018 AES | Private full dataset with 500000 traces | not available |
| CHES CTF 2018 AES | Preprocessing scripts for neural networks | https://github.com/agohr/ches2018 |
| CHES CTF 2018 AES | AISYLabs version with a different subset of 45000 traces from the full 500000 trace private dataset, used in [preprint 2021/357](https://eprint.iacr.org/2021/357.pdf)| http://aisylabdatasets.ewi.tudelft.nl/ches_ctf.h5 |

