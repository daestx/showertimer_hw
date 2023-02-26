# showertimer_hw
Hardware for shower timer

Double-sided layout of the shower timer hardware.
You can find the corresponding software project under the following link

https://github.com/daestx/showertimer

# Principle
<p align="center">
<img src="https://user-images.githubusercontent.com/93374366/219699983-246ae9d4-0463-4847-8e8a-edacd911a8da.png" width="30%" width="30%" title="3D model">
</p>

The principle of operation of the shower timer is based on the measurement of the water flow through the shower hose. A tap extension is used for this purpose. Inside the extension is the 3D printout shown above. When water flows through this extension, the propeller (shown in light green in the picture) is set in rotation. Neodymium magnets are located on both sides of the propeller shaft at the top.

Therefore, the magnets are also moved. Outside the extension, a magnetic field can then be measured by a Hall sensor.

Another sensor measures the temperature on the outside of the extension. This allows the water temperature to be determined.

It is important to choose the extension from a thermally conductive, non-magnetic material. A brass fitting is used.


https://www.amazon.de/-/en/dp/B00N4WI6IE?psc=1&ref=ppx_yo2ov_dt_b_product_details

The 3D print template will be hosted on Thingiverse soon.

More information, you'll find in the wiki page: https://github.com/daestx/showertimer_hw/wiki

# Debug interface
As debugger, I use a Segger J-Link and a Tag-Connect 6 pin connecter as you can see it here: https://www.tag-connect.com/product/tc2030-idc-nl. In future, I'll support the version with "legs" as well. An adapter from J-Limk to TagConnect can be found here:

https://github.com/daestx/jlink

