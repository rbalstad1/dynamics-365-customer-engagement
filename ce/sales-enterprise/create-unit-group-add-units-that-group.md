---
title: "Create a unit group and add units to that group (Dynamics 365 for Sales) | MicrosoftDocs"
ms.custom: ""
ms.date: 08/31/2017
ms.reviewer: ""
ms.service: "crm-online"
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "article"
applies_to: 
  - "Dynamics 365 (online)"
  - "Dynamics 365 Version 9.x"
ms.assetid: af99268c-9dc3-4037-b3cc-3d2a0eb2b296
caps.latest.revision: 18
ms.author: "shujoshi"
manager: "brycho"
---
# Create a unit group and add units to that group (Sales)

[!INCLUDE[cc-applies-to-update-9-0-0](../includes/cc_applies_to_update_9_0_0.md)]

Units are the quantities or measurements that you sell your products or services in. For example, if you sell gardening supplies, you might sell seeds in units of packets, boxes, and pallets. A unit group is a collection of these different units.  
  
 In [!INCLUDE[pn_crm_shortest](../includes/pn-crm-shortest.md)], you first create a unit group and then create units within that group. Let’s look at both of these tasks, using seeds as our example.  
 
<a name="bkmk_CreateUnitGroup"></a>   
## Step 1: Create a unit group  
  
1. [!INCLUDE[proc_permissions_mgr_vp_ceo_busmgr_sysadmin_syscust](../includes/proc-permissions-mgr-vp-ceo-busmgr-sysadmin-syscust.md)]  
  
    #### Check your security role  
  
    - [!INCLUDE[proc_follow_steps_in_link](../includes/proc-follow-steps-in-link.md)]  
  
    - [!INCLUDE[proc_dont_have_correct_permissions](../includes/proc-dont-have-correct-permissions.md)]  
  
2. [!INCLUDE[proc_settings_prod_catalog](../includes/proc-settings-prod-catalog.md)]  
  
3.  Choose **Unit Groups**.  
  
4.  To create a new unit group, choose **New**.  
  
     -OR-  
  
     To edit a unit group, open a unit group from the list.  
  
5.  Fill in your information:  
  
    - **Name**. Type a meaningful name for the unit group. In our example, you would type “Seeds.”  
  
    - **Primary Unit**. Type the lowest common unit of measure that the product will be sold in. In our example, you would type “packet.” Other examples could include ounces, hours, or tons, depending on your product or service.  
  
 ![Shows how to create a unit group in Dynamics 365](../sales-enterprise/media/v7-unit-group-mobile-single.png "Shows how to create a unit group in Dynamics 365 for Sales")  
  
6.  Choose **OK**.  
  
> [!NOTE]
>  You cannot delete the primary unit in a unit group.  
  
<a name="bkmk_CreateUnitsInGroup"></a>   
## Step 2: Create units in a unit group  
  
1.  In the unit group you want to add the units to, in the left pane, under **Common**, choose **Units**, and then on the **Units** tab, in the **Records** group, choose **Add New Unit**.  
  
     The unit that you specified as the primary unit earlier is already in the list of units.  
  
2.  Fill in your information:  
  
    1. **Name**. Type a meaningful name for the unit. In our example, you would type “box.”  
  
    2. **Quantity**. Type the quantity that this unit will contain. For example, if a box contains 12 packets, you would type “12.”  
  
    3. **Base Unit**. Select a base unit. The base unit will establish the lowest unit of measurement for the unit you’re creating. Using our example, you would select “packet.”  
  
         If you then create a unit called “pallet,” and one pallet contains 48 boxes, you would type “48” in **Quantity** and select “box” in **Base Unit**.  
  
     Here’s how:  
  
 ![Create a unit in the unit group in Dynamics 365](../sales-enterprise/media/v7-unit-pack.png "Create a unit in the unit group in Dynamics 365 for Sales")  
  
 ![Creating a unit with a base unit in Dynamics 365](../sales-enterprise/media/v7-unit-box.png "Creating a unit with a base unit in Dynamics 365 for Sales")  
  
3.  Choose **Save** or **Save and Close**.  
  
## Typical next steps  
 ![Right arrow button](../sales-enterprise/media/walkthrough-orange-right-arrow.png "Right arrow button") [Create a product](../sales-enterprise/create-product-sales.md)  
  
 \- OR -  
  
 ![Right arrow button](../sales-enterprise/media/walkthrough-orange-right-arrow.png "Right arrow button") [Create product bundles to sell multiple items together](../sales-enterprise/create-product-bundles-sell-multiple-items-together.md)  
  
 ![Home button](../sales-enterprise/media/walkthrough-home.png "Home button") [Set up a product catalog: Walkthrough](../sales-enterprise/set-up-product-catalog-walkthrough.md)