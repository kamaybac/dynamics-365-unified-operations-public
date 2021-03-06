---
# required metadata

title: Update how amounts are displayed on reports and documents
description: This topic provides information about how to update how amounts are displayed on reports and other documents for Estonia, Latvia, Lithuania, Poland, Czech Republic, Hungary, and Russia.
author: ShylaThompson
manager: AnnBe
ms.date: 06/20/2017
ms.topic: article
ms.prod: 
ms.service: dynamics-ax-applications
ms.technology: 

# optional metadata

ms.search.form: Currency
audience: Application User
# ms.devlang: 
ms.reviewer: kfend
ms.search.scope: Core, Operations
# ms.tgt_pltfrm: 
ms.custom: 264254
ms.search.region: Czech Republic, Estonia, Hungary, Latvia, Lithuania, Poland, Russia
# ms.search.industry: 
ms.author: v-elgolu
ms.search.validFrom: 2016-11-30
ms.dyn365.ops.version: Version 1611

---

# Update how amounts are displayed on reports and documents

[!include [banner](../includes/banner.md)]

This topic provides information about how to update how amounts are displayed on reports and other documents for Estonia, Latvia, Lithuania, Poland, Czech Republic, Hungary, and Russia.

For legal entities in Estonia, Latvia, Lithuania, Poland, Czech Republic, Hungary, and Russia, you can set up full names and short names for currency units and subunits. These names can be used to transform how amounts are represented on documents and reports. For example: The amount **LTL 100.20** can be displayed as **100 Litas 20 Centas**.

## Set up full and short names for currency units and subunits
To set up full and short names for currency units and subunits for a language, complete the following steps:

1. Open the **Currencies** page.
2. Select a currency.
3. On the Action Pane, click **Declension**.
4. To add full name and short name for a language, click **New** and complete the following fields.

   |                                                                        |                                                                                                                                                                                                                                                                        |
   |------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
   |                         <strong>Field</strong>                         |                                                                                                                      <strong>Description</strong>                                                                                                                      |
   |                       <strong>Language</strong>                        |                                                                                                               Select the language for the current text.                                                                                                                |
   |    <strong>Singular nominative (Name of units field group)</strong>    |                                                                                       Enter the singular form of the currency. For example, the singular form of Litas is Litas.                                                                                       |
   |     <strong>Plural nominative (Name of units field group)</strong>     | Enter the plural form of the currency. For example, enter Litai. <strong>Note</strong>: The <strong>Singular genitive</strong> and <strong>Plural genitive</strong> fields are available based on the language that you select in the <strong>Language</strong> field. |
   | <strong>Singular nominative field (Name of parts field group)</strong> |                                                                                                        Enter the singular form of the subunit of the currency.                                                                                                         |
   |     <strong>Plural nominative (Name of parts field group)</strong>     |                                                                                                         Enter the plural form of the subunit of the currency.                                                                                                          |
   |    <strong>Shortcut name of units (Short name field group)</strong>    |                                                                                         Enter the ISO code to identify the currency. For example, enter LTL to identify Litas.                                                                                         |
   |   <strong>Shortcut name for parts (Short name field group)</strong>    |                                                                                               Enter the denomination of the currency subunit. For example, enter Centas.                                                                                               |
   |       <strong>Conjunction 'and' between units and parts</strong>       |                                     Select to print the conjunction “and” between the currency units and unit parts. For example, on invoices or reports, the amount for LTL 100.20 will be displayed as 100 Litas and 20 Centas.                                      |


5. Click **Save**.




