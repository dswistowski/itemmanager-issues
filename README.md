# Welcome to the Item Manager.
The fastest item manager for Destiny 2

![Screen shot](/img/screen.png)

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

Additionally you can save search by pressing star icon. Your searchs are storen in browser local storage, so you can use them later on the same browser

## Can I change sort order?

Yes, please mind the search option on your navbar - near sort icon. You can use it to change current sorting.
