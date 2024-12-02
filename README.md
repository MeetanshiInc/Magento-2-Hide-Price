# **Magento 2 Hide Price Extension**

The **Magento 2 Hide Price** extension is a powerful tool designed for store owners who want to hide product prices on their Magento-based eCommerce websites. This feature can be particularly useful when targeting specific customer groups or when you want to hide prices until customers log in or request more information. This article will guide you through the key features and installation process of the Magento 2 Hide Price extension.

## **How It Works**

The **Magento 2 Hide Price** extension enables store administrators to hide product prices for specific customer groups, such as guests, non-logged-in users, or particular segments. Once the extension is installed and configured, store owners can decide whether to hide the price for all visitors or only for certain users, ensuring flexibility and customization.

## **Key Features**

* Supports multiple stores and languages.  
* Customize the text displayed in place of prices.  
* Option to hide the "Add to Cart" button.

## **Hide Price for Specific Customer Groups**

With this extension, store admins have the flexibility to control price visibility for different customer groups. Whether you want to show prices exclusively to registered users, hide them for guests or apply different rules based on customer groups, the extension allows full customization of price access and visibility.

## **Call for Price Button**

Instead of showing a price, the extension can display a customizable “Call for Price” or “Contact Us” button, encouraging customers to inquire for more information or a custom quote. This feature is particularly beneficial for high-value or personalized products and helps generate leads by fostering direct communication, ultimately boosting potential sales.

## **Seamless User Experience**

The Magento 2 Hide Price extension delivers a seamless user experience with minimal impact on website performance, ensuring optimal speed and functionality. It is fully mobile-optimized, responsive across all devices, and offers easy installation and setup for quick integration with your existing Magento store.

## **Extension Installation**

To install the **Magento 2 Hide Price** extension, follow these steps:

### **Step 1:** 

Extract the zip file and upload the extension to the root directory of your Magento 2 installation using FTP.

### **Step 2:**

### Login to your SSH and run below commands step by step:

* php bin/magento setup:upgrade  
* For Magento version 2.0.x to 2.1.x \- php bin/magento setup:static-content:deploy  
* For Magento version 2.2.x & above \- php bin/magento setup:static-content:deploy –f  
* php bin/magento cache:flush

## **How to Configure the Magento 2 Hide Price Extension**

### **Step 1: Configure Settings**

To configure the extension, log in to your Magento 2 admin panel and navigate to **Stores \> Configuration \> Hide Price**, where you'll find various settings to manage the extension.

![configuration](https://github.com/user-attachments/assets/78553fef-b83c-44a2-b43a-a6b4c2265e0a)

* **Hide Price**: Enable or disable the extension here.  
* **Hide Price Scope**: Choose the scope where you want to enable the "Hide Price" feature. If you select a product-specific scope, ensure you enable the product-specific hide price option, as detailed later in the document.  
* **Select Categories**: Choose the categories where you want to apply the "Hide Price" feature.  
* **Hide Price Text**: Enter the text or HTML code to display in place of the product price.  
* **Enable Hide Price for Selected Groups**: Set this option to “YES” to enable the hide price feature for specific customer groups. If enabled, select the relevant customer groups from the dropdown menu.  
* **Select Customer Groups**: Choose the customer groups for which the "Hide Price" feature will be active.

### **Step 2: Check Product-Specific Hide Price**

![check_product_specific_hide_price](https://github.com/user-attachments/assets/31448aaa-6b66-4038-8ad9-a9dfc5fb1d04)

The extension allows you to hide prices for individual products. To enable this feature, select the product-specific hide price scope during the extension configuration. Then, go to **Catalog \> Products \> Edit Product**, enable the hide price option in the relevant tab and you're all set.

### **Step 3: Check Hide Price on Frontend**

After successfully configuring the extension, the price details will be hidden on the frontend for the selected scope and customer groups.

* **Hide Price on Category Page**

![hide_price_on_category_page](https://github.com/user-attachments/assets/91388bc0-d155-4744-883d-381d3d705fd3)

* **Hide Price on Product Page**

![hide_price_on_product _page](https://github.com/user-attachments/assets/2cb8ea58-5904-480e-9c6d-009e6cea5f59)

## Download Our [Magento 2 Hide Price](https://meetanshi.com/magento-2-hide-price.html) Extension

