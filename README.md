# Shadow on the Sun

Minmaxxing cost vs mach #.


<img width="3296" height="2547" alt="00 - Shadow on the Sun - Main(2)" src="https://github.com/user-attachments/assets/c34b5564-d0d3-46f3-9347-4a64dce577e8" />

After a succesful static fire of an experimental K motor, I'm planning to build a flight vehicle using the same motor architecture. This vehicle is based off my previous rockets, with various optimizations and features to survive the flight profile.

### Aerostructures:

<img width="3296" height="2547" alt="04 - Fins(1)" src="https://github.com/user-attachments/assets/f05a769d-ed04-4a7a-b6f3-ac8aac6a20ef" />

The nosecone will be a 5 part molded fiberglass nosecone made from 5 layers of fiberglass. The mold should compress the nosecone to a consistent  thickness of .065". .01" of trowelable ablative (https://ntrs.nasa.gov/citations/20080012391) will be applied, but with a slightly altered mix ratio in order to get an appropriate viscosity to be used in the compression mold. 

The nosecone tip should be approx. .005" oversize compared to the nosecone surface it will connect to in order to prevent delamination. The same goes for the nosecone base and casing.

The fins will be 3.5mm quasi-isotropic carbon fiber cut by CNCmadness. The first half of the fin will be slotted and a phenolic leading edge will be bonded to it as ablative. The phenolic and carbon fiber on the fins will be beveled using a table saw, creating perfect bevels. 

### Motor: 

<img width="3296" height="2547" alt="03 - Casing(14)" src="https://github.com/user-attachments/assets/bb68e10e-c75c-49fb-8211-78e042962508" />

The motor will be a similar architecture to the one I static fired previously. An RCS 54mm nozzle will be potted on the aft end, and the forward closure will use an injected joint. With 1.375" of bond length, the motor's bonds have a safety factor of 6.8 at 800 psi.

The motor uses AeroTech PropX propellant, in a 6 grain configuration. There is 26.75" of liner, made from electrical insulation tubing from McMaster-Carr (this has been tested by many)

### Avionics & Recovery:

<img width="3296" height="2547" alt="02 - Avionics Bay(6)" src="https://github.com/user-attachments/assets/8ac33d59-12f0-4117-99eb-0f1ac9b6c925" />

The rocket will use a structural avionics bay made from G10 fiberglass, with a Blue Raven for deployment, as well as a featherweight GPS for tracking, and a 220mhz backup radio beacon as a backup tracker. 

The rocket will use a drougeless dual deploy cable cutter setup, where the main parachute is contained in a nomex burrito by a ziptie until a cable cutter fires at the appropriate altitude to deploy.

<img width="4347" height="2950" alt="yep! drawio" src="https://github.com/user-attachments/assets/b7acca9e-d208-47de-bdae-a3d0ad170e46" />


## Links

- [CAD](https://cad.onshape.com/documents/1bd81b77a3a17cb456f82160/w/97e9ab60a16197f8eb0e4abc/e/b023c5efac3a32166d460205)
- [BOM](https://docs.google.com/spreadsheets/d/1arTK88kPIIjBrJaRMpfglK5CKIUE6MHMySPSQ8KVSww/edit?usp=sharing)

### BOM

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
| Fin Order                                                            | CNCMadness   | Carbon Fiber/G11 Fins        | QUOTE                                                                                                                      | QUOTE        |          1 | QUOTE      |
| EP420 Epoxy                                                          | InfinityBond | Fin Fillet Epoxy             | https://www.infinitybond.com/products/infinity-bond-ep-420-ns-black-non-sag-epoxy?variant=39376515104902                   | 18           |          2 | 36         |
| Infinity Bond DMA Cartridge Gun for 50 mL Adhesive Cartridges        | InfinityBond | Fin FIllet Epoxy Aplicator   | https://www.infinitybond.com/products/infinity-bond-dma-cartridge-gun-for-50-ml-adhesive-cartridges?variant=39987625230470 | 24           |          1 | 24         |
| nan                                                                  | nan          | nan                          | nan                                                                                                                        | nan          |        nan | nan        |
| nan                                                                  | nan          | nan                          | nan                                                                                                                        | nan          |        nan | Total Cost |
| nan                                                                  | nan          | nan                          | nan                                                                                                                        | nan          |        nan | 325.89     |
