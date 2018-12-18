# Using the API-
* A substring is a string within a string that is indicated by two integers
* If the substring does not occur in the string then it returns -1

# Understand the new method-
* findKeyword("She's my sister", "sister", 0); iteration: 1 psn: 9 before: " " after: null
* findKeyword("Brother Tom is helpful", "brother", 0); iteration: 1 psn: 0 before: null after: " "
* findKeyword("I can't catch wild cats.", "cat", 0); iteration: 1, 2 psn: 8, 19 before: " ", " " after: "c", "s"
* findKeyword("I know nothing about snow plows.", "no", 0); iteration: 1, 2, 3 psn: 4, 8, 23 before: "k", " ", "s" after: "w", "t", "w"