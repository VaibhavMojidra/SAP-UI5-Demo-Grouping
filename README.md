# SAP UI5 Demo Grouping

In SAP UI5, Grouping the list items can be done on list by adding a declarative sorter with group equals true to our binding syntax.

### Code Explaination

The **items** aggregation of the **List** control is bound to a model path **invoice>/Invoices**. The **sorter** property of the **items** aggregation is set to sort the items based on the **ShipperName** property and group them based on the same property.

In other words, the items in the list will be sorted based on the **ShipperName** property and grouped based on the same property. The **grouping** feature is only available for dimension columns and takes place on the server.

---

[![Vaibhav Mojidra - 1.jpeg](https://raw.githubusercontent.com/VaibhavMojidra/SAP-UI5-Demo-Grouping/master/screenshot/1.jpeg "Vaibhav Mojidra")](https://vaibhavmojidra.github.io/site/)