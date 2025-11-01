# Shadow on the Sun

Minmaxxing cost vs mach #.


<img width="3296" height="2547" alt="00 - Shadow on the Sun - Main(2)" src="https://github.com/user-attachments/assets/c34b5564-d0d3-46f3-9347-4a64dce577e8" />

After a succesful static fire of an experimental K motor, I'm planning to build a flight vehicle using the same motor architecture. This vehicle is based off my previous rockets, with various optimizations and features to survive the flight profile. My goal is to fly past Mach 4 and fulfill my new years resolution of doing Mach 2, 3 and 4 in a year.

### Aerostructures:

<img width="3296" height="2547" alt="04 - Fins(1)" src="https://github.com/user-attachments/assets/f05a769d-ed04-4a7a-b6f3-ac8aac6a20ef" />

The nosecone will be a 5 part molded fiberglass nosecone made from 5 layers of fiberglass. The mold should compress the nosecone to a consistent  thickness of .065". .01" of trowelable ablative (https://ntrs.nasa.gov/citations/20080012391) will be applied, but with a slightly altered mix ratio in order to get an appropriate viscosity to be used in the compression mold. 

The nosecone tip should be approx. .005" oversize compared to the nosecone surface it will connect to in order to prevent delamination. The same goes for the nosecone base and casing. I heard James Grover use this technique and I saw that it worked fairly succesfully after his flight to Mach 4.4. 

The fins will be 3.5mm quasi-isotropic carbon fiber cut by CNCmadness. The first half of the fin will be slotted and a phenolic leading edge will be bonded to it as ablative. The phenolic and carbon fiber on the fins will be beveled using a table saw, creating perfect bevels. I've used this technique before for my 3" submin diameter and I got perfectly symmetric bevels. This is super important for fast flights like this because any radial asymmetry can lead to spin and then coning or pitch roll lock in. See: https://www.youtube.com/watch?v=gmv7G6Rf5WE for an example of coning due to asymmetry (in the motor, due to the moonburner configuration), https://ntrs.nasa.gov/citations/19660015111 for an explanation of pitch roll lock in. The fin shape is loosely based on sounding rocket fins and they are only slightly swept and are very square in order to be less likley to flutter and less likley to have dynamic stability issues. 

I might swap these fins out for some G11 fiberglass. I have a more marginal fin configuration where the rocket sims to Mach 4.5 with more swept fins.

### Motor: 

<img width="3296" height="2547" alt="03 - Casing(14)" src="https://github.com/user-attachments/assets/bb68e10e-c75c-49fb-8211-78e042962508" />

The motor will be a similar architecture to the one I static fired previously. An RCS 54mm nozzle will be potted on the aft end, and the forward closure will use an injected joint.The forward closure has two O rings because I can fit redundant O rings on it, while the nozzle only has one. With 1.375" of bond length, the motor's bonds have a safety factor of 6.8 at 800 psi, and a safety factor at my MEOP of 1500 PSI. I did these calculations using a simple composite case pressure vessel design spreadsheet that I made based on simple stress calculations.

<img width="784" height="158" alt="image" src="https://github.com/user-attachments/assets/0f5c648a-1fbc-466a-a5cb-ef5712f20479" />


The motor uses AeroTech PropX propellant, in a 6 grain configuration. There is 26.75" of liner, made from electrical insulation tubing from McMaster-Carr, which has been found to be a drop in replacement for phenolic motor liners manufactured by AeroTech, but cheaper. 

<img width="1302" height="882" alt="image" src="https://github.com/user-attachments/assets/010d04d5-29b4-4988-9924-a067f51e38fc" />


### Avionics & Recovery:

<img width="3296" height="2547" alt="02 - Avionics Bay(6)" src="https://github.com/user-attachments/assets/8ac33d59-12f0-4117-99eb-0f1ac9b6c925" />

The rocket will use a structural avionics bay made from G10 fiberglass, with a Blue Raven for deployment, as well as a featherweight GPS for tracking, and a 220mhz backup radio beacon as a backup tracker. The avionics bay is placed in the nosecone because it makes retention easier, as well as  I chose these electronics because I am familiar with their use and they are reliable, and the Blue Raven has a 400G accelerometer, allowing me to get decent speed estimates past COCOM limits for GPS (1000kts). The beacon is a simple and redundant system that will be put in the main body of the rocket electrical taped to the Kevlar shock cord, and tracked with a directional receiver system, where it's louder if I point at the beacon. 

The rocket will use a drougeless dual deploy cable cutter setup, where the main parachute is contained in a nomex burrito by a ziptie until a cable cutter fires at the appropriate altitude to deploy. I've used this setup before with success, and it has been used for high altitude flights in the past. It's not my personal favorite deployment method, but with the recovery volume of the rocket being the shape it is, it's the most space efficient setup for my purpose.

<img width="4347" height="2950" alt="yep! drawio" src="https://github.com/user-attachments/assets/b7acca9e-d208-47de-bdae-a3d0ad170e46" />


## Links

- [CAD](https://cad.onshape.com/documents/1bd81b77a3a17cb456f82160/w/97e9ab60a16197f8eb0e4abc/e/b023c5efac3a32166d460205)
- [BOM](https://docs.google.com/spreadsheets/d/1arTK88kPIIjBrJaRMpfglK5CKIUE6MHMySPSQ8KVSww/edit?usp=sharing)

### BOM

IMPORTANT NOTE: The BOM cost is signifigantly lower than what the total cost will be. Shipping the propellant incurs extra fees, and signifigant fees that are not counted apply on the fins which are shipped from canada.

| Item Name                                                            | Vendor       | Justification                | Link                                                                                                                       | Unit Price   |   Quantity | Subtotal   |
|:---------------------------------------------------------------------|:-------------|:-----------------------------|:---------------------------------------------------------------------------------------------------------------------------|:-------------|-----------:|:-----------|
| 54mm Nozzle, 0.455" Throat                                           | RCS          | Rocket Motor Nozzle          | https://www.rocketmotorparts.com/product/54mm-nozzle-0-455%22-throat                                                       | 36.5         |          1 | 36.5       |
| 54mm Propellant X™ Propellant Grain                                  | RCS          | Rocket Motor Propellant      | https://www.rocketmotorparts.com/details/p1577809_18245096.aspx                                                            | 68.99        |          2 | 137.98     |
| Buna-N O-ring, 1.875" O.D.                                           | RCS          | Avionics Bay/Aft End O Rings | https://www.rocketmotorparts.com/details/p1577809_19152682.aspx                                                            | 0.35         |          2 | 0.7        |
| Buna-N O-ring, 2" O.D.                                               | RCS          | Forward Closure O Rings      | https://www.rocketmotorparts.com/details/p1577809_7801660.aspx                                                             | 0.65         |          5 | 3.25       |
| Electrical-Insulating Garolite XX Tube                               | McMaster     | Rocket Motor Insulation      | https://www.mcmaster.com/8527K247/                                                                                         | 27.71        |          1 | 27.71      |
| Multipurpose 6061 Aluminum 2" Diameter Disc                          | McMaster     | Forward Closure Stock        | https://www.mcmaster.com/1610T15-1610T116/                                                                                 | 15.97        |          1 | 15.97      |
| Multipurpose 6061 Aluminum Round Tube 1/4" Wall Thickness, 2-1/4" OD | McMaster     | Forward Retention Ring Stock | https://www.mcmaster.com/9056K16-9056K165/                                                                                 | 24.19        |          1 | 24.19      |
| Easy-to-Machine Garolite LE Sheet                                    | McMaster     | Fin Leading Edge Protection  | https://www.mcmaster.com/6842K63/                                                                                          | 19.59        |          1 | 19.59      |
| Fin Order                                                            | CNCMadness   | Carbon Fiber/G11 Fins        | QUOTE                                                                                                                      | QUOTE        |          1 | QUOTE      | nan                                                                  | nan          | nan                          | nan                                                                                                                        | nan          |        nan | nan        |
| nan                                                                  | nan          | nan                          | nan                                                                                                                        | nan          |        nan | Total Cost w/o shipping|
| nan                                                                  | nan          | nan                          | nan                                                                                                                        | nan          |        nan | 265.89     |
