---
title: How To Prefix Product Tags on Shopify
subtitle: We demonstrate how you can add a prefix to existing product tags on your Shopify store using custom tag operation. 
excerpt: >-
  Imagine that you have 20 discount tags like '10% Off', '20% Off', etc and your goal is to add the prefix "Sale" to all of them. You can certainly create 20 operations to rename each individual tag but is there a more efficient way? There certainly is with Tag Genie and what we call Tag Templates. 
author: src/data/authors/jane-doe.yaml
date: '2021-04-10'
canonical_url: 'https://www.taggenieapp.com/blog/prefix-product-tags-shopify/'
thumb_image: https://taggenie.azureedge.net/images/blog-prefix-tags-cover.png
thumb_image_alt: Prefix tags tuhumbnail image
image: https://taggenie.azureedge.net/images/blog-prefix-tags-cover.png
image_alt: Prefix tags cover image
template: post
---

This time cover more advanced functionality of Tag Genie using our most powerful tool - Custom Tag Operation. How can you prefix product tags on Shopify? While that might sound like a trivial task it gets more complicated if you try to prefix different tags using the same prefix. 

Imagine that you have 20 discount tags like '10% Off', '20% Off', etc and your goal is to add the prefix "Sale" to all of them. You can certainly create 20 operations to rename each individual tag but is there a more efficient way? There certainly is with Tag Genie and what we call **Tag Templates**. 

Using **Tag Templates** you can add prefix to tags in bulk by using the special token **{{tag_name}}** which will basically match the name of the tag being processed. 

So in order to add the prefix "Sale", click the "**Create Tag Operations**" button in Tag Genie and then select **Custom Tag Operation**. On the next screen, add Rename tag operation and choose the condition that will match the tags you would like to add a prefix to. Having our example in mind, we can use the **contains** condition to match all tags that contain **"%"** which will match all tags like '10% Off', '20% Off'. 

The last step is to choose the new tag name. This is where we can use **Tag Templates** - simply type in **"Sale {{tag_name}}"** and Tag Genie will prefix all matching tags with "Sale" giving you "Sale 10% Off", "Sale 20% Off, etc. 

As always, we have prepared a short video tutorial to guide you through the process.

`youtube: https://youtu.be/8hNAOhFZWow`
