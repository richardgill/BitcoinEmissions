BitcoinEmissions
================

A project to calculate CO2 emissions of mining bitcoin.

Motivation
==========

We wanted to understand how much energy was going into the computing the hashes in bitcoin and hence how much CO2 was being produced. 



Assumptions
===========

Generating electricity releases 500 grams of CO2/kWhe. Based on:  [wikipedia](https://en.wikipedia.org/wiki/Electricity_generation#Environmental_concerns)

The average efficiency of the bitcoin miners in the system is 2000 Mhash/J. Which is conservative. Source: [mining hardware comparison](https://en.bitcoin.it/wiki/Mining_hardware_comparison)

We have generated a function which fits the HashRate up to now - it assumes it's exponental.

Results
=======

According to our calculations as of May 1st 2014 each bitcoin will release ~103 kg of CO2 into the atmosphere. That happens once every 24 seconds. 

If efficiency of bitcoin miners stays the same. That number will reach ~1602 kg of CO2 by May 1st 2015. 

Running the code
================

We've provided the code which is Wolfram Mathematica (version 9). 
