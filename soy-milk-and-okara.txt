Inputs:  
	- Soybeans (g)  
	- Nutrition (cal/g)
Outputs:
	- Milk (L)  
	- Okara (g)  


Formula:  
	totalCal = soybeans * calPerG  
	okaraCal = totalCal * retentionFactor (~30%)  
	milkCal = totalCal - okaraCal  
	milkCalPerL = milkCal / milk  

Example:  
	200g soy, 1 cal/g, 1.2L milk, 30% okara retention.  
	Total: 200 cal  
	Okara: 60 cal  
	Milk: 140 cal  
	Milk/L: 116.67 cal/L  

