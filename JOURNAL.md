# hack club highway project 1: the cold brew express - a diy electric scooter to take me to dunkin'
_can i get a medium raspberry watermelon refresher with sparkling water instead of green tea?_

start date: 5/14/2025

total time spent so far: 23 hrs

# entry 7 (6/8/25)
## parts received!

parts have been received for the cold brew express! i'm printing all the 3D printed stuff as I type this -- the last thing to do is to go to home depot and get some plywood, then construct! 

there have been some errors in my planning -- the suspension fork I bought does not have any spring force and also isn't hollow at the top. it's also a little smaller than i expected. i will try to get around that. i wired up the wheel and it seems to work pretty well! the battery works great and the wheel is indeed pretty fast, with high torque. 

*time spent for this session: 2 hrs*

# hack club highway journal entry 6 (5/18/25)
## cad is done!

![image](https://github.com/user-attachments/assets/7f137751-45b0-483e-bb49-27f31a800087)

i believe i've cadded the entirety of the main frame of the scooter! yes, i haven't added things like the throttle but these are the parts that are added to the scooter later as accessories.
wiring will be taped down the side of the handlebar with electrical tape and routed through the hole in the neck between the head tube and the base.

here's what the internals look like:

![image](https://github.com/user-attachments/assets/3bebbeaa-2e9e-4d9b-9dad-08d86f7ce169)

inside are the battery and controller, which will be mounted in foam. the wires for the motor (rear) will likely be routed through a drilled hole between the rear motor fork and the base, or through the bottom of the base. i've decided that once i start putting the scooter together, i'll decide on things like that.

in the front is a suspension fork that will give the scooter a smoother ride. the display will be a standard 4 line character LCD instead of a full-fledged TFT display since i realized i will need to work with some extremely complicated electronics that i don't have the experience for at the moment. the arduino will also be mounted in the bottom of the scooter. i'm going to need some long ass jumper wires LMFAO

i still don't know how fast the scooter will get, but i'm hoping that it will do 15mph. i'm legally bound to go under 20mph anyways

i'll now be submitting this to the hack club overlords and going off to continue my neighborhood game! i should add that i'm not very experienced with cad and have only in the past imported existing gobilda files and just mated them all together with a minimally designed chassis :sob:

# hack club highway journal entry 5 (5/17/25)
## cad almost done

the CAD is almost done! i ran into a few problems that i've fixed:
- the handlebars are not sized to align with the fork (OD 30mm). i fixed this by custom-creating my own 3D printed "clamp" that will just be superglued to the fork. since i have no interest in folding up the scooter, this will work fine
- ![image](https://github.com/user-attachments/assets/94a2a339-0de7-4925-91de-6de63c0e34b5)
- i've realized that i needed to CAD the dashboard with the display.

# hack club highway journal entry 4 (5/17/25)
## it's coming together!

![image](https://github.com/user-attachments/assets/bb163a51-e082-4fea-97b2-98c2637f1958)

as you can see, i've designed many of the parts for the scooter, including the fender and neck / head tube for holding the handlebars. i will purchase a clamp separately to ensure that the handlebars can only turn left-right and cannot move up and down. the last thing i will need to CAD is the suspension fork and then i'll be all set! since i don't know how to produce these parts and i don't necessarily have access to machining tools (my robotics team has a CNC but i don't know how to fabricate the parts more complex than just sheets of metal) i'll be 3D printing them since i'm more familiar with that. 

wires will be fed from my various accessories through the crossbar in a separate tube into the deck. and i will need to secure everything using foam for the interior electronics, screws, and lots of flex seal.

from end to end the scooter is approximately 3.5 ft (1075mm) long and 3 feet (900mm) tall. i came to this value through research on what the typical scooter looks like. i think that i might be able to actually submit this for review after tonight since much of the work is done after the design has already been submitted!

# hack club highway journal entry 3 (5/17/25)
## cad updates + more!

![image](https://github.com/user-attachments/assets/2999456b-8d38-42ac-99ac-2df16af9d259)

i haven't cadded any special parts yet, like suspension, forks, etc. i think i'll forgo the suspension because apparently all the easy-to-attach suspension forks are for 10-inch wheels, and this scooter is going to have 8-inch wheels. i'll use PVC pipe instead of metal since it's easier to work with.
the part of the deck that the rider stands on is bolted to the battery and controller holder with eight 4mm gobilda screws. i hope this will be enough support.

i've learned that handlebars are angled approx. 83 degrees to the ground, so i have it turned that way.

also, i think i'll actually be 3d printing some parts, such as the fenders for the wheels. i just need to buy some flex seal to waterproof it. i might need to cad forks too, but then my concern is that the forks are not strong enough when 3D printed -- i don't have machine shop knowledge to make custom aluminum forks for my scooter.

i have a full weekend to work, so hopefully i can finish the design soon and get building!

# hack club highway journal entry 2 (5/16/25)
## APPROVED!!
the cold brew express has been approved! i just need to send in a design before i receive my parts. i will get more highway points if i make a project that actually drives!!

i've changed the BOM and feature list to better reflect my hardware knowledge + exact parts i will be getting:
- 36V 500W brushless DC hub motor with wheel and tire included: $104
- 36V 500W motor controller: $35
- 36V 10 amp-hour lithium-ion battery with 30A BMS: $94
- front free-turning wheel and tire: $30
- accessories (i.e. throttle, brake, switches, buttons): about $25
- wires and connectors: about $10
- led 2/4 line display: $10
- rgb light strip/lights: $15
- plywood base: $20
- pvc tubing / wheel forks: $30

i've also begun to create an onshape CAD file for the scooter. i've consulted diagrams of other commercial scooters on the market for inspiration. also many of the parts i'm using have little documentation and no cad files, so i have to make or represent my own objects. here's a picture so far:

![image](https://github.com/user-attachments/assets/b05c78d9-b11b-47cf-ad97-f4d6f91caa09)

no handlebars yet. i am currently hollowing out the bottom of the deck of the scooter so that it can hold the motor controller and battery. 

# hack club highway journal entry 1 (5/15/25)
## introducing the cold brew express: an extremely overengineered custom e-scooter that lets me go get coffee whenever i want!

my goal is to create a modernized e-scooter that is powerful enough to travel 10+ mph and lasts long enough for me to make the 2.5 mile trip to the nearest dunkin’ and back. it will be similar to lime/bird scooters that you find in cities, except it will have some crazy features, including but not limited to the below (i anticipate that i won’t be able to do about half of these due to time/budget constraints):

- automatic start up to cruising speed upon kick off the ground  
- speed controlled via two buttons on either side of the handlebars. press the throttle on the right side to accelerate, press left side to brake  
- press a button to toggle cruise control. during cruise control, an IMU detects for if the scooter is leaning and disengages the autopilot for safety purposes  
- bright LED lights on the front, back, deck, and handlebars of the scooter for riding at night. deck lights will be RGB and controlled by a microcontroller :)  
- telemetry readings all over the scooter, taking data like temperature, speed, battery, miles, etc, fed to an LED/OLED display located on the front driven by an ESP32 microcontroller  
- camera module w/sd card to record trips on the scooter  
- bluetooth support to play music to my airpods directly from the scooter  
- ability to wirelessly charge my phone on the dashboard  
- tactile feedback - handlebars vibrate when braking/accelerating  
- cup holder for dunkin  
- GPS???  

## rough BOM:

- 500-750w brushless hub motor: $70  
- front wheel (rear wheel is attached to the hub motor): $25  
- esc (flipsky vesc 4.2): $50  
- battery pack w/charger (36/48v, 7 ah): $80  
- esp32 CAM microcontroller w/ IR filter ($10)  
- 4 inch display ($15)  
- LED lights (strips + light for head/tail) $20  
- vibration motors ($5)  
- IMU sensor (LSM6DSOX or MPU6050 or BNO055) about $10  
- microsd: $10  
- wireless charging module: $10  
- housing  
- plywood base $20  
- aluminum tubing for support columns and handlebars: $25  
- wires, connectors, switches, nuts, bolts, etc: $20  

**TOTAL: $370\***

\*i fully intend to pay surplus costs out of pocket because i think the cost of this project will exceed $350

as you can see some of these parts are a little pricey… even the core necessities of the scooter cost more than the normal project budget of $150, hence why i believe this falls under the advanced project category.

## design plan:

- research parts and draw inspiration from real electric scooters. identify common escs/batteries/motors for scooters like this one  
- CAD chassis in onshape (plywood deck, aluminum tube supports, handlebars, component layout). ensure parts fit inside enclosure and draw diagrams  
- ensure parts are compatible with each other. voltage compatibility between battery, esc, motor, sensors, and microcontroller, and communication compatibility between sensors and microcontroller  
- design interior layout so that the ESP32 is at the front (hence its camera can be utilized)  

## build plan:

- mechanical assembly. CNC plywood deck, assemble aluminum tubing, drill necessary holes, put enclosure together for the most part, install wheels and hub motor.  
- electrical assembly: lights  
- microcontroller system: wire up microcontroller, connect to various sensors, SPI protocol, configure display, etc  
- features: configure camera to save video clips to sd card, record trip stats, control special lighting, wireless charging, etc  
- weatherproofing: seal enclosures with silicone  
- finally paint the entire thing so that it sports a nice orange and purple color scheme, after my favorite coffee chain :) throw some stickers on and personalize it  
- test ride!! and then take it to dunkin for a nice iced coffee on a hot summer day  

## challenges:

- materials materials materials. metal is expensive and i need to figure out how to optimize the cost of materials for this project without building something dangerous. i’m leaning towards a strong plywood for the base board and metal support bars/steering column for stability. my FTC robotics workshop has a CNC machine that I can use to cut my parts.  
- deciding what motor to use (a BLDC for sure), and figuring how to manage an ESC (i’ve only ever worked with brushed motors)  
- figuring out suspension. i did some research and apparently some scooters don’t have a suspension? but also that using springs to damp some impacts provides for a smoother ride experience  
- i’m not very experienced with electrical work at this level – a vehicle that is powerful enough to carry a human will require an energy current of several amps (or more!) and the battery capacity will need to be ample. good thing my dad is an electrical engineer  
- figuring how how to accel curves so that when starting up and braking i am not thrown off the scooter (this would be very bad)  
- i live in new england ☠️ so i need to make sure the scooter doesn’t explode whether it’s 0 or 100 degrees (F) outside  
- waterproofing the housing so that the scooter is resistant to rain  
- according to massachusetts law i must ride the scooter at a max speed of 15 mph and i need a learner’s permit or a license (whoops im 18 and dont have my license yet 💀)  

i have past experience building robots for FTC and science olympiad – this is taking my love for motorized things to the next level :). it is now 3:30 am and i will sleep because i have school tomorrow.
