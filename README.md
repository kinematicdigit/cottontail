#Cotton Tail for ERCF

## DEVELOPMENT AND BETA!

**This is project is still underdevelopment, **please proceed with caution. I hold no responsibilities for any personal damages for the use of any of these files. Please do not modifiy or share any of the files.

Any bugs or observations, please report them to the #cotton-tail channel located at this server on discord: https://discord.gg/CATt7BUC

![](https://media.discordapp.net/attachments/1165841694273585234/1165910456683221073/394413133_10160827106300856_2289264436205624168_n.png?ex=654891ba&is=65361cba&hm=1bbe1b6bbc529e638add06c535aef12ad2c58fd5fa59339fec894c2ca8a0237b&=&width=2076&height=1492)

Cotton Tail buffer system will attach directly to the Sturdy Bunny upgraded ERCF and is designed to work with any number of filament blocks you choose (the initial test phase will go up to 9). 

The primary goal of this project was to reduce as much resistance in the path and to remove any inconsistencies in calibration. It works with Triple Decky but will work with whatever top hat/filament block design you want. In fact, there is no limitation to the design, and it also may remove the need for magnets in them altogether. There is a spring in the couplers to alleviate all pressure on the magnets.

This system is also designed to reduce the buffer length, which will help reduce friction on the entire system. There will also be optional QoL features to work with the new BTT MMB Can board.
Features:
- Large central buffer wheel - reduces the filament's natural shape - each wheel comes pre-notched to make loading filament easier.
- Inline connection - connects to the 2020 extrusion arm
- Short Buffer Length - Can operate as low as 500mm in buffer Length
- Reduced resistance - Tests up to 200 mm/s (with Galileo 2 extruder) - may do less or more depending on your extruder motor
- Improved encoder accuracy - makes all resistance more consistent for better encoder performance and less torque needed
- Stackable Arm - Each arm is stackable for whatever combination of gates you want. They are optimized for strength and weight and provide access for loading and unloading filament
- Uses most parts from ERCP -  if you already have a kit, most parts should be interchangeable.
- Filament Detector - Each coupler has a filament detector built in. This is optional and will interface with the new BTT MMB Can board. 
- Filament indicator - Future QoL option that will include the ability to light up each gate to tell you if it is loaded/active and empty/out of filament.

**BOM (subject to change) Each Arm needs:
(5-8) 8mm M3 screws
(0-1) 16mm M3 screw
(1) 25mm M3 screw
(1) Heatset (also optional)
PTFE Tubing (4mm OD/3MM ID recommended)
(1) 608 2RS Bearing (same as ERCP - skateboard bearing)
(1) ECAS
(2) M3 Hammerhead T-Nuts (for 2020 extrusions)
Optional will be
(1) BTT MMB Can board
(1) Microswitch
(1) 5.5 mm ball bearing
(2) 12mm M2 BHCS screws
(1) Button Neopixels

All the files are located in the STL folder and instructions below:

All the various parts to print, plus the optional parts for the MMB version (still underdevelopment). 
![](https://media.discordapp.net/attachments/1165841694273585234/1166559327402864740/3ACBDFDA-B7D4-4004-BF0B-E50EAFB31C6A.jpg?ex=654aee09&is=65387909&hm=875cfd432fc3a96d6faa8afc916acef6bbccdc20713cf08085ed1f5bf1cf0ea7&=&width=1990&height=1492)

**Each channel will require these
**
![](https://media.discordapp.net/attachments/1165841694273585234/1166559945559392327/IMG_6649.jpg?ex=654aee9c&is=6538799c&hm=9c2742055f2df63a0f79f44856ed78f66d5a14c02712e17de71a1af0c01af8d8&=&width=1118&height=1492)

**INSTRUCTIONS**

I recommend printing the arms at .2 layer height, with 4 walls and 10% lightning infill. This will reduce the amount of filament used by a lot. The rest of the parts can be printed with .2 layer height and 20-30% gyroid infill.


Start off with your printed channel arm by adding a 4mm deep M3 heatset installed into the back of the arm. Take care not to go too far past the channel.

![](https://media.discordapp.net/attachments/1165841694273585234/1166561293759684689/F00BC57D-E84A-4815-BBF8-64DA2912EA63.jpg?ex=654aefde&is=65387ade&hm=08bdc35eeea923c49fbd9ed99b090e794108d374da130eb86964d8f3a84d852e&=&width=1118&height=1492)

The heatset is optional as the dovetail is plenty strong.
Make sure you print the correct length axial screw. They are labelled for how many channels. They are longer than needed, in case you need to put a bypass divider or extra support. Use the matching nut and work it through the acme screw to make it smooth. A brass brush can also be used to clean it up a little.

![](https://media.discordapp.net/attachments/1165841694273585234/1166562691826077706/03CB5978-38C3-488A-B398-2204F452D71F.jpg?ex=654af12b&is=65387c2b&hm=0da278509b22ea01d22021a0aa45ddae4c7f6d433669017a782053f46bdfc8fb&=&width=1118&height=1492)

Load the axial and get the buffer wheel prepped. The 608 bearings should slide in with just a tiny bit of resistance. The flat side of the buffer wheel is what is loaded first. This is important as the filament loading holes are designed to be on the right-hand side.

|  ![](https://media.discordapp.net/attachments/1165841694273585234/1166563432158474300/7CB9A713-7055-4E55-9514-00930C308F54.jpg?ex=654af1db&is=65387cdb&hm=05682bf48e50b070b7051a8c5cbc5dd3b4052f38bef27b82e55300f968cb530a&=&width=1118&height=1492) |  ![](https://media.discordapp.net/attachments/1165841694273585234/1166563432837939351/A02FD7E0-9BDB-4D4F-BE65-BA50A2319948.jpg?ex=654af1dc&is=65387cdc&hm=2fa28c16409a1387976f122d807520bd9f47326ee32948361599a4b0440f2eb9&=&width=1118&height=1492) |
| :------------: | :------------: |
|  ![](https://media.discordapp.net/attachments/1165841694273585234/1166563433546780783/03955A03-D25D-4BAC-85CB-51AF9257F4D3.jpg?ex=654af1dc&is=65387cdc&hm=d5760c973abb4401dbe57e11425edbc17d3d052c994a63321a34e96f3aa757ee&=&width=1118&height=1492) |![](https://media.discordapp.net/attachments/1165841694273585234/1166563434318540821/7BA1B57D-1493-4D9E-90A0-0809B1D892E8.jpg?ex=654af1dc&is=65387cdc&hm=cb9fb0a623f18dce3bedc15acbd23bec98278482be93f553943c0ff95a03a828&=&width=1118&height=1492)  |

When pushing down on the axial, put your thumbs on each side of the bearing and push down with moderate force. Don't push too hard. If it doesn't go on, use a little sandpaper on the axial to reduce it. It is a tight fit but should slide on. Your pressure on the bearings will ensure the wheel is as balanced as possible. There's a very tiny bit of gap between the wheel and the side of the arm. Don't worry too much if it isn't perfect but you can try to balance it and spin it to check.

![](https://media.discordapp.net/attachments/1165841694273585234/1166566036422807642/501AC665-4C87-4F9B-BF9E-02EE1D704131.jpg?ex=654af448&is=65387f48&hm=648fdbba8d59edb812f41b0c823f684989694b0937867eefc1a41e239f2cf646&=&width=1118&height=1492)

Add spacer ring and preload M3 hammer t-nuts on M3 8mm SHCS  screws.![](https://media.discordapp.net/attachments/1165841694273585234/1166566629115691140/IMG_6650.jpg?ex=654af4d6&is=65387fd6&hm=404794e6178355b9dce1062f56811a5bee237fb31798950bc61c858a83f9ea19&=&width=1118&height=1492)

Load the mount onto the arm. Optionally you can add a M3 16mm screw to secure it.  This is completely optional.
![](https://media.discordapp.net/attachments/1165841694273585234/1166567693583908904/IMG_6652.jpg?ex=654af5d3&is=653880d3&hm=70b52f8bbdef868a77c80ff1d0e37bf9ed12a1a27fb2f5ecc8c8ef6643440984&=&width=1118&height=1492)

Squeeze the printed spring (it doesn't matter which way) and slide into the slot on the sloped side.
 ![](https://media.discordapp.net/attachments/1165841694273585234/1166568671204888596/IMG_6653.jpg?ex=654af6bd&is=653881bd&hm=fb12bcfa2adb8d3f501981e8632aaa37dd005f5b0466eb5fffeb34896d87dc1f&=&width=1118&height=1492)
 
 ![](https://media.discordapp.net/attachments/1165841694273585234/1166568671922106388/IMG_6654.jpg?ex=654af6bd&is=653881bd&hm=4a9a488689e897a7960f7114ab0fdd760e367dec803a9a08a4e61ec677750488&=&width=1118&height=1492) 

Add ECAS fitting in the hole. It's a snug fit.
![](https://media.discordapp.net/attachments/1165841694273585234/1166568911723044895/IMG_6655.jpg?ex=654af6f6&is=653881f6&hm=85300ae26aa64c36958a8da428391baffac58722e81088e360727d9808782044&=&width=1118&height=1492)

The coupler block will fit right onto the pins on the arm and push fit.
![](https://media.discordapp.net/attachments/1165841694273585234/1166569795395797022/IMG_6658.jpg?ex=654af7c9&is=653882c9&hm=27dbb7f43be6c9083e5d76186b036d6be1e301e9319943b21d5852b60dd3953a&=&width=1118&height=1492)

Repeat the process until all gates are loaded. When you get to the end, you will add the end cap and fix the final M3 25mm screw.  This does need the heat set to be in the last channel arm to secure.

![](https://media.discordapp.net/attachments/1165841694273585234/1166572214221557790/IMG_6660.jpg?ex=654afa09&is=65388509&hm=c8c7c16fdb9b55328cc9e0377ed0602b003543824068e6ffca8fbc81dee39632&=&width=1118&height=1492)

Secure screws into all the sides. You may optionally use just 3 screws if you like, but 6 is the recommended amount. All the screws go into an angle and are all self-tapping. Do not over-tighten or you’ll strip the plastic. 
![](https://media.discordapp.net/attachments/1165841694273585234/1166573596475408445/IMG_6662.jpg?ex=654afb53&is=65388653&hm=00c79f1a1ab782b5a365088b02000d8ccf0e88f0514f15617774aab86e2dafd0&=&width=1118&height=1492)

The next step is prepping the ERCF. If you have wiring clips, remove them and free all your wires. Line up the tnuts as best you can. Make sure you didn't wind them all the way down. The screws should have enough friction to hold them in place to make this part easier for you.
It should sit right on the shoulder and slip in. If not, jiggle it a little, and it should all mate perfectly. Grab your driver and turn and it should tighten right away. If not, back off a quick half-turn and turn the back the other way to load the nut in place. The last part is to cut 85mm of the tube or start out a little longer if you like, in case you use a different filament block than V6.3 of triple-decky.


|  ![](https://media.discordapp.net/attachments/1165841694273585234/1166575608810176532/IMG_6661.jpg?ex=654afd33&is=65388833&hm=7d6cfc7b61cf3d7b00ee9c549e4090a5f7aebe0f0942ece87f1ce9225f3c0a2f&=&width=1990&height=1492) | ![](https://media.discordapp.net/attachments/1165841694273585234/1166575898783391824/IMG_6664.jpg?ex=654afd78&is=65388878&hm=5bf0d94c3d3683103a2148c94dadd1ff409925a7031f0d9214f98d2c442cf0c0&=&width=1118&height=1492)|
| :------------: | :------------: |
|  ![](https://media.discordapp.net/attachments/1165841694273585234/1166575898783391824/IMG_6664.jpg?ex=654afd78&is=65388878&hm=5bf0d94c3d3683103a2148c94dadd1ff409925a7031f0d9214f98d2c442cf0c0&=&width=1118&height=1492)  |  ![](https://media.discordapp.net/attachments/1165841694273585234/1166578178794475520/26981E20-72F5-48BD-9927-712CA4046C2F.jpg?ex=654aff97&is=65388a97&hm=78f1f8481aad4379547d5d40a72189eef7239af00d0ed1b9585c63fc5cc73820&=&width=1118&height=1492) |

Insert the cut PTFE tube from the rear of the assembly. Push lightly in the spring and it should feed through. Line up to channel and press into the ECAS on the filament block. The rest of the tube  can be trimmed to around 10mm. Insert the cut PTFE tube from the rear of the assembly. Push lightly in the spring and it should feed through. Line up to channel and press into the ECAS on the filament block. The rest of the tube  can be trimmed to around 10mm.

| ![](https://media.discordapp.net/attachments/1165841694273585234/1166580032748146718/IMG_6668.jpg?ex=654b0151&is=65388c51&hm=10c6c057907171491a21cebb2b3ac11ead69224aac728873d5d7f6d5157185e5&=&width=1118&height=1492)  |  ![](https://media.discordapp.net/attachments/1165841694273585234/1166580033540866068/IMG_6667.jpg?ex=654b0152&is=65388c52&hm=aae3b6afe1f289e493093fc40ebe590237d7204de36c687404669f98e179040f&=&width=1118&height=1492) |
| :------------: | :------------: |
| ![](https://media.discordapp.net/attachments/1165841694273585234/1166580034748829717/IMG_6669.jpg?ex=654b0152&is=65388c52&hm=894578d9ec3d3065453bd4142875523e6b1823264c04fe9e9cf1c617a4487b47&=&width=1118&height=1492)  |  ![](https://media.discordapp.net/attachments/1165841694273585234/1166581653024546856/IMG_6670.jpg?ex=654b02d4&is=65388dd4&hm=adf671b12dc119fafaaaab0049e8d000631879b0254c324946104651b56e015a&=&width=1118&height=1492) |

To load the buffer, filament from your reverse Bowden. Try your best to work with the natural curl of the filament and feed it till you see it pop out on top. You should be able to grab it and feed it into the filament holder in the buffer wheel.

| ![](https://media.discordapp.net/attachments/1165841694273585234/1166583539542798386/IMG_6671.jpg?ex=654b0495&is=65388f95&hm=93bedc6a28d28a87139859dfc604fdc4a2ae06315aaca808c3ca69cb70625ebb&=&width=1118&height=1492)  | )![](https://media.discordapp.net/attachments/1165841694273585234/1166580034748829717/IMG_6669.jpg?ex=654b0152&is=65388c52&hm=894578d9ec3d3065453bd4142875523e6b1823264c04fe9e9cf1c617a4487b47&=&width=1118&height=1492)  |
| :------------: | :------------: |
| ![](https://media.discordapp.net/attachments/1165841694273585234/1166583541912580186/IMG_6674.jpg?ex=654b0496&is=65388f96&hm=92dc5cdbc4af929cadff86678fc66938d037a1af5cbd7832fef07cfc29609052&=&width=1990&height=1492)  |  ![](https://media.discordapp.net/attachments/1165841694273585234/1166583539542798386/IMG_6671.jpg?ex=654b0495&is=65388f95&hm=93bedc6a28d28a87139859dfc604fdc4a2ae06315aaca808c3ca69cb70625ebb&=&width=1118&height=1492) |

Turn the wheel until you see two or three rows. Below grab the filament in the holder and pull it out. Give yourself some length and feed back into the tube located there. It should feed clean through but if meet resistance it, press on the top hat to help it through. It is possible the trap in the block is preventing you from moving forward. This is actually a good thing as the trap keeps the filament from popping out of the block when it is disengaged.

|  ![](https://media.discordapp.net/attachments/1165841694273585234/1166585242660909086/IMG_6675.jpg?ex=654b062b&is=6538912b&hm=a7e1f70da27644f6b5c1ea31711d8fa50ef228248e94321a24cf2461523541a7&=&width=1118&height=1492) | ![](https://media.discordapp.net/attachments/1165841694273585234/1166585243462025236/IMG_6676.jpg?ex=654b062c&is=6538912c&hm=8537170e699333ac9ffc6a24e64b425e5bc6afe2f52adcbb42277ad009d035d3&=&width=1118&height=1492)  |
| :------------: | :------------: |
|![](https://media.discordapp.net/attachments/1165841694273585234/1166585244216987648/IMG_6677.jpg?ex=654b062c&is=6538912c&hm=4c746287c4cfe133487cc9c65edb1423b632e82385a384cbc949334529aec6c9&=&width=1118&height=1492)  |  ![](https://media.discordapp.net/attachments/1165841694273585234/1166585244951003146/IMG_6678.jpg?ex=654b062c&is=6538912c&hm=63cdd9fa9454be9187e00e98c48cabcb1d775c086cf25a594265531e41c355fd&=&width=1118&height=1492)
 |
![](https://media.discordapp.net/attachments/1165841694273585234/1166585245936660491/IMG_6679.jpg?ex=654b062c&is=6538912c&hm=e3c76bf88213eddcc9221ea91ed7ac1a73a6be620f368cd6a0f2d5fd51f3a63c&=&width=1118&height=1492)

Final thing to do is push the filament back flush to the opening so it doesn’t catch on the selector. That’s it. Load it all up and away you go!
![](https://media.discordapp.net/attachments/1165841694273585234/1166585620139884646/IMG_6680.jpg?ex=654b0685&is=65389185&hm=7568a71a55eee9097aa165998a36d50d42a99aebba1663cac728e537cc36b351&=&width=1118&height=1492)


