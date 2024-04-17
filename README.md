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
    - [x] ~~Wire i2c~~
        - [x] might not even need that (dont need it)
    - [x] rework connectors
    - [x] Dip switches
    - [x] Status LEDs
- [x] Wire to Pi GPIO
    - [x] Power pins
    - [x] Pi to DSPic
    - [x] Screen connectors
    - [x] Status LEDs
- [x] Add ICSP header
    - [ ] Second header for slave core?
- [x] Add connectors for coil drivers
- [ ] Add chip protection
    - [x] Add linear regulator
    - [x] ~~I2C protection~~
    - [x] PWM protection
    - [x] ADC protection
    - [x] Check to make sure the ESD would work
- [x] Find polyfuse to use
- [x] Find capacitor value for C5
- [x] Find crystal
- [x] Find inductor 
- [x] Finalize resistor and led paring 
- [x] Add connector for other PSU

## PCB
- [ ] Test points
- [ ] Add pcb art
- [x] Assign all footprints
- [x] Proper edge cuts for hat
- [x] Grounded screw holes
- [ ] Check footprints
- [x] Connectors and ESD
- [x] USB c and power
- [x] UART
- [x] DSPic

## Parts to order for hand soldering

| Part  | Number | Link |
| ------------- | ------------- | ------------- |
| Crystal  | 1  | https://www.digikey.com/en/products/detail/kyocera-avx/KC2520Z100-000C15XXK/11610165 |
| Inductor  | 1 | https://www.digikey.com/en/products/detail/delta-electronics-components/0805CS-621EGTS/9763907 |
| Amp Connector | 3 | https://www.digikey.com/en/products/detail/molex/5015680807/1531491 | 
| External Power | 1 | https://www.digikey.com/en/products/detail/molex/5015680207/1531485 | 
| Qwiic | 1 | https://www.digikey.com/short/mfth8vvv |
| Raspi Header | 1 | https://www.digikey.com/en/products/detail/sullins-connector-solutions/SFH11-PBPC-D20-ST-BK/1990093 |
| Programming header | 1 | https://www.digikey.com/en/products/detail/samtec-inc/TD-103-T-A/1105555 | 
| Jumper | 1 | https://www.digikey.com/en/products/detail/mill-max-manufacturing-corp/342-10-102-00-591000/4455936 |
| Fuse | 1 | https://www.digikey.com/en/products/detail/littelfuse-inc/1210L500-12SLWR/12807041 |
| Dip switches | 1 | https://www.digikey.com/en/products/detail/cts-electrocomponents/208-8/20795 |