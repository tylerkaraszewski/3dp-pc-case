<img width=400 src="https://github.com/user-attachments/assets/1c273aa4-d1d5-4e21-af01-30051f182feb">

This is a fully 3D-printable sub-6L case (in the version for the 9060XT variant).
There will be a 5070FE variant as well, which will be approximately 7.5L, but this is not yet available.

# System Component Requirements
1. This case is designed particularly around the [HDPlex 500W GaN PSU](https://hdplex.com/hdplex-500w-gan-aio-atx-power-supply.html).
This is not a standard sized PSU and so far as I know, there are no other PSUs that will fit aside from possibly some of the other
smaller HDPlex models. __This is the strictest component requirement in this list.__
2. The design targets the [PowerColor Radeon 9060XT 16GB GPU](https://www.powercolor.com/product-detail248.htm). It may also work with
other 2-slot GPUs up to 205mm in length, but I make no guarantees. The intention is to provide an Autodesk Fusion project that will allow
for user adjustments to length, depth, and height, but that is not yet available.
3. [This particular PCIe riser cable will fit.](https://www.amazon.com/LINKUP-RTX5090-Compatible-Designed-Reverse/dp/B0DPVMSBBW?pd_rd_w=WZtsl&content-id=amzn1.sym.ef8687d6-a5c9-462d-bf15-2b003652688f&pf_rd_p=ef8687d6-a5c9-462d-bf15-2b003652688f&pf_rd_r=6SY06311MCWA3WQNXGPQ&pd_rd_wg=wdk7x&pd_rd_r=1530de79-65b3-49e3-9d2e-52eea0201167&pd_rd_i=B0DPVMSBBW&th=1)
Use any other riser cable at your own risk.
4. [This is the target CPU cooler for this build.](https://www.thermalright.com/product/axp90-x53-full/) but any CPU cooler under 55mm should fit.

Any mini-ITX motherboard, CPU and RAM should be fine.

# Additional Parts Requirements
1. You need one bag of [these heat set inserts](https://www.amazon.com/Threaded-Inserts-Soldering-Printed-Materials/dp/B0D7M3LJDL?pd_rd_w=WZtsl&content-id=amzn1.sym.ef8687d6-a5c9-462d-bf15-2b003652688f&pf_rd_p=ef8687d6-a5c9-462d-bf15-2b003652688f&pf_rd_r=6SY06311MCWA3WQNXGPQ&pd_rd_wg=wdk7x&pd_rd_r=1530de79-65b3-49e3-9d2e-52eea0201167&pd_rd_i=B0D7M3LJDL&th=1) ()M3x4x5 size).
You only need about 40 of these. One bag is enough to make three cases.
2. The case is designed around [this power switch](https://www.amazon.com/dp/B08QV4CWYW?ref=ppx_yo2ov_dt_b_fed_asin_title).
I may make alternate front panels for a different size power switch to allow for options here, but so far those are not available.
3. You need a variety of M3 screws.<br>
  Flathead: 6mm x 12. 8mm x 10. 12mm x 12. (McMaster: [6mm](https://www.mcmaster.com/91294A126/), [8mm](https://www.mcmaster.com/91294A128/), [12mm](https://www.mcmaster.com/91294A132/))<br>
  Panhead: 8mm x 10. (Mcmaster: either [hex](https://www.mcmaster.com/91239A113/) or [phillips](https://www.mcmaster.com/92005A118/))<br>
  [This Amazon kit](https://a.co/d/0OQjD8p) probably has everything you need.

4. WIRE FOR POWER SWITCH (TODO)
5. Printer filament of your choice. The example prints shown here were done in PETG-CF, but I have made plenty of test prints in PLA and they
seem to have worked fine, even with the heat of the PSU, but I don't guarantee anything.

# Tool Requirements
1. Appropriate screwdrivers and allen keys. I will not enumerate these here. I assume anyone skilled enough to attempt this project owns a
screwdriver or two.
2. Soldering iron. This is to set the heat set inserts, there is no soldering required electrically in the case.

# Printing Instructions
This is not a 3D printing tutorial. If you are completely new to 3D printing, I suggest getting used to your printer with some objects from the
internet. Note that this project requires printing relatively large flat pieces which can be difficult if your bed is out of level or has adhesion
issues, so make sure that's sorted before you begin.

## Download the Zip File of Your Choice
Currently there is [only one](https://github.com/tylerkaraszewski/3dp-pc-case/blob/main/9060XT_case_v94.zip).

The 9060XT variant requires a printer bed size of 201x222mm or larger.

__NOTE__ When printing `leftside panel` and `rightside panel` note which is which and keep track of this until assembly. The two are slightly different but close enough to be confused.

Print one of each STL in the zip file except for:
* foot 1
* foot 2
* riser bushing

Print __2__ of each of those files.

__THESE FILES ARE INTENDED TO PRINT WITHOUT SUPPORTS__

You should be able to orient all of these files to print without supports. I do use supports to print the feet, though this should not strictly be
necessary either. All other files except the feet should not need supports.

## Install the Heat Set Inserts
I will not cover _how to do this_ in detail. [There's a reasonably good guide here.](https://hackaday.com/2019/02/28/threading-3d-printed-parts-how-to-use-heat-set-inserts/) My tips as I've worked on this are:
1. Don't lift the insert into place on the tip of the soldering iron. Set it in the hole and bring the soldering iron to it. This prevents overheating the insert before you even touch the part.
2. Let the inserts cool after inserting them. They are hot and will burn you. Also, the plastic is soft and will deform until it cools.

There are five parts that need inserts set into them. These are `front beam`, `IO beam`, `top beam`, `bottom beam`, and `mobo panel`. The location of the inserts in each is as follows:

1. In the IO beam, insert two inserts either side of the power connector, from the back (the completely flat side) as shown: <br><img width=400 src="https://github.com/user-attachments/assets/6f20641e-27d3-4c74-9503-17ce9437bf7b">
2. In the front beam, insert four inserts along the inside edge of the front opening, from the front (the flat side) as shown: <br><img width=400 src="https://github.com/user-attachments/assets/6ced1c35-aea7-4567-a2e5-99bc29f77ed6">
2. In the motherboard panel, insert four inserts into the top of the raised motherboard standoffs as shown: <br><img width=400 src="https://github.com/user-attachments/assets/a1dc1851-ec54-4a60-b60b-ef3622fd1d13">
4. Then flip the motherboard panel over and install two more inserts into the remaining holes from the backside, as shown: <br><img width=400 src="https://github.com/user-attachments/assets/19ad9b42-9a8b-4a2a-a062-2fa1c6836056">
5. The top and bottom beam are more complex, with 14 inserts each, but both are done the same way.
6. Insert 4 inserts into the flat side of each of the top and bottom beams, as shown: <br><img width=400 src="https://github.com/user-attachments/assets/0920498a-79d1-430b-869d-175274ab88e1">
7. Insert 3 inserts into each short side of the top and bottom beams (6 inserts per part, 12 in total for this step), as shown: <br><img width=400 src="https://github.com/user-attachments/assets/ee9e08b3-f12a-41b7-b20f-83dc59608f0e">
8. Insert 2 inserts into each long side of the top and bottom beams (4 inserts per part, 8 in total for this step), as shown: <br><img width=400 src="https://github.com/user-attachments/assets/8d844b45-8ae6-446a-94ab-2effc89ad40a">
9. The last 3 images all show `bottom beam`. The process with `top beam` is the same, and so I will not include images of each step, but for reference, here is the final part, showing inserts on all sides. <br><img width=400 src="https://github.com/user-attachments/assets/e980ad55-88a1-46ed-970c-74218c4c463d">

# Assembly Instructions

1. Assemble the motherboard, CPU, cooler, RAM, and SSD as normal.
<br><img width=400 src="https://github.com/user-attachments/assets/4a4c2ecb-40a8-449b-a57b-667283f18e35">

2. Disconnect the end of the power connector from the PSU.
<br><img width=400 src="https://github.com/user-attachments/assets/08fb9aa5-608a-43a2-94b3-b52173e2dda2">

3. Install the power plug from the outside of the IO panel using two 8mm flathead screws.
<br><img width=400 src="https://github.com/user-attachments/assets/46606d7a-3433-417c-ab21-f7985a3d68f4">

4. Install the PCIe riser cable and bend it under the motherboard. Install the motherboard in the motherboard panel using four 8mm panhead screws.
IMPORTANT: Run the end of the power connector into the same space as the PCIe riser cable before securing the motherboard to the motherboard tray.
<br><img width=400 src="https://github.com/user-attachments/assets/3779eeea-127c-4f71-8c61-f88c795b2a9e">

5. Using two more 8mm panhead screws, attach the PCIe cable to the back of the motherboard tray. Use the two riser bushings as spacers between
the motherboard tray and the bottom of the PCIe riser cable. Pull the end of the PSU cable up alongside the PCIe riser cable.
The following three photos show this in detail.
<br><img width=400 src="https://github.com/user-attachments/assets/1857618a-7a12-4c43-a8a5-e7d4dc3a10ef">
<br><img width=400 src="https://github.com/user-attachments/assets/dba2da08-3238-4ae2-bef5-4ae87ce6f107">
<br><img width=400 src="https://github.com/user-attachments/assets/22449d0b-96fe-47ab-bf8b-16df97226816">

6. Install the GPU into the riser cable.
<br><img width=400 src="https://github.com/user-attachments/assets/6083821b-4e24-46c5-b233-60b04dee4fa4">

7. Slide the IO shield into place and slide the IO panel onto the back of the motherboard tray.
<br><img width=400 src="https://github.com/user-attachments/assets/b3024440-de5c-4d46-bfad-166fafba48dd">

8. Slide the top and bottom beams into place interlocking them with the top and bottom of the motherboard tray. Secure them in place with
six 12mm flathead screws.
<br><img width=400 src="https://github.com/user-attachments/assets/4e2d010a-3328-4953-b35a-9a260e7e6255">

9. Install the CPU, Motherboard, and GPU power cables into the PSU. There are easier to reach now. Note that the cables in this photo are
custom short cables, but you can use the stock ones as well.
<br><img width=400 src="https://github.com/user-attachments/assets/ec999144-77dc-4388-9e03-03009faf458f">

10. Plug the PSU into the power cable installed in the back of the case.
<br><img width=400 src="https://github.com/user-attachments/assets/12f15a04-88b4-4d27-802e-d8c22233b08b">

11. Slide the PSU into place and install with four 6mm flathead screws.
<br><img width=400 src="https://github.com/user-attachments/assets/6cbc94b9-becb-47c6-8c8a-b5cfcd75e9d6">

12. Attach the CPU and motherboard power cables.
<br><img width=400 src="https://github.com/user-attachments/assets/a049e028-fbbd-4159-b5e7-a0e2e644a142">

12. Attach the GPU power cable.
<br><img width=400 src="https://github.com/user-attachments/assets/fa04ccea-debc-4c4d-ab7c-2c8bff9db3ff">

13. Install the front beam using six more 12mm flathead screws.
<br><img width=400 src="https://github.com/user-attachments/assets/ac328fb5-ab98-461c-8462-ebee674ecc3d">

14. Simultaneously install both the `front panel back` and `front panel` using four 8mm flathead screws. These screws pass through both panels.
<br><img width=400 src="https://github.com/user-attachments/assets/906eca53-7f9a-47c5-b808-c84f1c6ee2ea">

15. Install the power switch through the bottom of the front panel, and secure it in place from behind with the included nut.
Plug the power switch into the motherboard.
<br><img width=400 src="https://github.com/user-attachments/assets/389566a4-349c-4ca7-8ea3-ac7c6dbab6b8">

16. Install the feet using four additional 8mm panhead screws. Note that there are two different mirrored feet, and each foot will only fit correctly in two of the four corners.
If a foot doesn't fit on one spot, try it in another.
<br><img width=400 src="https://github.com/user-attachments/assets/6fb12d9f-9f5c-4206-ac6c-ea19a820c515">

17. Simultaneously install both the `top panel back` and `top panel` using four  8mm flathead screws. Note that while `top panel back` only fits one way,
`top panel` will fit both directions but is asymmetric by 0.25mm at one end. Try it facing both directions to see which way the ends align better
(there should be a 0.25mm gap at the front of the case, and it should be flush at the back of the case).
<br><img width=400 src="https://github.com/user-attachments/assets/36b3c456-75d2-43a6-97b2-75582e17edf9">

18. Using four 6mm flathead screws, attach the `leftside panel` in front of the CPU. Like the top panel, it is asymmetric by 0.25 at the top and the front.
There should be a tiny gap along the front and top, and it should be flush with the bottom and back of the case. Rotate it 180 degrees and see which way it fits better.
<br><img width=400 src="https://github.com/user-attachments/assets/8b745a7d-ffa1-4612-90aa-240fad66d435">

19. Install the `rightside panel` in front of the GPU with the same procedure at the `leftside panel`.
<br><img width=400 src="https://github.com/user-attachments/assets/8f2ee408-9e6f-41ee-9bb2-904c7d47b936">

## All done!
<br><img width=400 src="https://github.com/user-attachments/assets/bafbff48-f467-4172-a56a-93b66d134334">
<br><img width=400 src="https://github.com/user-attachments/assets/945ced50-0dea-4dd7-bf79-38890a95689e">
