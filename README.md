<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=180&color=0:0f2027,50:203a43,100:2c5364&text=Felix&fontColor=e6edf3&fontSize=56&fontAlignY=36&desc=Embedded%20Software%20Engineer&descSize=18&descAlignY=58" width="100%" alt="Felix · Embedded Software Engineer" />

**Communication protocols on microcontrollers · Software-defined radio · RF hardware**

Heidelberg, Germany &nbsp;·&nbsp; Amateur radio callsign DM5LF

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/felix-langer-2b350122b/)

</div>

<br />

## About

I implement communication protocols on microcontrollers, from firmware to system-level verification with real measurement hardware. Before that I was an application engineer for analog ICs and PCB design, so I start with the datasheet and the physical layer.

In my spare time I build software-defined radios and take digital radio protocols apart.

<br />

## Current project

<table>
  <tr>
    <td width="38%" align="center" valign="middle">
      <a href="https://github.com/w4tchd0g/phenix-1255-sw">
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/w4tchd0g/phenix-1255-sw/HEAD/_doc/images/phenix-1255_logo_white.png">
          <img src="https://raw.githubusercontent.com/w4tchd0g/phenix-1255-sw/HEAD/_doc/images/phenix-1255_logo_transparent.png" width="200" alt="Phenix-1255 logo">
        </picture>
      </a>
    </td>
    <td width="62%" valign="middle">
      <h3><a href="https://github.com/w4tchd0g/phenix-1255-sw">Phenix-1255</a></h3>
      <p>SDR transceiver for TETRA base stations, based on the Semtech SX1255 and the NXP FRDM-MCXN947.</p>
      <p>The sample path runs on a dedicated microcontroller: timestamped I/Q samples are counted in hardware and streamed to any Linux or macOS host over HS USB or Ethernet. The firmware switches the PA off independently of the host.</p>
      <p><sub>Firmware, host software and the redesigned RF shield by me. Original board concept by Z32IT (<a href="https://github.com/labdvm/Phenix-1255-HW">Phenix-1255-HW</a>).</sub></p>
    </td>
  </tr>
</table>

<table>
  <tbody>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/w4tchd0g/phenix-1255-sw">phenix-1255-sw</a></h4>
      <p>Zephyr firmware for the FRDM-MCXN947 and a SoapySDR driver for TETRA base station software such as TETRA-BlueStation and FlowStation.</p>
      <img src="https://img.shields.io/badge/C-1f2937?style=flat-square&logo=c&logoColor=white" alt="C" />
      <img src="https://img.shields.io/badge/Zephyr_RTOS-1f2937?style=flat-square" alt="Zephyr RTOS" />
      <img src="https://img.shields.io/badge/SoapySDR-1f2937?style=flat-square" alt="SoapySDR" />
      <img src="https://img.shields.io/github/license/w4tchd0g/phenix-1255-sw?style=flat-square&color=1f2937" alt="License" />
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/w4tchd0g/phenix-1255-shield">phenix-1255-shield</a></h4>
      <p>4-layer RF shield (TX 440 MHz, RX 430 MHz) with reworked matching networks, SMA connectors and port protection. Multimode platform: TETRA today, DMR and FM planned.</p>
      <img src="https://img.shields.io/badge/KiCad_10-1f2937?style=flat-square&logo=kicad&logoColor=white" alt="KiCad 10" />
      <img src="https://img.shields.io/badge/4_layers-1f2937?style=flat-square" alt="4 layers" />
      <img src="https://img.shields.io/badge/430%2F440_MHz-1f2937?style=flat-square" alt="430/440 MHz" />
    </td>
  </tr>
  </tbody>
  <tbody>
  <tr>
    <td colspan="2" align="center">
      <a href="https://github.com/w4tchd0g/phenix-1255-shield">
        <img src="https://raw.githubusercontent.com/w4tchd0g/phenix-1255-shield/HEAD/docs/img/pcb-3d.png" width="85%" alt="3D render of the phenix-1255-shield PCB">
      </a>
      <br />
      <sub>phenix-1255-shield, 3D render of the PCB</sub>
    </td>
  </tr>
  </tbody>
</table>

<br />

## Areas of focus

<table>
  <tbody>
  <tr>
    <td width="50%" valign="top">
      <h4>Software-defined radio</h4>
      Real-time signal processing in Rust, from raw IQ samples to decoded data.
    </td>
    <td width="50%" valign="top">
      <h4>Digital voice and data modes</h4>
      TETRA, DMR and M17: protocol structure and metadata analysis.
    </td>
  </tr>
  </tbody>
  <tbody>
  <tr>
    <td width="50%" valign="top">
      <h4>Embedded systems</h4>
      Bare-metal C on ARM Cortex-M, VHDL on FPGAs, test setups for embedded targets.
    </td>
    <td width="50%" valign="top">
      <h4>RF hardware</h4>
      Design and measurement of filters, amplifiers and antennas.
    </td>
  </tr>
  </tbody>
</table>

<br />

## Technical skills

<table>
  <tbody>
  <tr>
    <td><b>Languages</b></td>
    <td>
      <img src="https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white" alt="C" />
      <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++" />
      <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust" />
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
      <img src="https://img.shields.io/badge/VHDL-1f6feb?style=flat-square" alt="VHDL" />
      <img src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white" alt="Bash" />
    </td>
  </tr>
  </tbody>
  <tbody>
  <tr>
    <td><b>Embedded & hardware</b></td>
    <td>
      <img src="https://img.shields.io/badge/ARM_Cortex--M-0091BD?style=flat-square&logo=arm&logoColor=white" alt="ARM Cortex-M" />
      <img src="https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white" alt="STM32" />
      <img src="https://img.shields.io/badge/NXP_MCX-000000?style=flat-square&logo=nxp&logoColor=white" alt="NXP MCX" />
      <img src="https://img.shields.io/badge/Zephyr_RTOS-6e40c9?style=flat-square" alt="Zephyr RTOS" />
      <img src="https://img.shields.io/badge/Xilinx_FPGA-E01F27?style=flat-square" alt="Xilinx FPGA" />
      <img src="https://img.shields.io/badge/Altium_Designer-A5915F?style=flat-square&logo=altiumdesigner&logoColor=white" alt="Altium Designer" />
      <img src="https://img.shields.io/badge/KiCad-314CB0?style=flat-square&logo=kicad&logoColor=white" alt="KiCad" />
    </td>
  </tr>
  </tbody>
  <tbody>
  <tr>
    <td><b>RF & DSP</b></td>
    <td>
      <img src="https://img.shields.io/badge/GNU_Radio-FF6600?style=flat-square&logo=gnu&logoColor=white" alt="GNU Radio" />
      <img src="https://img.shields.io/badge/SoapySDR-6e40c9?style=flat-square" alt="SoapySDR" />
      <img src="https://img.shields.io/badge/UHD_/_USRP-009cde?style=flat-square" alt="UHD / USRP" />
    </td>
  </tr>
  </tbody>
  <tbody>
  <tr>
    <td><b>Radio protocols</b></td>
    <td>
      <img src="https://img.shields.io/badge/TETRA-b45309?style=flat-square" alt="TETRA" />
      <img src="https://img.shields.io/badge/DMR-b45309?style=flat-square" alt="DMR" />
      <img src="https://img.shields.io/badge/M17-b45309?style=flat-square" alt="M17" />
    </td>
  </tr>
  </tbody>
  <tbody>
  <tr>
    <td><b>Tooling</b></td>
    <td>
      <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux" />
      <img src="https://img.shields.io/badge/macOS-000000?style=flat-square&logo=apple&logoColor=white" alt="macOS" />
      <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
      <img src="https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white" alt="CMake" />
      <img src="https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white" alt="LaTeX" />
    </td>
  </tr>
  </tbody>
</table>

<img src="https://capsule-render.vercel.app/api?type=waving&height=100&color=0:0f2027,50:203a43,100:2c5364&section=footer" width="100%" alt="" />
