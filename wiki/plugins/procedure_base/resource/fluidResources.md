# Fluid Resources

A fluid resource allows the interaction with fluid tanks from blocks, items or (rarely) entities.

![Set Block](/resources/plugins/procedure_base/resource/setBlockFluidResource.png)

![Set Item](/resources/plugins/procedure_base/resource/setItemFluidResource.png)

![Set Entity](/resources/plugins/procedure_base/resource/setEntityFluidResource.png)

Each procedure block takes a fluid resource variable and gives out a boolean whether the block/item/entity has a fluid resource.

---

These procedure blocks return a fluid resource directly, but can cause an error if they are `null`.

![Get Block](/resources/plugins/procedure_base/resource/getBlockFluidResource.png)

![Get Item](/resources/plugins/procedure_base/resource/getItemFluidResource.png)

![Get Entity](/resources/plugins/procedure_base/resource/getEntityFluidResource.png)