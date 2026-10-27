CIS-165-W198

Initial Plan
  average.cpp Plan
    Variables:
      value1 = 28
      value2 = 32
      value3 = 37
      value4 = 24
      value5 = 33
    Calculations:
      sum = value1 + value2 + value3 + value4 + value5
      average = sum / 5
    Output:
      Display the sum with a label.
      Display the average with a label.
  ocean_levels.cpp Plan
    Rate:
      1.5 millimeters per year
    Years:
      5
      7
      10
    Calculations:
      increase_5 = rate × 5
      increase_7 = rate × 7
      increase_10 = rate × 10
    Output:
      Display all three ocean-level increases with labels and units.
      
Testing 
  Average Test 1 (Assigned Values)
    Vaules used
      28, 32, 37, 24, 33
    Expected Results 
      Sum = 154, Average = 30.8
    Actual results 
      Sum = 154, Average = 30.8
    Result - My expected results matched my actual results. 
  Average Test 2 (changed values)
    Vaules used
      10, 20, 30, 40, 55
    Expected Results 
      Sum = 155, Average = 31.0
    Actual result 
      Sum = 155, Average = 31.0
    Result - My expected results matched my actual results. 
  Ocean Test 1 (Assigned rate)
    Vaule used  
      1.5
    Expected Results 
      7.5, 10.5, 15.0
    Actual results 
      7.5, 10.5, 15.0
    Result - My expected results matched my actual results. 
  Ocean Test 2 (changed rate)
    Vaule used 
      2.3
    Expected Results 
      11.5, 16.1, 23.0
    Actual results 
      11.5, 16.1, 23.0
    Result - My expected results matched my actual results. 

Questions
  1.) Why should the five values and the average use the double data type?
    - The double data type can store decimal values. The five assigned values are whole numbers; however, the average may        contain a decimal value such as 30.8. 
  2.) Trace the assigned values through sum and average.
    - The values 28, 32, 37, 24, and 33 are added together to get the sum of 154. The program then divides 154 by 5 to           calculate for the average. The average is 30.8.
  3.) Why should the average calculation divide the completed sum rather than only the final value?
    - An average shows the total of all values divided by the number of values. Dividing only the final value would             disregard the other numbers and get an incorrect average.
  4.) Explain how the ocean-level calculations use the annual rate and number of years.
    - The program multiplies the annual ocean-level rise rate by the number of years. 
  5.) Why is the annual ocean-level rate a good candidate for a named constant?
    - The annual rate does not change during program execution. Using a named constant prevents accidental changes and           makes the program easier to read.
  6.) Why does the assignment require calculations to be stored before using cout?
    - Storing calculations in variables makes the program easier to read, debug, test, and understand.










