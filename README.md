# FIXME (1): Prompt for four weights. Add all weights to a list. Output list.
weight1 = float(input('Enter weight 1:\n'))

weight2 = float(input('Enter weight 2:\n'))

weight3 = float(input('Enter weight 3:\n'))

weight4 = float(input('Enter weight 4:\n'))

weights = [weight1, weight2, weight3, weight4]
print('Weights:', weights)
print()


# FIXME (2): Output average of weights.
average_weights = (weight1 + weight2 + weight3 + weight4)/4
print('Average weight:', average_weights)


# FIXME (3): Output max weight from list.
weights.sort()
print('Max weight:', ('%.2f' % max(weights)))
print()

# FIXME (4): Prompt the user for a list index and output that weight in pounds and kilograms.
list_index = input('Enter a list index (1 - 4):\n')
print('Weight in pounds:', ('%.2f' % weight3))
kilograms = weight3 / 2.2
print('Weight in kilograms:', ('%.2f' % kilograms))
print()
    
# FIXME (5): Sort the list and output it.
weights.sort()
print('Sorted list:', weights)
