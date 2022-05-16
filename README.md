# codewar-winner
I won a kata! 

HERE GOES THE PROBLEM :

After a hard quarter in the office you decide to get some rest on a vacation. So you will book a flight for you and your girlfriend and try to leave all the mess behind you.

You will need a rental car in order for you to get around in your vacation. The manager of the car rental makes you some good offers.

Every day you rent the car costs $40. If you rent the car for 7 or more days, you get $50 off your total. Alternatively, if you rent the car for 3 or more days, you get $20 off your total.

Write a code that gives out the total amount for different days(d).

HERE GOES THE SOLUTION :

Solution 1 : If a day === 1 and a day's price is $40 then rentalCarCost will be day * $40, right?
so that means if it were 10 days, we will get 10 * $40...

Solution 2 : If you rent the car for 7 or more days i.e rentalCarCost - $50

Solution 3 : If you rent the car for 3 or more days i.e rentalCarCost - $20

Solution 4 : If any of those solution above do not apply, then rentalCarCost remains calculated by the number of days i.e rentalCarCost * day
