# Bresenham_Line_Drawing_Algorithm

# Modification when m>1:
When the slope m is greater than 1, it means the line is steeper, and for each step in the x-direction, the corresponding step in the y-direction is greater than 1. To adapt Bresenham's algorithm for such cases, the roles of x and y are swapped. That is, instead of considering each x-coordinate, we consider each y-coordinate and calculate the corresponding x-coordinate. This ensures that we cover each pixel in the line without skipping any pixels.


# Output:
Test Case 1:
(1,1)
(2,1)
(3,2)
(4,2)
(5,3)
(6,3)
(7,4)
(8,4)
# ***********
# *#*********
# *#*********
# **#********
# **#********
# ***#*******
# ***#*******
# ****#******
# ****#******
# ***********
# ***********

Test Case 2:
(1,1)
(1,2)
(2,3)
(2,4)
(3,5)
(3,6)
(4,7)
(4,8)
# ***********
# *##********
# ***##******
# *****##****
# *******##**
# ***********
# ***********
# ***********
# ***********
# ***********
# ***********
