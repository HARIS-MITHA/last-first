# last-first
to display last digit of number;
   def last_digit(number):
	return(number%10)
number=int(input())
print(last_digit(number))

to display first digit of number;
    def first_digit(number):
    while number>0:
      rem=number%10
      n=number//10
      number=n
    return(rem)
number=int(input())
print(first_digit(number))
