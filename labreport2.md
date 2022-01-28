# CSE-15L Lab Report 2

For this lab report I will be going over 3 changes we made to the default markdown code from github in order to make it work. 

## 1st Code Change:

The first code change that our group worked on was the while statement on line 13 of the code. 

<img width="1204" alt="Screen Shot 2022-01-28 at 3 08 15 PM" src="https://user-images.githubusercontent.com/97698918/151633862-48bcc414-d9c1-4a39-ae1c-e9dd975ea62d.png">

[1] (https://github.com/ocboogie/markdown-parse/commit/2ae51068a97b42a93a61c886534133634ade07e0)

The following is the error we got with the older faulty version of the code. It is an index out of bounds exception. 

<img width="619" alt="Screen Shot 2022-01-28 at 3 20 27 PM" src="https://user-images.githubusercontent.com/97698918/151634735-06f0e346-9007-40ec-b2c2-fe4e30235c4a.png">

To fix this, we replaced "while(currentIndex < markdown.length())" to "while(currentIndex <**=** markdown.length())." We also added an if statement to break if
the nextOpenBracket was -1. 

## 2nd Code Change:

The second code change that our group worked was on adding more if statements to correct indices and positioning. 

<img width="1213" alt="Screen Shot 2022-01-28 at 3 26 52 PM" src="https://user-images.githubusercontent.com/97698918/151635164-c0c758b7-e197-4173-98af-b14bdd210ff8.png">

[2] (https://github.com/ocboogie/markdown-parse/commit/30eda7a98151e2b31d8188d583db27200989e734)

<img width="603" alt="Screen Shot 2022-01-28 at 3 28 24 PM" src="https://user-images.githubusercontent.com/97698918/151635260-84a21855-7e5c-4e4c-8894-cdd8bf69f80e.png">

We were still getting an ArrayIndexOutOfBoundsException for line 27. In order to correct this we fix the error and another infinite loop. This was to 
change the current index by repeating the code if the character at the index was "!" Meaning, go to the next index. 

## 3rd Code Change:

The third change was replacing line 21 with an if statement. 

<img width="1217" alt="Screen Shot 2022-01-28 at 3 42 24 PM" src="https://user-images.githubusercontent.com/97698918/151636211-4172b336-7d67-4aab-ab09-e5bb4574f5a6.png">

[3] (https://github.com/ocboogie/markdown-parse/commit/ce6dcbf6156474a0f980316be42c1bcd66fd0d52)

We fix the error by rejecting the extra space between ](. This is done with the if statement where if there is an open parantheses after a closing square bracket, there will be a space between. 






