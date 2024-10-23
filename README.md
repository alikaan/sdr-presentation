# EEM5524 - Advanced Communication Electronics  
## Subject: Software Defined Radio  
**Lecturer**: Assoc. Prof. Bahadır Süleyman YILDIRIM  
**Prepared by**: Ali Kaan TÜRKMEN  
**Student ID**: 1642180002  

---

## What's Software Defined Radio?

As described by the FCC (Federal Communication Commission), it is a radio that includes a transmitter where the operating parameters (such as frequency range, modulation type, or maximum output power) can be altered by making changes in software without modifying hardware. Essentially, SDR allows us to design with one hardware and make changes purely in software.

---

### Traditional Radio vs Software Defined Radio

- **Traditional Hardware-Based Radio Devices**:  
  - Limit cross-functionality.
  - Only modifiable through physical intervention.
  - High production costs, limited flexibility.

- **Software Defined Radio (SDR)**:  
  - Supports multiple waveform standards.
  - Provides a flexible, efficient, and cost-effective solution.
  - Enables multi-mode, multi-band, or multi-functional wireless devices through software upgrades.

---

## FPGA (Field Programmable Gate Arrays)

- **Definition**:  
  FPGAs contain programmable logic blocks and reconfigurable interconnects, allowing the blocks to be "wired together" like many logic gates. They perform parallel operations such as video and voice processing.

- **Advantages of FPGAs**:  
  - Flexibility to perform various tasks.
  - Faster than microcontrollers.
  - Programmable in the field.
  - Capable of parallel processing.
  - High I/O.

- **FPGA vs Microcontroller**:  
  - Microcontrollers have fixed peripherals.
  - In FPGAs, we can directly connect switches to LEDs, like designing an electronic circuit.

---

## FPGA Solutions and IP Cores

- **FPGA vs ASIC**:  
  - ASIC (Application-Specific Integrated Circuit) is designed for specific tasks and cannot be reprogrammed.
  - FPGAs are reprogrammable and flexible but costlier for high-volume production.
  - Typically, development begins with FPGA and is later converted to ASIC for efficiency in mass production.

---

## Software Defined Radio (SDR) Features

- **Reconfigurability**:  
  - Supports multiple software modules implementing different standards.
  - Dynamic configuration in both terminal and infrastructure equipment.

- **Ubiquitous Connectivity**:  
  - Compatible with network technologies via over-the-air software modules.
  - Infrastructure equipment can adjust to legacy terminals.

- **Interoperability**:  
  - Open architecture facilitates seamless third-party applications.

---

## Programmability Levels in Radio

1. **Hardware Radio**:  
   - No software changes allowed.

2. **Software-Controlled Radio**:  
   - Baseband operations and protocols implemented in software.

3. **Software Defined Radio**:  
   - Baseband processing and DDC/DUC modules are programmable.

4. **Ideal Software Radio**:  
   - Programmability extends to the RF section.

5. **Ultimate Software Radio**:  
   - Single chip with no external antenna and no operating frequency restrictions.

---

## SDR Architecture

- **Main Functional Blocks**:  
  1. RF Section (Analog hardware)  
  2. IF Section (Digital hardware)  
  3. BB Section (Digital hardware)

- **BB Operations**:  
  - Channel coding, source coding, control functionality, modem functionality, adaptive modulation schemes.

- **Object-Oriented Approach**:  
  - Hardware abstraction, software portability, API definition.

- **Parameter Approach**:  
  - General structure with configurable modules.

---

## Implementation Options

- SDR operations can be implemented with:  
  1. **ASIC**  
  2. **FPGA**  
  3. **DSP**  
  - Each has its own benefits and drawbacks.

---

## Application Examples

- **Commercial**: International connectivity, prototyping.
- **Military**: Real-time flexibility, security.
- **Civilian**: Portable command for crisis management.
- **Technologies**: Bluetooth, WLAN, GPS, Radar, WCDMA, GPRS, GSM, AM, FM.

---

## SDR Listening Example

- **Wireless Devices in Listening Mode**:  
  By using a wireless device and network tools (e.g., Kali Linux tools), we can collect data from surrounding networks.
  
- **SDR Technology in Listening Mode**:  
  SDR can be a powerful gadget for listening to RF signals. SDR devices are useful for RF product prototyping and testing.

---

## Conclusion

- With SDR, almost anything is possible within current limits.
- From hardware design to software design, SDR offers reusability, reconfigurability, and recycling.
- **Multimode Devices**: One device is adequate for various functions.
- **Cost-Effective**: Cheaper than traditional hardware approaches.

---

**Thank you!**  
Prepared by: Ali Kaan TÜRKMEN
