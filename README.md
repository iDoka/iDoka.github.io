CV
==

|               |              |
| :------------ |:-------------|
| **Name** 	    | Dmitry Murzinov |
| **Education** | M.Sc. in Radio Engineering at the Power Engineering Institute |
| **Residence** | EU |
| **Web**       | <http://idoka.ru> |
| **E-mail**    | <job@idoka.ru> |
  


PROFESSIONAL SKILLS
-------------------
***

### ASIC/VLSI

### FPGA

### Embedded



PROJECTS
--------
***

### OPENSOURCE

1. [ASIC Pinout Drawer](https://github.com/iDoka/asic-pinout-drawer) - This is easy to use pin assignment generator for IC case. Project is opensource (MIT license). Tool converting AsciiDoc pin description table to vector image (SVG format) that contains chip pinout with pin name and color coding (if needed) the type of pin for inserting into final documentation.
2. [Hamming and SECDED Verilog Generator](https://github.com/iDoka/hdl-secded-producer) - MATLAB/Octave generator of Hamming ECC coder/decoder. Output format is Verilog HDL. Optional adding atop Hamming Coding extra parity bit we have a Single Error Correction/Double Error Detection (SEC/DED) algorithm.
3. [EDA Scripts](https://github.com/iDoka/eda-scripts) - Collect of various scripts for helping work with EDA-tools (ASIC, Xilinx FPGA, etc)
4. [Verilog Implementation of the GOST 28147-89 Symmetric Cipher](http://opencores.org/project,gost28147) - a Soviet and Russian government standard symmetric key block cipher (64-bit blocksize and 256-bit keysize). This core support for following cipher modes: CBC, CFB, OFB (and CTR in future) and allows to use of S-box according to RFC4357/GOST R34.11-94 or RFC5830 (at synthesis-stage), and also S-box switch "on the fly" (realtime). This implementation provide trade off size and performance. The goal was to be able to fit in to a low cost Xilinx FPGA and still be as fast as possible.


### COMMERCIAL

1. **CAN FD IP-core** - implementation on verilog CAN Flexible Datarate (according ISO standard) with some reliable features for Industrial application (which have requirements for Safety Level)
2. **GNSS Multichannel Antijamming System** - Research and implement as part of GNSS ASIC the multichannel Supressor of Interference. The method was modeled in MATLAB in multibit fixed point and proven as well (recorded physical signal → HDL → MATLAB). An application for Pantent is submitted.
3. **226-Channel GNSS 65nm Vanguard ASIC (TSMC 65LP)** - responsible for several IPs/tasks:
  - Multichannel Digital Down Converter IP core (RTL description, Functional Verification, DC synthesis (including optimization RTL for DW-lib and DC-Ultra), STA, Power Estimation, Formal Verification, FPGA-proven stage, manufacturing tests)
  - IP cores for various legacy interfaces and units (McBSP/SPORT, UART, I2C, RTC)
  - Seamless integration IP-cores on Gaisler-edition of AMBA-bus
  - Creation and invoking know-how HW/SW co-simulation and co-verification environment
4. **Digital Modem for LEO Satellite**
  - Development Digital Modem board based on TI TMS320VC55xx DSP (functional diagram, choice of components, schematic, PCB-design (place&routing))
  - Research and Implementation of signal processing algorithms for receiving/transmiting in UHF/VHF-band in conformity with specified RF-channel energetics
  - Writing firmware for DSP (signal processing algorithms, communication protocol with host-CPU)
  - Complex debugging and field experience
  - Tools: MATLAB, TI Code Composer Studio, PCAD



PUBLICATIONS
------------
***

### PATENTS


1. [**US8509359B2** Multi-channel sequential Viterbi decoder](https://patents.google.com/patent/US8509359B2/); Inventor: Dmitry Murzinov, Timur Kelin, Dmitry Pyatkov; Priority 2010-02-27
2. [**US20150244416A1** Digital filter for narrowband interference rejection](https://patents.google.com/patent/US20150244416A1/); Inventor: Dmitry Murzinov, Victor Prasolov, Andrey Veitsel; Priority 2013-10-28
3. [**US9759753B2** Digital sweep type spectrum analyzer with up/down frequency conversion](https://patents.google.com/patent/US9759753B2/); Inventor: Dmitry Murzinov, Igor Orlovsky, Victor Prasolov, Andrey Veitsel; Priority 2014-11-18


ALAILABLE EQUIPMENTS
--------------------
***

### HW Equipment

* RF/SDR-platforms:
  * BladeRF SDR Kit
  * rtl-sdr + SAW-filters
  * CC1111-based ISM-sniffer Dongle
  * nRF24-based dongle with sniffer FW
* Logic Analyzer:
  * DSlogic16 pro
	* Saleae-clone FX2-based
* Osciloscopes:
	* Rigol DS-1052E
* Multimeters:
  * HoldPeak HP-890CN
  * HoldPeak HP4070C
* HW-sniffers for several protocols:
  * CAN-to-USB adapter
  * LIN-to-USB adapter
  * I2C-to-SPI adapter
  * SPI-to-USB adapter
  * BLE-sniffer:
    * BLE TI CC2540-based USB-dongle
    * BLE Cypress-based USB-dongle
* Others:
  * 4-ch I/V-to-USB logger


### SW Tools

* CNUradio
* MatLab
* SocketCAN, CANtoolz 
* rf-cat
* sigrok
* rtl-sdr, rtl_433
