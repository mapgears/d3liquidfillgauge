# d3liquidfillgauge

Created from: https://gist.github.com/adube/343e46d470655f935d4d8e382f2948d9

## Original README content

Liquid Fill Gauge v1.1 - 7/14/2015

Changes:

* Added support for updating the gauge value after loading is complete. The loadLiquidFillGauge method now returns an object with an update method which allows the gauge value to be changed. Click any of the gauges above to randomly update their value.

Configurable features include:

* Changeable min/max values.
* All colors.
* Outer circle thickness.
* Gap between the outer circle and inner fill area.
* Wave height.
* Wave speed.
* Wave count.
* Wave rise time.
* Wave height scaling on/off. Reduces the wave height near the min/max values so that the wave won't make the fill area appear total full or totally empty.
* Wave starting offset. Most useful when wave animation is turned off and you want the wave min or max at a specific horizontal position in the fill area.
* Wave rising upon load on/off.
* Wave animation on/off.
* Text height.
* Text vertical position.
* Text increment from min value upon loading.
* Display of % symbol on/off.

Open source under [BSD 2-clause](http://choosealicense.com/licenses/bsd-2-clause/)  
Copyright (c) 2015, Curtis Bratton  
All rights reserved.


Changes by adube:

* 0.2.0 - Allow changing configuration while updating. Useful to change colors.
