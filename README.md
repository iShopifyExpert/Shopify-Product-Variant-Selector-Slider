# Shopify-Product-Variant-Selector-Slider
How to Use
===========

add this line where you want to show variant slider

{% render 'variant-selector-slider', handle: 'the-starter-set' %}

Or 

<!-- dynamicaly add product variants by this code - Code by iShopifyexpert - Aaliyan Gul -->
{%- render 'variant-selector-slider', 
    handle: 'the-starter-set', 
    title: 'CONFIGURE YOUR STARTER SET', Subtitle: 'CHOOSE YOUR VIAL & POTIONS', 
    Paragraph: "Once you're happy with your above selection, click add to bag below!"
-%}
