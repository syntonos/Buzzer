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
![image](https://cdn.hackclub.com/019ee811-82eb-779a-a00f-b2e80f5c6b4e/image.png)
![image](https://cdn.hackclub.com/019ee812-35d9-7d58-8776-c9e3b60cae83/image.png)
![image](https://cdn.hackclub.com/019ee812-7a2b-70bb-86a9-cffce5e7fb4e/image.png)
![image](https://cdn.hackclub.com/019ee812-d8fc-77a4-9544-526289b33a74/image.png)
it's going to be held together at the top with friction from the keyswitch + the keycap, then the bottom  is held together with m2 heat inserts and screws. or just screws, because the diameter is too small and it's not like i'm going to be taking this apart often. 

![image](https://cdn.hackclub.com/019ee81f-26f4-7cbf-93bf-0e6bab001bed/image.png)
this should be ok? i just realized that i'm going to need to ship these to taiwan so the page is completely different for aliexpress ... but i'll handle it later ...