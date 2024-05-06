---
title: Saeco Phedra Coffee Vending Machine
description: Documentation about how our coffee vending machine works.
published: true
date: 2024-05-06T07:00:02.796Z
tags: 
editor: markdown
dateCreated: 2024-04-28T07:18:17.845Z
---

# Introduction
> This machine is not operational yet and this documentation is a work in progress.
{.is-danger}


Our "Saeco Phendra Cappuccino" is a hot beverage vending machine. It can make many types of hot beverages including coffee and chocolate. This wiki page documents how we have it setup, all of it's resources, and the procedures for maintenance, and restocking it.
![saeco-hendra.png](/other/vending/saeco-phedra.png =x300)

# How to use
> Do not perform maintenance or try to open the machine unless you have permission from the infrastructure working group or committee.
{.is-warning}

The usage instructions attached to the machine are fairly simple.

1. Swipe card.
2. Place cup under outlet.
3. Select beverage to vend and add fresh milk if desired.
4. Enjoy beverage.


# Specifications
**Induction class:** Green (No induction required)
**Model:** Saeco Phedra Cappuccino
**Controller:** Proprietary (original, supports MDB)
**Serial Number:** 9010N5P0005980 (maybe)
**Manufacture Date:** 07/2010
**Beverages dispensed counter when we got it:** 15,974

**Documentation:**

* [Original User & Service Manual](/other/vending/saeco-phedra-user-manual-and-maintenance.pdf)

# Stock procedures
## Suppliers
A local supplier in Enogerra called [Crema Coffee Garage](http://cremacoffeegarage.com.au) is recommended for all vending powders. They have local stock of chai, choc and milk powder, and have a reasonable price.

### Specific product that we use
If you need to use a different product for some reason, ***make sure you by one that specifically says it's for vending machines.***

* [Arkadia Original Chocoloate Powder](https://cremacoffeegarage.com.au/arkadia-vending-chocolate-750g.html)
* [Arkadia Chai Spiced Powder](https://cremacoffeegarage.com.au/arkadia-chai-1kg-spiced-vending.html)
* [Crema Vending Dairy Creamer](https://cremacoffeegarage.com.au/crema-vending-dairy-creamer-750g.html)

## Restocking the machine
Todo.

# Maintenance
Todo.

# Recipes
Our paper cups are 340ml capacity but aim to vend 310ml at most. Any recipe with a reasonable amount of the dairy creamer will foam *a lot* so make sure you reduce the water quite a bit.

## Recipes
### Espresso
Sequence: C000

### Long Black
Sequence: C000

### Dirty Chai

### Chai Latte

### Flat White

### Cappuccino

### Mocha

### Hot Chocolate
**Sequence**: 2300 (Choc, Milk)

**Choc**
% InstProd 2: 80%
InstProd Dose 2: 88 (34g)
H2O InstProd 2: 96 (80ml)
% Pump 2: 80%

**Milk**
% InstProd 3: 80%
InstProd Dose 3: 58 (14g)
H2O InstProd 3: 180 (150ml)
% Pump 3: 80%

# Dosage Amounts
Trying to work out the dosage amounts that correspond to the numbers on the screen can be frustrating! The best way to work it out is to use the test menu to vend "powder only" of a set amount, say 100 units. It's recommended to configure a dummy recipe (on say recipe slots 9-16 which aren't used) containing only the product you want. There should be a recipe configured on 9,10 & 11 for this purpose already.

Place a small bowl or cup under the dispening outlet to catch it, then use the test menu and "powder only" button to dispense the product. Weigh the amount that came out and work out the dosage / grams. You can then use this value to work out what dosage value you need to get a certain amount dispensed. The value is dependant on the product type, supplier, and which hopper it's dispensed from.

## Calibrated Dosage Amounts
The following should be good enough to use when programming new recipes. If you change the supplier or type of product, you should re-calculate it using the instructions above and update this section.

* "Just Water": 1.3 doses/ml (100 dose dispensed just above 75ml)
* "Hopper 1/2 Water": 1.2 doses/ml (150 dose dispensed 123ml)
* Arkadia Chocolate Powder in *hopper 2*: 2.6 doses/gram (80 doses dispensed 30g)
	* Arkadia recommends 11.5g/100ml of beverage
* Crema Dairy Creamer Powder in *hopper 3*: 4.2 doses/gram (80 doses dispensed 19g)
	* Crema recommends 8.5g/100ml of beverage
* Arkadia Chai Spiced Powder in *hopper 1*: 4.2 doses/gram (80 doses dispensed 19g)
	* Arkadia recommends 11g/100ml of beverage
