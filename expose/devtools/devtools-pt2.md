1. The bug was that both num1 and num2 are strings instead of nums, so calculateSum simply concatenates the two strings instead of adding their numerical value.
2. Convert the datatype of num1 and num2 from string to int using Number().
