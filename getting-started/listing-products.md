---
title: Listing Products
parent: Getting Started
nav_order: 1
---

# Listing Products
{: .no_toc }

We'll provision and manage the technology that powers your Annex Market node.

Most nodes will run a Shopify store, with a special theme that gets updated in
sync with the rest of the Annex Market nodes.

You'll be empowered to input your own data by following the steps outlined here:

The below is adapted from ["Shopify Official Documentation - Add a
Product"][add-product-shopify-docs], and ["Product Details"][product-details-shopify-docs]


- TOC
{:toc}

Background / Most Important Part
-----------------

While running a node, you'll be listing many products for pickup & delivery.

Annex Market will handle the listing & categorization of all Annex Market
products.

When you're ready to add your own product offerings, (fresh meals, takeout
options, etc.) there are a few key things to remember:

1. *Set a unique SKU.* Perhaps two letters representing your company, followed
   by a three digit numbering scheme.
   &nbsp;
   Ex. If your company is "Acme, Inc." your SKUs should be `AI001`, `AI002`, `AI003`,
   and so on.
2. *Inventory* should be set *not* to be tracked for in-house products that you sell
   through this online store <br /> ![No Inventory Tracking][no-inventory]
3. You can toggle *Product availability* per product when you are out of
   ingredients or are not taking orders on certain items.

------------------------

## First Steps

<iframe src="https://www.youtube.com/embed/fIxM_BP3Mtc?cc_lang_pref=en&amp;cc_load_policy=1&amp;hl=en" allowfullscreen width="100%" style="max-width: 800px" height="450"></iframe>

1.  From your Shopify admin, go to **Products** &gt; **All products**.<br />
    <img src="https://cdn.shopify.com/shopifycloud/help/assets/manual/products/add-update-products/products-button-copy-9e449c68c7970e0dfc17056a6f5cb3a17aa4f106b8dc39e0a9f4fbb5d6aec38e.png" width="239" height="180" alt="" />

2.  From the **Products** page, click **Add product**.

3.  Enter a title for your product, along with additional [details](https://help.shopify.com/en/manual/products/understanding-products).<br />
    <img src="https://cdn.shopify.com/shopifycloud/help/assets/manual/products/add-update-products/title-and-description-17c678b3ba2f184d43156ae94e61add3b4b79ebc387e2738a5c816c7be55b295.png" width="508" height="407" alt="" />

4.  Whenever you'd like to update, or save your progress, click **Save**. <br />
    <img src="https://cdn.shopify.com/shopifycloud/help/assets/manual/products/add-update-products/click-save-d701ebc7f7fe0ff6941f89de72c09f96a6b572bf9a3bfad23aeab010f084edfe.png" width="1024" height="483" alt="" />


## Product details

The details you provide for a product affect the way the product appears to
customers, make it easier for you to organize your products, and help customers
find the product. You don't have to provide every detail for each product.

For products that don't have any variants, the **Pricing**, **Inventory**, and
**Shipping** sections are shown on the product details page. If you add
variants, then those sections are no longer shown on the product details page.
To change the details for product variants, see [*Editing variants for an
existing product*](https://help.shopify.com/en/manual/products/variants/edit-variants).

### Title and description

-   **Title** - The name for your product as you want your customers to
    see it.

-   **Description** - The description for your product. This area uses
    the [rich text editor](https://help.shopify.com/en/manual/productivity-tools/rich-text-editor) so that you
    can format your text. Describe your products in detail to inform and
    persuade your potential customers. If you're a reseller, then don't
    use a manufacturer's exact description, because you want your
    products to be unique to search engines.

### Media

The images show your customers what the product looks like. For information
on adding product media, see [*Product media*](https://help.shopify.com/en/manual/products/product-media).

### Pricing

-   **Price** - The price that you're charging for the product.
    &nbsp;
    Click **Charge taxes on this product** if the product is taxable.

-   **Compare at price** - The original price for a product that is on
    sale. When you enter a compare at price, the product displays a
    [sale price](https://help.shopify.com/en/manual/promoting-marketing/discount-codes/sales).

-   **Cost per item** - can be left blank for our purposes.

### Inventory

-   **SKU (stock keeping unit)** - The code that identifies the product
    within your business. For effective tracking and sales reporting,
    each SKU needs to be unique.

-   **Barcode (ISBN, UPC, GTIN, etc.)** - can be left blank for our purposes.

-   **Inventory policy** - leave "Track Quantity" unchecked.
    ![][no-inventory]

### Shipping

-   **This is a physical product** - Give this a &#10004;

-   **Weight** - The product's actual weight. Product weight would ideally be
    exact if we were using third party services, and it was used in shipping fee
    calccalculations. Please include your best guess in lieu of that.
    &nbsp;
    It is shown to customers on the front end.

### Variants

For a product that has variants, this section shows the options for the
product, such as color and size. For more information about variants,
see [*Variants*](https://help.shopify.com/en/manual/products/variants).

### Product availability

This section should really only ever show "online store", and it should be
checked, as long as you want the product to appear for customers.

A list of your active sales channels where you can make the product
available. To edit sales channel availability, click **Manage**. For
more information about products and sales channels, see [*Make products
available on your sales
channels*](https://help.shopify.com/en/manual/products/add-update-products#make-products-available-on-your-sales-channels).

You can't set sales channel availability for individual product
variants.

### Product Organization

-   **Product type** - A category for the product that you can use to
    manage and group your products.
    &nbsp;
    For example, you can use the product type as a condition for an
    [automated collection](https://help.shopify.com/en/manual/products/collections/automated-collections), or to help you filter your products
    in the Shopify admin. A product can have only one product type.
    &nbsp;
    You can choose from any defined product type, or create a new one.
    To create a product type, enter it into the **Product type** field
    and then save the product. You can also create and edit product
    types in the [bulk editor](https://help.shopify.com/en/manual/productivity-tools/bulk-editing-products).

-   **Vendor** - The manufacturer, wholesaler, or other vendor for the
    product. This should probably be *you*.

-   **Collections** - The collections that a product is included in. You
    can use this field to add the product directly to [a manual collection](https://help.shopify.com/en/manual/products/collections/manual-shopify-collection#create-a-manual-collection).
    Automated collections include the product when it matches the collection
    conditions.

-   **Tags** - Tags are searchable keywords that you can associate with
    your product. Tags can help customers find your product through your
    online store search, and you can also use them to create [automated
    collections](https://help.shopify.com/en/manual/products/collections/automated-collections/auto-select).
    &nbsp;
    For more information about tags, see [*Tag formats*](https://help.shopify.com/en/manual/products/details/tags).

[add-product-shopify-docs]: https://help.shopify.com/en/manual/products/add-update-products#add-a-new-product
[product-details-shopify-docs]: https://help.shopify.com/en/manual/products/details
[no-inventory]: /assets/images/track-quantity-no.gif
