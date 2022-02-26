# CSE-15L Lab Report 4

[This is my MarkdownParse repository](https://github.com/Ari2123/markdown-parse-lab8)

[This is the MarkdownParse repository I reviewed](https://github.com/m1ma0314/markdown-parse)

## FOR MY MARKDOWN-PARSE

<img width="621" alt="Screen Shot 2022-02-25 at 4 14 53 PM" src="https://user-images.githubusercontent.com/97698918/155819799-75d388b8-c5ba-43cb-91d7-79a9ad8369a9.png">

<img width="685" alt="Screen Shot 2022-02-25 at 4 15 14 PM" src="https://user-images.githubusercontent.com/97698918/155819821-c9443700-280d-495f-8a8a-9fcd38bc8675.png">

All the tests for the snippets work perfectly. One situation in which it would not work would be possibly if there was a link in the snippet which 
was not being correctly made into one by our MarkdownParse code by having extra paranthesis. This could be done by faulty if-statements. 

## FOR THEIR (REVIEWED) MARKDOWN-PARSE

Their code on VS code with the testers had some other issues that were beyond my capacity to fix, but here are the tests:

<img width="553" alt="Screen Shot 2022-02-25 at 4 24 40 PM" src="https://user-images.githubusercontent.com/97698918/155820374-0d5e3967-da60-4de9-8c71-c6d5a56c2ce2.png">

<img width="714" alt="Screen Shot 2022-02-25 at 4 25 00 PM" src="https://user-images.githubusercontent.com/97698918/155820390-338900c0-d6d0-48d2-9780-53b227245076.png">

<img width="722" alt="Screen Shot 2022-02-25 at 4 25 15 PM" src="https://user-images.githubusercontent.com/97698918/155820402-1a85ec46-4e7a-4df9-8a54-2b5ff1820986.png">

Beyond the other issues in their code, for the 3 snippets, it seems that their code does not properly detect the 3rd link (ucsd.edu): <[`google.com, google.com, ucsd.edu]> but was:<[url.com, `google.com, google.com]>". This could have to do with their if statements, or it could have to do with how they increment the spaces. 
