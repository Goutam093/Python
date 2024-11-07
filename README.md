# Python
python code for pyramid pattern <br>
def print_pyramid(n):
    # Loop through each level of the pyramid
    for i in range(1, n + 1):
        # Print spaces before the stars on each level
        print(' ' * (n - i), end='')  
        # Print stars for the current level
        print('*' * (2 * i - 1))

# Example usage:
n = 5  # Number of rows for the pyramid
print_pyramid(n)
