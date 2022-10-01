# bar-chart
creating a bar chart using geom_bar out of ggplot2

# Your team assigns you the task of creating a series of visualizations based on requests from the Chocolate and Tea management team. You decide to use ggplot2 to create your visuals. Assume your first line of code is:
ggplot(data = best_trimmed_flavors_df) +

# You want to use the geom_bar() function to create a bar chart. Add the code chunk that lets you create a bar chart with the variable Rating on the x-axis. 
geom_bar(mapping = aes(x = Rating))
ggplot(data = best_trimmed_flavors_df) +

# Add a code chunk to the second line of code to map the aesthetic alpha to the variable Rating:
geom_bar(mapping = aes(x = Company.Location, alpha = Rating))
