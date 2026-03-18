# Item Resources

An item resource allows the interaction with container from blocks like chests, items like shulker boxes or bundles and entities like the player inventory.

![Set Block](/resources/plugins/procedure_base/resource/setBlockItemResource.png)

![Set Item](/resources/plugins/procedure_base/resource/setItemItemResource.png)

![Set Entity](/resources/plugins/procedure_base/resource/setEntityItemResource.png)

Each procedure block takes an item resource variable and gives out a boolean whether the block/item/entity has an item resource.

---

These procedure blocks return an item resource directly, but can cause an error if they are `null`.

![Get Block](/resources/plugins/procedure_base/resource/getBlockItemResource.png)

![Get Item](/resources/plugins/procedure_base/resource/getItemItemResource.png)

![Get Entity](/resources/plugins/procedure_base/resource/getEntityItemResource.png)