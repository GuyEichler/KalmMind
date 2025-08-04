# KalmMind

This is a repository to reference the open-source release of the KalmMind work published at the 2025 Design, Automation and Test in Europe Conference (DATE) and at the 2025 Design Automation Conference (DAC).

DATE paper:
-----------
Guy Eichler, Joseph Zuckerman and Luca P. Carloni. "KalmMind: A Configurable Kalman Filter Design Framework for Embedded Brain-Computer Interfaces." 2025 Design, Automation & Test in Europe Conference (DATE). IEEE, 2025.
[link](https://ieeexplore.ieee.org/abstract/document/10992818)

DAC paper:
----------
Guy Eichler, Joseph Zuckerman and Luca P. Carloni. "An Energy-Efficient Kalman Filter Architecture with Tunable Accuracy for Brain-Computer Interfaces" 2025 Design Automation Conference (DAC). IEEE, 2025.

General Instructions:
=====================

* The source code to reproduce KalmMind and specificially, the KalmMind-based hardware accelerators can be found [here](https://github.com/GuyEichler/esp/tree/kalman).

* KalmMind is embedded inside a fork of [ESP - the open source SoC platform](https://esp.cs.columbia.edu/).

* The source code for the accelerators can be found under:
`esp/accelerators/vivado_hls/` [link](https://github.com/GuyEichler/esp/tree/kalman/accelerators/vivado_hls)

* To synthesize the accelerators and execute on FPGA, follow the formal integration instructions given by ESP's documentation and inside the official [ESP repository](https://github.com/sld-columbia/esp).

 * For any question please contact Guy Eichler at `guyeichler@cs.columbia.edu`

 * Please reference both DAC and DATE papers in case of using the KalmMind work.
