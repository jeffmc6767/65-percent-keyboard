67% Keyboard
-
A 60-70% keyboard with a customizable oled and 2 rotary encoders. 
<img width="698" height="410" alt="Screenshot 2026-08-13 at 2 15 45 PM" src="https://github.com/user-attachments/assets/f20524ba-3a7f-4f03-a8ce-69f210e18a1d" />

Quick start
-

How can you build it yourself. 

1. Buy all the parts in the BOM (Also make sure to buy Cherry MX switches that are 3 or 5 pin) and order a PCB
2. solder everything according to the layout on the PCB
3. Install firmware by plugging in the raspberry pi pico 2wh and flashing it.
4. Customize keys in the software
5. Done!

Features:
-

1. 73 key keyboard, with 2 customizable keys
2. 2 rotary encoders for volume and brightness control(default)
3. Rotary encoders include push button
4. 1 0.91" customizable OLED screen

How it works:
-

The 73 switches and 2 rotary encoders are wired in a matrix, each with a diode to detect which key is pressed. Each switch is soldered directly to the PCB. 

The keyboard will be wireless via bluetooth, 2.4gz, and also supports USBC connection, since the raspberry pi pico2wh has wifi and bluetooth connectivity. 




Here's some images:
-

<img width="866" height="625" alt="Screenshot 2026-08-13 at 2 16 21 PM" src="https://github.com/user-attachments/assets/6804b0b5-0591-4b77-b5d8-cd5719a43496" />
<img width="746" height="425" alt="Screenshot 2026-08-13 at 2 16 12 PM" src="https://github.com/user-attachments/assets/5765c897-2979-4a33-a383-15d24a400e3d" />
<img width="723" height="347" alt="Screenshot 2026-08-13 at 1 37 29 PM" src="https://github.com/user-attachments/assets/7fdd3f21-188b-4646-87d6-6a359dfc0bfb" />

I will be using PLA matte white to print the case out (because it has no LED's) or petg white depending on what filament I have. 

ROUGH BOM: look at the BOM.csv. 

- 73x switches: $29.99(I own these already)
- 75x 1N4148 Diodes: $5
- 2x PEC11R-4220f-S0024-ND: $8.60
- 1x Raspberry Pi Pico 2WH: $21
- 1x 0.91" OLED: $9
- 1x Tin Lead Sn60-Pb40 (0.6mm, 50g): $12
- 1x PCB: $76
- 6.25U and 2.00U stabilizer: $15
