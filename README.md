# practice_bokeh
Practicing interactive visualization with Bokeh. 

- gapminder.py

Case study : 
Bokeh server application to visualize Gapminder data from 1970 to 2010. Creates a scatter plot of each country's data with dropdowns for both x and y axes to select from fertility, life expectancy, child mortality, and GDP data.
Slider changes visualization depending on the year. Each dot represents a country and is shaded according to continent. Legend provides color mappings key.

Run locally by executing in shell:
bokeh serve --show gapminder.py 
