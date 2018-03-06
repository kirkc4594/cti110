# cti110
CTI Repository
# P3T1- Areas Of Rectangles
# Candice Kirk
# 03/06/18

# Get the dimensions of rectangle 1.
length1_CSK = int(input('Enter the length of rectangle 1: '))
width1_CSK = int(input('Enter the width of rectangle 1: '))

# Get the dimensions of rectangle 2.
length2_CSK = int(input('Enter the length of rectangle 2: '))
width2_CSK = int(input('Enter the width of rectangle 2: '))

# Calculate the areas of the rectangles.
area1 = length1_CSK * width1_CSK
area2 = length2_CSK * width2_CSK

# Determine which has the greater area.
if area1 > area2:
    print('Rectangle 1 has the greater area.')
else:
    if area2 > area1:
        print('Rectangle 2 has the greater area.')
    else:
        print('Both have the same area.')
        
