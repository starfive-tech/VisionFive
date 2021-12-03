# VisionFive
## VisionFive hardware and softward resources
[VisionFive](https://rvspace.org/en/Product/VisionFive/Technical_Documents/VisionFive_Single_Board_Computer_Quick_Start_Guide) is a RISC-V single board computer based on the StarFive JH7100 SoC.

## How to get VisionFive?
  Please follow the [Sales Registration Page](https://forum.rvspace.org/t/how-to-purchase-visionfive/37/4)

### Hardware
  TBD, we will release hardware design soon.

### Software
  * [secondBoot](https://github.com/starfive-tech/JH7100_secondBoot) first stage bootloader
  * [ddrinit](https://github.com/starfive-tech/JH7100_ddrinit) ddr initialization and carry opensbi+uboot
  * [OpenSBI](https://github.com/starfive-tech/opensbi) version 0.9
  * [U-Boot 2022.01-rc2](https://github.com/starfive-tech/u-boot) maintained by [Wei Fu](https://github.com/tekkamanninja)
  * [StarFive Freelight U SDK](https://github.com/starfive-tech/freelight-u-sdk)
  * [Linux Kernel, visionfive](https://github.com/starfive-tech/linux/tree/visionfive) currently 5.16-rc, maintained by [@esmil](https://github.com/esmil/)
  * [Linux Kernel, visionfive-5.15.y](https://github.com/starfive-tech/linux/tree/visionfive-5.15.y) 5.15 LTS version，maintained by [@esmil](https://github.com/esmil/)
  * [Fedora RISC-V image](https://github.com/starfive-tech/Fedora_on_StarFive) by [Wei Fu](https://github.com/tekkamanninja)
  * [recovery binary](https://github.com/starfive-tech/bootloader_recovery) used for bootloader recovery
  * [bootloader recovery utility](https://github.com/kprasadvnsi/JH71xx-tools) by [@kprasadvnsi](https://github.com/kprasadvnsi)
 
### Wiki and Tutorials
  * Please refer to [RVspace Wiki Page](https://rvspace.org/)
    * [VisionFive Quick Start Guide](https://rvspace.org/en/Product/VisionFive/Technical_Documents/VisionFive_Single_Board_Computer_Quick_Start_Guide)
    * [VisionFive Software Technical Reference Manual](https://rvspace.org/en/Product/VisionFive/Technical_Documents/VisionFive_Software_Technical_Reference_Manual)
    * [StarFive 40-Pin GPIO Header User Guide](https://rvspace.org/en/Product/General/StarFive_40-Pin_GPIO_Header_User_Guide)
    * [VisionFive vs StarLight](https://rvspace.org/en/Product/General/StarFive_Board_Guide_StarLight_vs_VisionFive)

### Technical Documentation
 * [StarFive JH7100 SoC datasheet](https://github.com/starfive-tech/JH7100_Docs/blob/main/JH7100%20Data%20Sheet%20V01.01.04-EN%20(4-21-2021).pdf)
 * [SiFive U74 core manual](https://github.com/starfive-tech/JH7100_Docs/blob/main/vic_u7_manual_with_creativecommons.pdf)
 * [Memorandum - L2 Cache Coherence](https://github.com/starfive-tech/JH7100_Docs/blob/main/JH7100%20Cache%20Coherence%20V1.0.pdf)
 * [SiFive E24 core manual](https://github.com/starfive-tech/JH7100_Docs/blob/main/SiFive%20VIC_E24%20Manual.pdf)
 * [SiFive E24 user guide](https://github.com/starfive-tech/JH7100_Docs/blob/main/SiFive%20VIC_E24%20User%20Guide.pdf)
 * [StarFive JH7100 SoC Boot User Guide](https://github.com/starfive-tech/JH7100_Docs/blob/main/JH7100%20SoC%20Boot%20User%20Guide-V01(2021-6-7).pdf)

### Community
  * [RVSpace.org](https://rvspace.org), forum for discuss RISC-V and VisionFive.

### License
  * [CERN-OHL-P (permissive)](https://ohwr.org/cern_ohl_p_v2.txt)
  * More information on [CERN Open Hardware License (OHL) v2](https://ohwr.org/project/cernohl/wikis/home)
