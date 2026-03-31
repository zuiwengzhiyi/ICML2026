

|ID|Method|White?|Gran.|UCF-Crime (AUC)|UCF-Crime (SNR)|XD-Violence (AP)|XD-Violence (SNR)|
|-|-|:-:|-|:-:|:-:|:-:|:-:|
|M1|Memory (Raw)|❌|Inst.|81.21|1.09|70.10|1.29|
|M2|Mem. (Flash.)|❌|Inst.|82.69|1.29|71.89|1.44|
|M3|Global (Raw)|❌|Glob.|82.00|1.19|77.01|1.91|
|M4|Global (White.)|✅|Glob.|84.17|1.27|75.15|1.86|
|M5|(Multi-Axis)|❌|Scen.|85.10|1.30|79.32|2.02|
|**M6**|**PRISM (Ours)**|✅|**Scen.**|**86.07**|**1.39**|**80.86**|**2.11**|

Performance comparison using the PerceptionEncoder backbone on UCF-Crime and XD-Violence datasets



| ID | Method | White? | Gran. | AUC | AUC\_A | AP | AP\_A | SNR |

| :--- | :--- | :---: | :--- | :---: | :---: | :---: | :---: | :---: |

| M1 | Memory (Raw) | ❌ | Inst. | 91.10 | 67.68 | 69.52 | 71.90 | 1.885 |

| M2 | Memory (Flashback) | ❌ | Inst. | 91.00 | 66.38 | 68.52 | 70.56 | 1.943 |

| M3 | Global (Raw) | ❌ | Glob. | 91.16 | 66.82 | 71.17 | 72.23 | 1.934 |

| M4 | Global (Whitened) | ✅ | Glob. | 91.39 | 67.96 | 71.04 | 72.08 | 1.965 |

| M5 | Multi-Axis (Raw) | ❌ | Scen. | \*\*91.64\*\* | 68.75 | 73.49 | 74.55 | 1.999 |

| \*\*M6\*\* | \*\*PRISM (Full)\*\* | ✅ | \*\*Scen.\*\* | 91.59 | \*\*69.55\*\* | \*\*75.39\*\* | \*\*76.60\*\* | \*\*2.151\*\* |


Robustness evaluation of PRISM on the MSAD dataset under a massively mixed semantic pool								



