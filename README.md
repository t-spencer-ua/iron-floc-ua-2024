# iron-floc-ua-2024
Troy Spencer  
Underwood & Associates Internship 2024  
Iron Floc, Effects on Biodiversity


Site Names:  
Jabez 3 = j3  
Howard’s Branch = hb  
Cattail Creek; restored = ccr  
Jabez Main Branch = j1  
Arthur’s Run = ar  
Cattail Creek; unrestored = cc


site_name, transect_number, plot_location, and flow rate are all text inputs, ferrous_iron, d_o, d_o%, temp, conductivity, turbidity, taxa, and sample are all numeric inputs.

site_name = the name of the project site or unrestored site analogue

transect_number = the number of the transect the data was collected at, with the lowest number (1) being the closest to the downstream end of the project, moving upstream as the numbers increase

plot_location = whether the data was sampled on the transect exactly, or up or downstream of it, as per the 10 foot distance listed in the methods page

ferrous_iron = the ferrous iron present in the water sample for the given location, in ppm

d_o = dissolved oxygen present at the given location, in mg/L

d_o% = dissolved oxygen present at the given location, as % of total possible

temperature = temperature at the given location, in celsius

conductivity = the conductivity of the water at the given location

turbidity = the turbidity of the water at the given location
*any reading of 120.1 indicates that the turbidity was greater than 120, which is the maximum length of the turbidity tube used

taxa = the narrowest relevant taxonomical classification for each invertebrate

condition = the stream location is either restored or unrestored

date = the date of data collection, given in the ISO DD-MONTH-YYYY format

percent_cover = the average of three percent cover estimates as measured with a .5x.5m transect at three randomly selected points along the transect

sample = a yes or no value indicates whether the individual was in the original sample (yes) or collected from the vicinity and added to the sample manually (no)

flow_rate = average amount of water passing through the system per second, as measured with the orange method in cubic meters per second (m^3/s)