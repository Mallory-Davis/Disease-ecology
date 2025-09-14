# Disease-ecology
Worksheet 1
<img width="448" height="274" alt="image" src="https://github.com/user-attachments/assets/31d3309b-5b23-4e01-ba52-bf5e283787ec" /> 



Find area of a circle with radius 5 cm.

Formula: ¶ * r^2

where r is the radius.

{r}
# Function to calculate the area of a circle
area_of_circle <- function(radius) {
  area <- pi * radius^2
  return(area)
}
radius <- 5 # from the example
circle_area <- area_of_circle(radius)
cat("The area of the circle with radius", radius, "is", circle_area, "\n")
The area of the circle with radius 5 is 78.53982 


