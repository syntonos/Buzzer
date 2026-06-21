# journal #1: schematic & pcb

![image](/Journal%20Images/log_1.1.png)
schematic ! fairly easy. most of these were parts i've already used before, so no hunting down footprints or 3d models involved. 

the design works as follow:
- up to 8 external buzzers are attached to gpio pins via jst plugs, which senses when they get pressed. the led is fixed to the color that is flashed first, so it records who was the fastest. the reset button on the main hub resets the led. 

![image](/Journal%20Images/log_1.2.png)
![image](/Journal%20Images/log_1.3.png)

- put way too much work into trying to make this smaller, but it's really limited by the footprint of the xiao esp32 and the switch. 
![image](/Journal%20Images/log_1.4.png)
![image](/Journal%20Images/log_1.5.png)

- it's done tho !!! it's beautiful

# journal #2: case & bom

main case !
![image](/Journal%20Images/log_2.1.png)
![image](/Journal%20Images/log_2.2.png)
![image](/Journal%20Images/log_2.3.png)
![image](/Journal%20Images/log_2.4.png)
it's going to be held together at the top with friction from the keyswitch + the keycap, then the bottom  is held together with m2 heat inserts and screws. or just screws, because the diameter is too small and it's not like i'm going to be taking this apart often. 

![image](/Journal%20Images/log_2.5.png)
this should be ok? i just realized that i'm going to need to ship these to taiwan so the page is completely different for aliexpress ... but i'll handle it later ...

# journal #3: case for the individual buzzer + assembling cart

![image](/Journal%20Images/log_3.1.png)

made a little case for the individual buzzers! it's just one 3d printed part, and the switch slides in. you then wrap or solder the jst wires into the pins.

pretty much done ! time to assemble a cart.

so apparently no lipo batteries ship to taiwan ! fun ! and nothing ships to taiwan for free. also fun. so 50+ % of my bom is shipping costs.

# journal #4: readme and github