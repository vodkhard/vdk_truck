# vdk_truck

> Resources for FiveM allowing the user to access to a car inventory and for developpers to add and remove items from this inventory. It's a resource more for developers.

## Requirements

- **es_freeroam**
- **vdk_inventory** : https://forum.fivem.net/t/release-inventory-system-v2-personal-menu/
- **ply_garage** (to add **personal vehicles**) : https://forum.fivem.net/t/release-en-fr-async-garages-v4-2-06-06-17-updated/
- **MySQL-Async** : https://forum.fivem.net/t/beta-mysql-async-library-v0-2-2/

## Installation

- Download the resource here : https://github.com/vodkhard/vdk_truck 
- Place the folder "vdk_truck" to resources folder of FiveM
- Execute _dump.sql_ file in your database (will create the tables and the constraints)

## Usage

- For users : Press your  INPUT CELLPHONE CAMERA FOCUS LOCK (usually '**L**') to show the menu in front a vehicle
- For developers : Use "**car:receiveItem**" and "**car:looseItem**" server events
- You can watch the **PutInCoffre** function of `vdk_inventory` to see an example
