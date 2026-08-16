# Caixa Registradora feta amb arduino
El programa principal està a la carpeta remote és el fitxer main.ino. Els altres fitxers, són programes mencionats en el document fets servir per identificar els tags de les targetes i els números del comandament.

Les següents són totes les connexions fetes.

Aquí hi ha un video del projecte: https://youtu.be/ofhUXn1jWI4

## pins

IR receiver:
- G: GND
- R: 5V
- Y: 8 digital


RFID sensor:
- 3.3V
- RST: digital 49
- GND: gnd
- no connection
- digital 50
- digital 51
- digital 52
- SDA: digital 53


Buzzer:
- positive pin: digital 7
- negative: GND


LCD 16x2:
- VSS - GND (breadboard)
- VDD - 5V
- v0 -2 digital pwm
- RS- digital 45
- RW: gnd breadboard
- E: digital 44
- D4: 43 digital
- D5: 42 digital
- D6: 41 digital
- D7: 40 digital
- A: 5V
- K: GND


LCD 20x4:
- GND: GND
- VVC: 5V
- SDA: SDA
- SCL: SCL 

