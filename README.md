# Just a list of embedded boards with AI/ML accelerators

### Boards with ARM Ethos NPUs

#### Available now
- Grove Vision AI Module V2
  - MCU: WiseEye2 HX6538 (2 x ARM Cortex-M55 & Ethos-U55)
  - Supports TensorFlow and PyTorch frameworks
  - Price: ~16 usd  [Seedstudio](https://www.seeedstudio.com/Grove-Vision-AI-Module-V2-p-5851.html)
 
- Alif Semiconductor AK-E7-AIML
  - MCU: Ensemble E7 (2 x ARM Cortex-A32, 2 x ARM Cortex-M55 & Ethos-U55 NPU)
  - Supports TensorFlow light
  - Price: ~250 usd [Arrow](https://www.arrow.com/en/products/ak-e7-aiml/alif-semiconductor)

- NXP MCIMX93-EVK
    - MCU: i.MX93 (1-2 x ARM Cortex-A55, 1 x ARM Cortex-M33, Ethos-U65 NPU)
    - Price: ~622 usd [NXP](https://www.nxp.com/design/design-center/development-boards-and-designs/i.MX93EVK)

- MaaXBoard OSM93 Board
  - MCU: i.MX93 (1-2 x ARM Cortex-A55, 1 x ARM Cortex-M33, Ethos-U65 NPU)
  - Price: ~200 usd [AVNET](https://www.avnet.com/shop/us/products/avnet-engineering-services/aes-maaxb-osm93-dk-g-3074457345658404668/)

#### Available later
- Nuvoton NuEzAI-M55M1 and NuMaker-M55M1
  - MCU: Nuvoton M55M1 (1 x ARM Cortex-M55 & Ethos-U55 NPU)
  - Supports Google Teachable Machine platform
  - Price: Unknown
  - More info: [Nuvoton](https://www.nuvoton.com/ai/product/)

- Alif DK-B1
  - MCU: Alif Baletto B1 ( 1 x ARM Cortex-M55 & Ethos-U55 NPU)
  - Price: Unknown
  - More info: [embedded.com](https://www.embedded.com/alif-semiconductor-releases-an-evaluation-board-for-its-balletto-bluetooth-mcu/)
    
### MCUs only, no boards anounced yet
- Infenion PSOC Edge E83/E84
  - 1 x ARM Cortex-M55 & Ethos-U55 NPU, 1 x ARM Cortex-M33 & NNLite
  - Price: Unknown
  - More info: [Infenion](https://www.infineon.com/cms/en/product/microcontroller/32-bit-psoc-arm-cortex-microcontroller/32-bit-psoc-edge-arm/)


### Boards with other AI/ML Accelerators
- ESP32-S3-EYE
  - MCU: ESP32-S3 (2 x XTensa LX7 cores and PIE (Processor Instruction Extensions) for AI)
  - Price: ~45 usd [Espressif](https://www.espressif.com/en/products/devkits)
  - Multiple boards with the ESP32-S3 are available from both Espressif and other companies, it is possible to find a simple development board with a camera for ~16 usd like this [Aliexpress](https://www.aliexpress.com/item/1005006099376239.html?spm=a2g0o.productlist.main.23.3b6873c2z6Q8cS&algo_pvid=2963be0f-51e1-49de-9a64-57deb3a43ea7&aem_p4p_detail=20250104105015766303348993560000228815&algo_exp_id=2963be0f-51e1-49de-9a64-57deb3a43ea7-11&pdp_npi=4%40dis%21NOK%21166.50%21154.14%21%21%2114.28%2113.22%21%4021038df617360166158211126e22c2%2112000035736382712%21sea%21NO%21161859955%21X&curPageLogUid=rBh3zc2wl0nh&utparam-url=scene%3Asearch%7Cquery_from%3A&search_p4p_id=20250104105015766303348993560000228815_3)

- Seeed Studio XIAO ESP32S3
  - MCU: ESP32-S3 (2 x XTensa LX7 cores and PIE (Processor Instruction Extensions) for AI)
  - Price: ~7 usd [SeedStudio](https://www.seeedstudio.com/XIAO-ESP32S3-p-5627.html)
 
       
- ESP32-P4-Function-EV-Board
  - MCU: ESP32-P4 (1 x 32-bit RISC-V (up to 400MHz), 1 x 32-bit RISC-V (up to 40MHz) and PIE (Processor Instruction Extensions) for AI))
  - Price: ~60 usd [Espressif](https://www.espressif.com/en/products/devkits)
    

> NOTE: The Espressif AI accelerator PIE has different capabilities on the ESP32-S3 and the ESP32-P4 boards. Espressif documented the changes in their blog: [Espressif](https://developer.espressif.com/blog/2024/12/pie-introduction/) 


- NUCLEO-N657X0-Q
  - MCU: STM32N657X0 (1 x ARM Cortex-M55 and ST Neural-ART Accelerator)
  - Price: ~55 usd [ST](https://www.st.com/en/evaluation-tools/nucleo-n657x0-q.html#overview)
 
- STM32N6570-DK
  - MCU: STM32N657X0H3Q (1 x ARM Cortex-M55 and ST Neural-ART Accelerator)
  - Price: ~185 usd [ST](https://www.st.com/en/evaluation-tools/stm32n6570-dk.html#overview)

- 01Studio CanMV K230 Development Board
  - MCU: CanMV K230 (1 x 64-bit RISC-V (up to 1.6GHz), 1 x 64-bit RISC-V 800 MHz and KPU (Knowledge Process Unit) AI accelerator)
  - Price: ~55 usd [Aliexpress](https://www.aliexpress.com/item/1005007573129445.html)
 
  
- MAX78000FTHR
  - MCU: Analog Devices MAX78000 (1 x ARM Cortex-M4 & In-house Neural Network Accelerator)
  - Price: ~28 usd [Analog Devices](https://www.analog.com/en/products/max78000.html#evaluation-kit)
 
- Arduino Nicla Voice
  -  MCU: nRF52832 (1 X ARM Cortex-M4), Syntiant NDP120 (1 x ARM Cortex-M0, 1 x Syntiant Core 2 Neural Decision Processor)
  -  Price: ~70 usd [Arduino](https://store.arduino.cc/products/nicla-voice)

-  AVNet AES-RASYNB-120-SK-G
    -  MCU: Renesas RA6M4 (1 x Cortex-M4), Syntiant NDP120 (1 x ARM Cortex-M0, 1 x Syntiant Core 2 Neural Decision Processor)
    -  Price: ~100 usd [Avnet](https://www.avnet.com/wps/portal/us/products/avnet-boards/avnet-board-families/rasynboard/)

-  SYNTIANT TINYML
    -  MCU: Syntiant NDP101 (1 x ARM Cortex-M0, 1 x Syntiant Core 1 Neural Decision Processor)
    -  Price: ~37 usd [Digikey](https://www.digikey.com/en/products/detail/syntiant-corp./SYNTIANT%2520TINYML/15293343?utm_adgroup=Evaluation%20Boards%20-%20Embedded%20-%20MCU%2C%20DSP&utm_campaign=Shopping_Product_Development%20Boards%2C%20Kits%2C%20Programmers_NEW&utm_content=Evaluation%20Boards%20-%20Embedded%20-%20MCU%2C%20DSP&utm_medium=cpc&utm_source=google&utm_term=)
  
