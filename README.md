# H-repairkit

**Please do NOT sell this script for money.**  
It only took about 20 minutes to make and is shared freely with the community.  
Respect the work and keep it free!

**This script is provided as-is. Errors or bugs may occur, and no official support will be given.**  
You are encouraged to troubleshoot and customize it yourself.

---

A simple and modern vehicle repair kit script for FiveM that works with **ESX** and **vRP** frameworks.

---

## Features

- Framework support for ESX & vRP  
- Configurable repair duration, cancel key, freeze, and animations  
- Press **X** to cancel repair anytime  
- Cannot repair from inside vehicle
- Localized with English and Danish support  
- Easy to configure and customize  

---

## Installation

1. Drag and drop the  `H-repairkit` folder in your `resources` directory.  
2. Add the `repairkit` item to your inventory system (Item below).  
3. Use the repair kit item to repair vehicles nearby.

---

## Item

['repairkit'] = {
    label = 'Repair Kit',
    weight = 500,
    stack = true,
    close = true,
    description = 'Used to repair vehicles',
    usable = true,
    client = {
        event = 'H-repairkit:useItem',
    }
}
