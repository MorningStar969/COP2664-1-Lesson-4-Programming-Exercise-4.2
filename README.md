# COP2664-1-Lesson-4-Programming-Exercise-4.2
This is a GitHub repository link for Programming Exercise 4.2 of Lesson 4.

// These five different program sections are used to compute the sum of the first two integers, the absoulute difference of n and 51, return true if one of them is 20 or if their sum or difference is 20, return true if one one is negative or postive, and determine if they are both in range of 20 to 30.

import Foundation // This is used to import the Foundation library.
// 1.
func sumOfTwoIntegers(a: Int, b: Int) -> Int { // This function is used to compute the sum of the first two integers.
  if a == b { // This if statement is used to determine if the two integers are equal.
    return (a + b) * 3 // This is used to return the sum of the two integers multiplied by 3 if they are equal.
  } else { // This else statement is used to determine if the two integers are not equal.
    return a + b // This is used to return the sum of the two integers.
  }
}
print(sumOfTwoIntegers(a: 5, b: 5)) // This is used to print the sum of the two integers.
// 2.
func absoluteDifference(n: Int) -> Int { // This function is used to compute the absolute difference of n and 51.
  if n > 51 { // This if statement is used to determine if n is greater than 51.
    return (n - 51) * 2 // This is used to return the absolute difference of n and 51 multiplied by 2.
  } else { // This else statement is used to determine if n is less than 51.
    return 51 - n // This is used to return 51 minus n.
  }
}
print(absoluteDifference(n: 53)) // This is used to print the absolute difference of n and 51.
// 3.
func test(x: Int, y: Int) -> Bool { // This function is used to determine if one of the two integers is 20 or if their sum or difference is 20.
  if x == 20 || y == 20 { // This if statement is used to determine if one of the two integers is 20.
    return true // This is used to return true if one of the two integers is 20.
  } else if x + y == 20 { // This else if statement is used to determine if their sum is 20.
    return true // This is used to return true if their sum is 20.
  } else { // This else statement is used to determine if neither of the two integers is 20.
    return false // This is used to return false if neither of the two integers is 20.
  }
}
print(test(x: 20, y: 10)) // This is used to print true if one of the two integers is 20 or if their sum or difference is 20.
// 4.
func test2(x: Int, y: Int) -> Bool { // This function is used to determine if one one is negative or positive.
  if x < 0 && y > 0 || x > 0 && y < 0 { // This if statement is used to determine if one one is negative or positive.
    return true // This is used to return true if one one is negative or positive.
  } else if x < 0 && y < 0 { // This else if statement is used to determine if both of the two integers are negative.
    return true // This is used to return true if both of the two integers are negative.
  } else { // This else statement is used to determine if both of the two integers are positive.
    return false // This is used to return false if both of the two integers are positive.
  }
}
print(test2(x: -1, y: 1)) // This is used to print true if one one is negative or positive.
// 5.
func test3(x: Int, y: Int) -> Bool { // This function is used to determine if they are both in range of 20 to 30.
  if x >= 20 && x <= 30 && y >= 20 && y <= 30 { // This if statement is used to determine if they are both in range of 20 to 30.
    return true // This is used to return true if they are both in range of 20 to 30.
  } else if x >= 30 && x <= 40 && y >= 30 && y <= 40 { // This else if statement is used to determine if they are both in range of 20 to 30.
    return true // This is used to return true if they are both in range of 20 to 30.
  } else { // This else statement is used to determine if they are not in range of 20 to 30.
    return false // This is used to return false if they are not in range of 20 to 30.
  }
}
print(test3(x: 20, y: 30)) // This is used to print true if they are both in range of 20 to 30.
