# vdk_truck

> Resources for FiveM allowing the user to access to a car inventory and for developpers to add and remove items from this inventory.

## If you want to support me and my work : :moneybag:[Paypal](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=B3ZE4W8Y626MA):moneybag:

## Requirements

- **es_freeroam**
- **vdk_inventory** last version : https://forum.fivem.net/t/release-inventory-system-v2-personal-menu/
- **ply_garage** (to add **personal vehicles**) : https://forum.fivem.net/t/release-en-fr-async-garages-v4-2-06-06-17-updated/
- **MySQL-Async** : https://forum.fivem.net/t/beta-mysql-async-library-v0-2-2/

## Installation

- Download the resource here : https://github.com/vodkhard/vdk_truck 
- Place the folder `vdk_truck` to resources folder of FiveM
- Execute **dump.sql** file in your database (will create the tables and the constraints)

## Usage

- For users : Press your  INPUT CELLPHONE CAMERA FOCUS LOCK (usually '**L**') to show the menu in front a vehicle
- For developers : Use "**car:receiveItem**" and "**car:looseItem**" server events
- You can change the **max capacity** in _server.lua_ with the maxCapacity variable
- You can watch the **PutInCoffre** function of `vdk_inventory` to see an example

## Next steps

- Add this system for job vehicles because actually it only work with personal vehicles ;)
