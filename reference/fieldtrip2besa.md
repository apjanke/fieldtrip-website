---
title: fieldtrip2besa
layout: default
tags: 
---
```
 FIELDTRIP2BESA saves a FieldTrip data structures to a corresponding BESA file. This
 export function is based on documentation that was provided by Todor Jordanov of
 BESA.

 Use as
   fieldtrip2besa(filename, elec)
 to export single trial data as a set of ascii-vectorized files (.avr)

 Use as
   fieldtrip2besa(filename, elec)
 or
   fieldtrip2besa(filename, grad)
 to export channel positions (.elp).

 Additional key-value pairs can be specified according to
   channel   = cell-array, can be used to make subset and to reorder the channels

 See also FIELDTRIP2SPSS, FIELDTRIP2FIFF
```
