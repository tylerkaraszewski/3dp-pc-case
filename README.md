GThis is a fully 3D-printable sub-6L case (in the version for the 9060XT variant).
There will be a 5070FE variant as well, which will be approximately 7.5L, but this is not yet available.

# System Component Requirements
1. This case is designed particularly around the [HDPlex 500W GaN PSU](https://hdplex.com/hdplex-500w-gan-aio-atx-power-supply.html).
This is not a stadard sized PSU and so far as I know, there are no other PSUs that will fit aside from possibly some of the other
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

# Printing instructions
This is not a 3D printing tutorial. If you are completely new to 3D printing, I suggest getting used to your printer with some objects from the
internet.Note that this project requires printing relatively large flat peices which can be difficult if your bed is out of level or has adhesion
issues, so make sure that's sorted before you begin.

## Download the Zip File of Your Choice
Currently there is [only one](https://github.com/tylerkaraszewski/3dp-pc-case/blob/main/9060XT_case_v94.zip).

Print one of each STL in the zip file except for:
* foot 1
* foot 2
* riser bushing

Print __2__ of each of those files.

__THESE FILES ARE INTENDED TO PRINT WITHOUT SUPPORTS__

You should be able to orient all of these files to print without supports. I do use supports to print the feet, though this should not strictly be
neccessary either. All other files except the feet should not need supports.
