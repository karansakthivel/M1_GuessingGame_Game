## Introduction
The guessing game is two-person game called "Guess the number". The first player thinks of an integer within a known range. If the guess is incorrect then the first player tells the second player whether the guess was too high or too low. Eventusally the second player guesses the correct number. 
## SWOT ANALYSIS
![Screenshot (230)](https://user-images.githubusercontent.com/89648206/132314075-9d5d147b-6ebf-423d-bda4-03099ab72553.png)



## ***4 W's and 1H***
### Who:
       This game is useful for the people who looks for the entertainment.
### What:
        This game increases the anticipation capability. 
### When:
        The project is used when the people look for stress relief.
### How:
        This project works on a computer or laptop 
## HIGH LEVEL REQUIREMENTS:
| ID | Description | Category |
|---------|--------|----------|
| HLR_01 | Visual Studio code Platform| software | 
| HLR_02 |windows or linux OS | software | 
## LOW LEVEL REQUIREMENTS:
| ID | description |
|-----|------------|
|LLR_01 | reference number |
|LLR_02 |guessed number |

## IMPLEMENTATION STRUCTURE:
Folder        | Description
--------------| ----------------------------------------------
`inc`         |  header files
`src`         | Source code files for solvinng Arthimetic operations
`test`        | All source code and data for testing purposes
`unity`       | Files for unit testing

# TEST PLAN:
| **Test ID** | **Description**                                              | **Expected Input** | **Expected Output** |   
|-------------|--------------------------------------------------------------|------------|-------------|
|  HLT_01      | gguessing number | num=5, guess=4 | your number is lower than the guess number |
|  HLT_02      | guessing a number  | num=5,guess=-2 | guess the number within the range|
|  HLT_03      |guessing a number| num=5, guess=7| your number is greater than the guess number | 
|  HLT_04      |guessing a number| num=5, guess=11| enter the number within the range| 
