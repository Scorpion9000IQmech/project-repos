# CHAIN DRIVEN SYSTEM
---
This Project is a chain driven system, My goal was originally to design a functioning moving system so that I may practice designing, 3d printing and accounting for tolerances, moving parts as well as other factors, it was a project aimed simply at allowing me to learn, but it has become a working functioning chain driven system, it is a complete, working, moving mechanism. to put it simply it is the mechanism and parts behind a chain system as in a bicycle for example. 

###  learnt from this
1.accounting for tolerances, how sprockets and gears work, how a chain is made, a few ways of securing methods, ensuring for external forces affecting it, experimenting/redesigning, assembling multiple components/accounting for how they would come together and finally reducing material usage without sacrificing durability.

2.accounting for 3d printer limitations such as, print bed misalignment, the filament extrusion width compared to components so that I dont create difficult edges or surfaces to print, supports, strength needed for certain components/infill and accounting for where I may need supports to protect important small protrusions of a component

3.I also learnt soldering for the purpose of my motor as it was poorly done and ripped off, so I learnt to solder as to remedy it. Beyond the simple project, I also considered How I may want to further improve it by adding gears hence I added extra space for a gear come the time, as for now my prototype of a chain drive system is complete.

## process of design
---
I started by designing the chain link, trying to imitate a bycyle chain, I designed the plates, the rollers, and the pins in a way that it latched on reproducably and I can extend the chain or break it if needed
---
<img width="209" height="160" alt="image" src="https://github.com/user-attachments/assets/cd0d53b7-9cfb-4b0d-91b0-97c9a336d249" />

I then designed the sprockets by learning how they are made, doing the calculations to find the size of the sprocket necessary for my chain and then improved the sprocket in a way it smoothly operates with the chain
---
<img width="343" height="553" alt="image" src="https://github.com/user-attachments/assets/7f0901c8-06bd-4158-b819-473f3c00ca7e" />

I also designed the shafts so it spins, but can lock the sprockets into place along with accounting for any gears or additional systems I may want to add in the future but never ended up doing, it also had a hold in its back and a place to latch the motor to the shaft so it does not seperate
---
<img width="203" height="232" alt="image" src="https://github.com/user-attachments/assets/baa977a7-96fc-4bf5-9ebc-5e210cedd282" />

the base was simply designing a place for all that to rest on the already completed system and it simply had to be redesigned a few times like for slack on the chain and attaching the two peices together since it was too large of a piece to print in one go on my 3d prineer
---
<img width="527" height="172" alt="image" src="https://github.com/user-attachments/assets/70dad351-f96a-40c8-aa41-cfe2a20b9684" />
<img width="275" height="165" alt="image" src="https://github.com/user-attachments/assets/bf73f26f-71dd-4956-96c2-d40e05537d05" />
<img width="911" height="517" alt="image" src="https://github.com/user-attachments/assets/064acceb-e14a-4ce9-8f36-cc825b22ac3f" />

## ASSEMBLY
---
#### 1.the base componet simply has a pin and hole which can be inserted

#### 2.insert 608 bearings tightly into the two holes on the base

#### 3.the shaft is designed to be inserted into the bearings and the shaft has a extruding peice to stop at the right length

#### 4.the hole in the back of the shaft on the other side of the bearing is for the motor which for me has a 6.5mm rod, I then used a C clip attached to a larger/smaller C clip for which there is a groove in the shaft

#### 5.insert the smaller sprocket into the base componet 2 shaft and larger for componet 1

#### 6.for the chain there are two hole sizes for the plates, the smaller hole size is on the outside, so insert the pin into the smaller one then the larger one, insert a roller, insert another larger one and then another smaller one, closing it with a C clip that latched into the groove on the opposite end

#### 7.continue this on either side with the same pattern to lengthen the chain

## BOM

| Item | Quantity | Unit Cost (USD) | Total Cost (USD) | Link | Notes |
|------|----------|-----------------|------------------|------|-------|
| Bearings | 2 | 0.35 USD give or take | 0.7 USD | I aquired it in person from a shop | Not greatly expensive just need to make sure its 608 so it fits properly and make sure it is put in while the filament is hot because its a tight fit |
| PLA Filament (3D Printed Parts) | 1 | 1.953 USD | 1.953 USD | Estimated filament usage is 279 grams and this much money |
| Motor | 1 | 12 USD without shipping | 12 USD | [Amazon](https://www.amazon.com/12-24V-Electric-RS-550-Torque-Screwdriver/dp/B07QDNPWKR) | You will need to buy a sleeve coupler or any coupler that is 6mm in diameter on the outer edge to fit the hole on the pin|
| 12V Li-ion Battery Pack with integrated power with switch/turning knob( battery/switch repurposed from another household item) | 1 |---|---|---| depends on what you choose to use instead, I suggest any battery pack(12V) with a simple sliding switch, I personally repurposed another battery with an already attached turning knob |
| sliding switch(in case) | 1 | 2.35-2.2 USD | 2.35-2.2 USD | [Ali Express](https://ar.aliexpress.com/item/1005009128381048.html?spm=a2g0o.productlist.main.3.5f676f775YqlFz&algo_pvid=c2ee822d-6409-4d4b-9415-97dccd72e0e4&algo_exp_id=c2ee822d-6409-4d4b-9415-97dccd72e0e4-2&pdp_ext_f=%7B"order"%3A"967"%2C"spu_best_type"%3A"price"%2C"eval"%3A"1"%2C"fromPage"%3A"search"%7D&pdp_npi=6%40dis%21OMR%211.709%210.855%21%21%2129.26%2114.63%21%402140e67317774133058863937e708f%2112000048014276276%21sea%21OM%216453760668%21X%211%210%21n_tag%3A-29911%3Bd%3A74d2ffa1%3Bm03_new_user%3A-29895&curPageLogUid=8lLYBw9yebYk&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005009128381048%7C_p_origin_prod%3A&gatewayAdapt=glo2ara)
