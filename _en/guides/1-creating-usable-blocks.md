---
title: 1 Creating Usable Blocks
description:
authors: ['Doaa Alsharif']
author_contacts: ['doaa']
order: 1
keywords: ['architecture', 'rhino']
layout: toc-guide-page
category_page: guides/
---

The aim of this tutorial is to learn how to create usable blocks for windows and doors from manufacturer websites like Anderson windows website. These blocks will be inserted as instance blocks in later chapters of this guide.

## 1.1 What are Blocks and How to Create Them

When you make a block in Rhino from geometry in the current file with the Block command, Rhino replaces the geometry you selected with a block instance. It saves the block definition (the geometry you selected to define the block) in the file. You can insert as many instances of this definition as needed with the Insert command.


(More information about blocks can be found here: Link and Link.)

### Advantages of using blocks include:

- You can change any number of copies of an object if they are block instances by making changes to the geometry that defines the block.
- Objects can be updated from external files.
- Repeated instances of a single definition do not increase the file size much since there is only one actual definition for the block held in the file. All instances reference the data for the one original definition. Rhino does some bookkeeping and display tricks to display these at the other locations and orientations.




---

## Next Steps

Now that you know what a scripting language is, check out the [Python Essentials]({{ site.baseurl }}/guides/rhinopython/primer-101/2-python-essentials/) guide to learn more about the Python language.
