# DSPic_Pi_Hat
A Raspberry Pi hat with a DSPic and USB.

To-do list:

## schematic

- [x] USB
- [x] UART chip
- [x] Verify chip selected 
- [ ] Wire DSPic 
    - [x] Wire dubug port
    - [ ] 1n4148 to MCLR?
    - [x] Add oscillator
    - [ ] Check oscillator
    - [x] Wire ADC pins
    - [ ] Check ADC connections
    - [x] Wire PWM pins
    - [x] Wire i2c
        - [ ] might not even need that
    - [ ] rework connectors
    - [x] Dip switches
    - [x] Status LEDs
- [ ] Wire to Pi GPIO
    - [x] Power pins
    - [x] Pi to DSPic
    - [x] Screen connectors
    - [x] Status LEDs
- [x] Add ICSP header
    - [ ] Second header for slave core?
- [x] Add connectors for coil drivers
- [ ] Add chip protection
    - [x] Add linear regulator
    - [x] I2C protection
    - [x] PWM protection
    - [x] ADC protection
    - [ ] Check to make sure the ESD would work
- [ ] Find polyfuse rating
- [x] Add connector for other PSU

## PCB
- [ ] Test points
- [ ] Add pcb art
- [x] Assign all footprints
- [ ] Proper edge cuts for hat
- [ ] Check footprints
- [x] Connectors and ESD
- [x] USB c and power
- [x] UART
- [x] DPSIC