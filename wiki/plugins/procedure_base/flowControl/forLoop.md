# For Loop

The for loop repeats code until the a specific condition is met.

![For Loop](/resources/plugins/procedure_base/flowControl/forLoop.png)

While the code is looping the index that gets changed can be accessed by the Get Index block.

![Get Loop Index](/resources/plugins/procedure_base/flowControl/forLoopIndex.png)

## Parameter

For Index `Index Field` = `Index Value`; Repeat as long as Index `Condition` `End Value`; `Change Operator` Index by `Change Value` do

|Definition|Description|
|-|-|
|Index Field|This is the index that will be changed during the looping. The name allows it to be accessable by the Get Index block.<br><span style="color:#ff0000">Note:</span> While a For Loop block can be placed inside another one the Index needs to be different|
|Index Value|This sets the starting value of the index.|
|Condition|This determines how the loop stops.<br><span style="color:#ff0000">Note:</span> For loops where the index does not increase for decrease by 1 conditions with &ne; can lead to infinite loops.<br>Different condition operators: &ne; <, &leq;, &geq;, >.|
|End Value|This determines when the loop stops.|
|Change Operator|This determines how the index value changes while the loop is running.<br>Options: Add, Subtract, Multiply, Divide|
|Change Value|This determines by how much the index is getting changed.|