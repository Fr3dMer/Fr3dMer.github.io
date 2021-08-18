---
author: Freddie 
name: Other things I have been working on
image_link: /assets/images/gamelife.jpeg
title: Other things I have been working on
blurb: A few other things I've been playing with in my free time.
layout: projects
---

#### Conway's Game of Life

I’ve been playing around with Conway's Game of Life and trying to make it run on larger and larger grids, while trying to keep each tick at 0.5s. 

Right now I'm at a 60x60 grid using CPython. I've learn't alot since writing this code so my next plan is to go through and re-write the inefficient bits while using a different interpreter. 


#### Exploring property price patterns using the [Price Paid dataset](https://www.gov.uk/government/statistical-data-sets/price-paid-data-downloads) from HM Land Registry

After looking at flat prices I had a hunch they may follow a positve curve throughout their lifetimes with a dip around the 5 year mark. 

I analysed price data from HM Land Registry's dataset for all transactions since 1995 by writing a python script to filter out all non-flat transactions in my area and then ordering the data by postcode and creating an index. I also created a list of unique addresses for the area. By combining both of these lists I could find the transaction history for each flat. After creating this final dataset I could manipulate it to find that there is indeed a positve curve with a dip. 

My next goal is to use R to graph this data and output some nice illustrations of it.

#### Dual OS on home PC
       
On my home PC I use Windows and Arch linux (with GNOME as my desktop environment) on seperate SSD’s, using rEFInd as boot menu to choose between operating systems.
