# ISS_ClassActivity2
#List of all errors with their fixes

Line 1 -- def is_narc(n) -> def is_narc(n):

Line 3 -- num_str == str(n) -> num_str = str(n)

Line 4 -- num_digits == len(num_str) -> num_digits = len(num_str)

Line 6 -- sum_of_powers = sum(int(digit) *** num_digits for digit in num_str) -> sum_of_powers = sum(int(digit) ** num_digits for digit in num_str)

Line 10 -- def print_narcis_numbers(start end) -> def print_narcis_numbers(start, end):

Line 12 -- for num in range(start, end + 1)
-> for num in range(start, end + 1):

Line 13 -- if is_narcissistic(num) -> if is_narc(num):

Line 16 -- print_narc_numbers(1000, 5000) ->  print_narcis_numbers(1000, 5000) 
