# attribute_decay
Purpose of this code is to generate artificial multivariate datasets
Given:
1) a list of attribute initial values as a "\n" delimited list file
2) a comma per term and \n per attribute delimited parameter of decay from position zero file
3) a functional form option for which the array of parameters applies, can mix functional forms
4) an extent of calculation option, the number of positional steps

Output:
csv which gives the position and attribute value at each position
parsable as
position_x,position_y,attribute_val_0,attribute_val_1,...,attribute_val_n

Which maps quickly to a shapefile where the first two columns are point coordinates and attr vals are entries in the attribute table for each coordinate.

This map may then be interpolated to create an attribute surface for any given attribute.

###
