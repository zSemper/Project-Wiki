# The Resource System

Resources are the gateway to interact with items, fluids and energy. While they are very powerful, they are also more advanced than other features procedure blocks provide.

A resource variable is by default `null`, meaning trying to interact with it will produce an exception and causes the game to crash. 

---

There are two different methods of setting a resource to an actual value. Both can be used in different contexts, depending on if the resource comes a block, item or entity.

The first is by using a setter procedure block. This will set the variable and gives out a boolean depending on if the resource is `null` or not, to avoid errors.

![Setter](/resources/plugins/procedure_base/resource/setBlockItemResource.png)

The second method is by getting the resource directly, which is not recommended, unless it's known the returned resource is not `null`.

![Getter](/resources/plugins/procedure_base/resource/getBlockItemResource.png)

---

If it's not 100% clear, if a resource is at any point `null` or not, it can be checked by a Is resource null procedure block.

![Is null (you better hope not)](/resources/plugins/procedure_base/resource/isResourceNull.png)
