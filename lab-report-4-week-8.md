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

SCREENSHOTS FOR SNIPPETS:

Snippet 1:
<img width="425" alt="Screen Shot 2022-03-11 at 4 41 48 PM" src="https://user-images.githubusercontent.com/97698918/157996003-145acda8-33c6-4e52-9eb4-954a5a4249df.png">

Output for snippet1:

<img width="183" alt="Screen Shot 2022-03-11 at 4 44 02 PM" src="https://user-images.githubusercontent.com/97698918/157996136-53db6701-a974-4041-8671-f452ecdb448b.png">

<img width="455" alt="Screen Shot 2022-03-11 at 4 45 19 PM" src="https://user-images.githubusercontent.com/97698918/157996207-a708cdd8-9e5c-4140-b070-09a7bc6b7ca2.png">


Snippet 2:

<img width="485" alt="Screen Shot 2022-03-11 at 4 42 29 PM" src="https://user-images.githubusercontent.com/97698918/157996032-63db017d-9b71-4f32-a0bc-bccdf0cfa78e.png">

Output for snippet2:

<img width="303" alt="Screen Shot 2022-03-11 at 4 44 33 PM" src="https://user-images.githubusercontent.com/97698918/157996165-debeb91b-919c-4c9a-88af-3eeff8e6fae4.png">

<img width="453" alt="Screen Shot 2022-03-11 at 4 44 52 PM" src="https://user-images.githubusercontent.com/97698918/157996185-348e5d16-e9f0-4d8a-8a41-dd611b2dd839.png">


Snippet 3:

<img width="639" alt="Screen Shot 2022-03-11 at 4 42 51 PM" src="https://user-images.githubusercontent.com/97698918/157996054-01e2c72c-f55b-4177-9d83-2b01b781cec2.png">

Output for snippet3:

<img width="355" alt="Screen Shot 2022-03-11 at 4 45 53 PM" src="https://user-images.githubusercontent.com/97698918/157996240-a5ae14d7-672c-41fc-bee8-a1094f113320.png">

First link (twitter) opened:

<img width="229" alt="Screen Shot 2022-03-11 at 4 46 10 PM" src="https://user-images.githubusercontent.com/97698918/157996258-2afdd1e7-0283-4441-8a74-a273040e076e.png">

Second link (ucsd cse 15l lab) opened:

<img width="291" alt="Screen Shot 2022-03-11 at 4 46 57 PM" src="https://user-images.githubusercontent.com/97698918/157996290-6ce4fafd-5ac1-4e27-a8b6-c90f0357deb5.png">

Third link (cse.ucsd.edu) opened:

<img width="245" alt="Screen Shot 2022-03-11 at 4 47 27 PM" src="https://user-images.githubusercontent.com/97698918/157996311-05081033-0e31-4c7e-b2ef-2064a5fbd044.png">
