# 01_RAM Memory

[RAM Memory &#128279;](https://alison.com/topic/learn/84200/topic-a)

# BIOS and CMOS: What's the Difference?

### The Basic Input-Output System (BIOS)

- BIOS stands for **Basic Input-Output System**.
- It is a type of firmware embedded on the motherboard of a computer.
- The primary function of BIOS is to:
  - Initialize and test hardware components during the startup process (POST - Power-On Self-Test).
  - Provide the operating system with a basic interface to interact with hardware.
  - Load the bootloader or operating system from storage devices.
- BIOS settings allow users to configure hardware parameters like boot priority, enabling/disabling peripherals, and setting system clock speeds.

### The Complementary Metal-Oxide-Semiconductor (CMOS)

- CMOS stands for **Complementary Metal-Oxide-Semiconductor**.
- It refers to a technology used for building integrated circuits and the small memory chip that stores BIOS configuration settings.
- The CMOS chip retains information like:
  - System time and date.
  - Hardware settings (e.g., hard drive configuration, boot order, and power management settings).
- CMOS requires a small battery (commonly called the CMOS battery) to retain its settings when the computer is powered off.

### Key Differences Between BIOS and CMOS

1. **Function**:
   - **BIOS**: Provides the software interface to initialize and manage hardware.
   - **CMOS**: Stores BIOS configuration settings and other system information.
2. **Power Dependency**:
   - **BIOS**: Does not require power to retain firmware; it is stored permanently on a ROM chip.
   - **CMOS**: Requires a battery to retain its data when the system is powered off.
3. **Storage**:
   - **BIOS**: Contains the instructions for system startup and hardware initialization.
   - **CMOS**: Stores user-configurable system settings like time and hardware configuration.

### Conclusion

While BIOS and CMOS work closely together, they serve distinct purposes. BIOS acts as the system’s initialization software, while CMOS holds configuration data required during startup. Both are crucial for a computer's boot process.
