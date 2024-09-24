##1. We have to find module in magento 2 that we want to change
in this example it will be : 'vendor/magento/module-checkout/view/frontend/layout/checkout_index_index.xml'

#2. To override this xml layout for checkout we can create new module in 'app/code/Aware/CheckoutShippingNote'

#3. We have to find a block we want to change and use <referenceBlock> instead of <block> in his place to add some changes , then follow structures to the moment where we can inject out new element 



##Magento 2: Adding a Checkbox on Checkout

#Step 1: Identify the Module to Modify
Locate the Magento 2 module that needs to be modified. In this example, we will use: 'vendor/magento/module-checkout/view/frontend/layout/checkout_index_index.xml'.

#Step 2: Create a New Module to Override the Layout
Create a new module in 'app/code/Aware/CheckoutShippingNote to override the checkout layout XML'.

#Step 3: Modify the Block and Add a New Element
Identify the block that needs to be modified and use the <referenceBlock> tag instead of <block> to make changes. Then, follow the XML structure to the point where you can inject your new element.

```xml
<block>
```
