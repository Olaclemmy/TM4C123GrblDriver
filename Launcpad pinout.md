# Tiva C \(TM4C123G\) LaunchPad pin assignments

```
                  3v3 [] [] VBUS (5v)        Step Y PF2 [] [] GND
                  PB5 [] [] GND              Step Z PF3 [] [] PB2
   Spindle enable PB0 [] [] PD0 Reset               PB3 [] [] PE0 Stepper enable
Spindle direction PB1 [] [] PD1 Feed Hold       RTS PC4 [] [] PF0
      Spindle PWM PE4 [] [] PD2 Cycle Start   Dir X PC5 [] [] RST
                  PE5 [] [] PD3 Safety Door   Dir Y PC6 [] [] PB7
    Keypad strobe PB5 [] [] PE1               Dir Z PC7 [] [] PB6
            Probe PA5 [] [] PE2               Flood PD6 [] [] PA4 Limit Z
           I2CSCL PA6 [] [] PE3                Mist PD7 [] [] PA3 Limit Y
           I2CSDA PA7 [] [] PF1 Step X              PF4 [] [] PA2 Limit Z
```
