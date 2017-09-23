# Welcome to the Item Manager.
The fastest item manager for Destiny 2

![Screen shot](https://raw.githubusercontent.com/dswistowski/itemmanager-issues/master/img/screen.png)

# FAQ

## Is it safe?

Yes, the app is using official Bungie API. After authorization - Bungie provides one-hour valid token which is stored only in your local session and is not send anywhere else. The token allows only to transfer items, change lock state. Bungie does not allow to do any not reversible operations - like dismantle or infuse items

## How does it work?

After authorization, select your target on the top nav bar (any character on vault), then click the item. Item will be transferred to the selected character.

## Why this app, not other already existing?

A long time ago, I've created Vault helper what was the first item manager app for Destiny. My UI approach was always different than others. It can be not so intuitive but is more efficient in the long run.

## How search works

 - You can search by name - just type part of your item name: `Mida mu`
 - You can search by tier - just type the tier: `legendary`
 - You can search by power level - try: `265+`, `280-290`
 - You can search by type - try: `legs`, `ship`, `energy`
 - You can search by subtype - try: `submashine`
 - You can search by damage type - try: `solar`, `void`
 - You can search by character - try: `vault`, `warlock`
 - You can join searches - `legendary submashine solar 280+` will show only legendary submashine guns with solar modifier and power level bigger than 280.
 - You can search for duplicates - `duplicate`
 - You can search for rare modifications which you cannot exchange to legendary ones yet `rare modifications 1-2 characters`
 - You can find rare modification to change to legendary which are stored in valut: `rare modifications 3+ vault`
Additionally you can save search by pressing star icon. Your searchs are storen in browser local storage, so you can use them later on the same browser

## Can I change sort order?

Yes, please mind the search option on your navbar - near sort icon. You can use it to change current sorting.


## Examples:
### Searching for mods - transfer to vault
![Mods to valut](https://raw.githubusercontent.com/dswistowski/itemmanager-issues/master/img/to-vault.png)
### Searching for mods - transfer to character
![Mods from vault](https://raw.githubusercontent.com/dswistowski/itemmanager-issues/master/img/from-vault.png)
### Search for duplicates
![Duplicates](https://raw.githubusercontent.com/dswistowski/itemmanager-issues/master/img/duplicates.png)