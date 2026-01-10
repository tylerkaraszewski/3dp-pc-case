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
3. SCREWS (TODO)
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
I will not cover _how to do this_ in detail. [There's a reasonbly good guide here.](https://hackaday.com/2019/02/28/threading-3d-printed-parts-how-to-use-heat-set-inserts/) My tips as I've worked on this are:
1. Don't lift the insert into place on the tip of the soldering iron. Set it in the hole and bring the soldering iron to it. This prevents overheating the insert before you even touch the part.
2. Let the inserts cool after inserting them. They are hot and will burn you. Also, the plastic is soft and will deform until it cools.

There are five parts that need inserts set into them. These are `front beam`, `IO beam`, `top beam`, `bottom beam`, and `mobo panel`. The location of the inserts in each is as follows:

1. In the IO beam, insert two inserts either side of the power connector, from the back (the completely flat side) as shown: <br><img width=400 src="https://github.com/user-attachments/assets/6f20641e-27d3-4c74-9503-17ce9437bf7b">
2. In the front beam, insert four inserts along the inside edge of the front opening, from the front (the flat side) as shown: <br><img width=400 src="https://github.com/user-attachments/assets/6ced1c35-aea7-4567-a2e5-99bc29f77ed6">
2. In the motherboard panel, insert four inserts into the top of the raised motherboard standoffs as shown: <br><img width=400 src="https://github.com/user-attachments/assets/a1dc1851-ec54-4a60-b60b-ef3622fd1d13">
4. Then flip the motherboard panel over and install two more inserts into the remaining holes from the backside, as shown: <br><img width=400 src="https://github.com/user-attachments/assets/19ad9b42-9a8b-4a2a-a062-2fa1c6836056">
5. The top and bottomn beam are more complex, with 14 inserts each, but both are done the same way.
6. Insert 4 inserts into the flat side of each of the top and bottom beams, as shown: <br><img width=400 src="https://github.com/user-attachments/assets/0920498a-79d1-430b-869d-175274ab88e1">
7. Insert 3 inserts into each short side of the top and bottom beams (6 inserts per part, 12 in total for this step), as shown: <br><img width=400 src="https://github.com/user-attachments/assets/ee9e08b3-f12a-41b7-b20f-83dc59608f0e">
8. Insert 2 inserts into each long side of the top and bottom beams (4 inserts per part, 8 in total for this step), as shown: <br><img width=400 src="https://github.com/user-attachments/assets/8d844b45-8ae6-446a-94ab-2effc89ad40a">
9. The last 3 images all show `bottom beam`. The process with `top beam` is the same, and so I will not include images of each step, but for reference, here is the final part,m showing inserts on all sides. <br><img width=400 src="https://github.com/user-attachments/assets/e980ad55-88a1-46ed-970c-74218c4c463d">

