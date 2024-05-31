---
title: Laser Cutter
description: Learn about our laser cutter.
published: true
date: 2024-05-31T02:13:02.443Z
tags: 
editor: markdown
dateCreated: 2021-09-07T13:27:31.653Z
---

# Introduction
Our laser cutter is one of our most popular tools. It can be used to cut or engrave lots of common materials including timber, plastic, and paper, to name a few. Unfortunately it cannot cut metal or glass (though it can engrave them in the right circumstance).

![laser.png](/digitalfabrication/laser.png =x300)
*A picture of our laser cutter*

# Opt-in Booking System
Please use the link in the [member portal](https://portal.brisbanemaker.space) to see existing bookings or to make a new one. We operate an opt-in booking system for this machine.

It's called an opt-in booking system because you can still use it before/after your booked time or without a booking, but you may have to share with other members.

Please read our full tool sharing and booking policy [here](/policies/fair-use#tool-sharing) for details.

# Recommended Uses
You can cut out unique shapes from sheets of materials up to 8-10mm thick (material dependent). Laser cutting is ideal for making mounting plates, custom enclosures and boxes, personalising projects, etc.

You can also engrave text, images and other shapes directly onto your projects. This allows you to create truly unique works of art, add a personal touch to your project, or make something as simple as a name badge or plaque.

# Specifications
**Usage Cost:** $10/hr of machine on time

**Induction Class:** 🟡 Orange Tool (Induction Required)
**Cut/Engrave Area:** 700 x 500mm Max
**Laser Power:** ~100w power from a 130w rated Reci tube
**Focal Length:** 76.2mm (previously 50.8mm)
**Max Cut Depth:** Up to 8mm - 10mm (depending on material, acrylic and ply work best at up to 6mm)
**Notable Features:** camera assisted job positioning; automatic focus; automated extraction, air assist and cooling system.

# Induction Process
**⚠️ This tool requires an induction before use.**

To book an induction for this machine, please use the "book appointment" link from the [member portal](https://portal.brisbanemaker.space).

[INDUCTION FORM](https://docs.google.com/forms/d/e/1FAIpQLScVzylQZOLUkiaqrupoYlcB5JeBWFef23AOR8p6ANu0f3PWCg/viewform) (completed by the person running the induction as a record of completion)

# Machine Consumables
## Focus Lens
Cloudray from Aliexpress is the best place to buy these. The most recently purchased one was [this listing](https://www.aliexpress.com/item/32234326702.html?spm=a2g0o.order_list.order_list_main.40.428b18029YGYMx).

It's important that you choose the following specs:
* USA CVD ZnSe (other types aren't suitable for our environment)
* 76.2mm Focal Length (aka 3")
* 18mm Diameter

## Mirrors
Cloudray from Aliexpress is the best place to buy these. The most recently purchased one was [this listing](https://www.aliexpress.com/item/32234558080.html?spm=a2g0o.order_list.order_list_main.61.428b18029YGYMx).

It's important that you choose the following specs:
* "Mo" Material
* 19.05 Diameter
* 10.6nm/ 10600nm Wavelength
* Power rating should be at least 130W


# Safety

## Potential Hazards
| Potential Hazard | Details |
|--|--|--|
|[![laser-beam.svg](/sops/warning-icons/laser-beam.svg)<div>Laser Beam</div>](#)|The CO<sup>2</sup> laser beam can shoot out the front of the machine.|
|[![breathing-hazard.svg](/sops/warning-icons/breathing-hazard.svg)<div>Breathing Hazard</div>](#)|Certain materials can generate fumes or fine particulate matter during cutting operation.|
|[![flammable-material.svg](/sops/warning-icons/flammable-material.svg)<div>Flammable Material</div>](#)|Material being cut can heat up and combust during cutting operation.|
|[![entanglement.png](/sops/warning-icons/entanglement.png)<div>Entanglement</div>](#)|Focusing apparatus can pose a entanglement and crushing hazard|
{.sop-symbols}

# How To Operate
You should be familiar with how to operate this tool after completing an induction. However, a quick reference guide is included below to assist you.

## Camera Positioning System
We have a super cool camera positioning system setup on the laser cutter. It allows you to put offcuts or irregular sized sheets inside and visually move your cut/engrave job around with a preview of where it's going to cut.

It's accurate to within 2-3mm normally, but may deviate by up to 5mm (half a square in lightburn). Make sure to move the Z height of the machine to the engrave/cut height **before capturing a snapshot** for best accuracy. If accuracy is critical, do a test cut first before relying on the camera.

## Software / Cut Files
We use industry standard software called [Lightburn](https://lightburnsoftware.com) to run our laser cutter. This software supports the following files: .SVG, .DXF or . PDF.  Alternatively, you can purchase a license of Lightburn if you'd like to experiment at home or on your own computer (recomended if you do a lot of lasering).

You can bring your files:
* on a USB flash drive/SD card
* use AirDrop to copy it to our iMac
* login to google drive etc. directly on our iMac

You don't need to set your cut files with specific colours / thicknesses etc for cutting vs engraving. All of that is configured inside lightburn before being sent to the machine. However, we do recommend that you group your jobs by cuts and engraves. On import, lightburn assigns layers by colour so having all your cuts as one colour, and all your engraves as a different colour is helpful. Once in lightburn, you apply certain profiles (like say one for cutting and a different one for engraving) to each layer.

## Before Use
1. Check that your material is on the approved materials list.
2. Turn on the machine and "focus" it by using the on board control panel. Place your material onto the bed and click on "Update Overlay" to update the camera preview.
3. Import your job into lightburn and place it on your material. Use our pre calibrated profiles to start with and adjust settings as needed.
4. Check the material thickness, then start the job and watch the machine until it is finished.

## During Use
1. Watch the machine **at all times** while it is running.
2. Do not leave the machine unattended for even a moment. You must watch it at all times while it is running. Leaving it unattended will result in a warning (or worse) for breaching our [safety policy](/policies/safety).
3. Immediately press the red "e-stop" button if you think there is a problem with the machine. It's better to spoil a piece of material than a $10,000 machine. If a fire does not subside after stopping the machine, immediately grab a fire extinguisher *then* open the machine to put it out.

## After Use
1. Wipe down the shiny horizontal surfaces with the provided cleaning wipes.
2. Dispose of all offcuts into the bin and tidy up the area.
3. Turn off the machine.

# Offcuts and Scraps
We have an offcuts box right next to the laser cutter. You are welcome to use any offcuts or scrap pieces of material from this box for free. You are also encouraged to leave any offcuts from your projects in this bin (ie give some/take some). However, you should break off any thin pieces and you should check that there is at least 10cmx10cm of usable material left.

# Approved Materials
Some materials are dangerous to cut or engrave and can damage the machine or even worse, release poisonous fumes. We operate a very strict list of approved materials. If you use a material not on this list without prior approval from staff, we will issue a warning (or worse) for breaching our safety policy.

We recommend that most people use Acrylic or "Laser Safe" Plywood for the cleanest cuts and least amount of hassle.

## List of Approved Materials
* "Laser Safe" plywood such as from [Plyoneline](http://plyonline.com.au) or [LaserPly from Plyco](https://plyco.com.au/collections/laserply)
* Balsawood
* Bunnings Plywood (BC Grade) * **not recommended if you need a high quality finish**
* Bunnings MDF * **not recommended to use due to excessive charring and smoke**
* Acrylic
	* Some materials are similar in appearance to acrylic but are quite different. Some can release poisonous fumes or result in poor cuts. Any acrylic that is not from our material shelf must have a receipt or manufacturer affixed label showing that it is acrylic.
* Cardboard and Card
* Veg Tan Leather (other colours / types please **ask first**)
* Very thin polycarbonate (<1mm)
* EVA Foam

# Brisbane Makerspace Stocked Materials
We try to keep the following materials / consumables in stock for members to purchase. However, we sometimes run out of stock due to the volunteer nature of how we operate. It is generally recommended to source your own materials.

## 600 x 400mm sheets
These sheets are approximately sized - please check each sheet if the exact size is critical for your intended use.
* 3-6mm Acrylic - C Grade, approx size, has scratches and marks (various colours) ($3)
* 3mm MDF ($3)
* 3mm Radiata Plywood ($7)
* 3mm Poplar Plywood ($14)

# Tips / Suppliers
The following is a list of tips/recommended suppliers for commonly used consumables:
* Poplar (and other laser safe) Plywood - [Plyonline](https://www.plyonline.com.au/collections/poplar-plywood/laser) or for more range [Plyco](https://plyco.com.au)
* Radiata Plywood, MDF & Sand Paper - [Bunnings](http://bunnings.com.au)
* Acrylic (local supplier) - [Acrylics Online](https://acrylicsonline.com.au)
* Acrylic (online supplier) - [Koenig](https://koenigmachinery.com.au/collections/all)
* Extra Wide Masking Tape - [Graphpic Art Mart](https://www.gamart.com.au/Products/Item/tapear)
