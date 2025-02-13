---
title: "Inventory Manager"
image: "/assets/images/inv.png"
description: "A simple, yet powerful tool used for warehouse inventory. Includes features to add and remove inventory as well as issue out equipment to individuals and track history."
technologies:
  - Python
  - USB Barcode Scanner
  - MySQL
github: "https://github.com/BNeasse99/inventorymanagerv4"
---

## More Detailed Description

This project started as a way to move away from paper and word of mouth tracking in my workplace when I was in the Air Force. We had tens of thousands of dollars worth of equipment needing to be hand counted too often without reliable record keeping. We had a need to come up with a new way to not only keep track of current inventory amounts, but also track individual users who were given equipment. Another need was keeping reliable counts for inventory as well as updating these amounts any time products were removed or added. In order to accomodate this, I built a program in Python using a MySQL database in order to keep records. I also used a barcode scanner in order to maintain efficiency and ease for end users. Keeping simplicity in mind, I used a simple GUI in order to ensure end users only had to use basic inputs to use the system. There are options for adding new users based off of the barcode on their ID, adding inventory, updating inventory, getting current counts on individual items, adding new products, and pulling up data on individual users to visualize what items they received. There is also a tracker built in order to audit who was giving out equipment, when they did it, and who they gave it to.