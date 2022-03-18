# CSE-15L Lab Report 3

After calling diff on the professor's markdown-parse results.txt and my markdown parse (markdown-parse-3) results.txt (results2.txt) I got this:

<img width="597" alt="Screen Shot 2022-03-10 at 6 03 07 PM" src="https://user-images.githubusercontent.com/97698918/157787922-c41ff080-f836-46f6-bece-73c847300fea.png">
<img width="606" alt="Screen Shot 2022-03-10 at 6 03 23 PM" src="https://user-images.githubusercontent.com/97698918/157787962-d9d7ed58-7c56-46ee-bf9b-ab7fb7cede36.png">

## TEST 1:

Looking at the diff I will examine line 880 of the results.txt which leads me to test file 495.md. Upon previewing, I can see that my output "> [foo(and(bar))]"
matches the previewed output from VScode for this test file.<img width="491" alt="Screen Shot 2022-03-10 at 6 05 18 PM" src="https://user-images.githubusercontent.com/97698918/157788151-434a067c-7f5f-44bd-98c3-7a1061f32f0e.png">

Whereas the professor's output "< [foo(and(bar]" misses 2 parentheses in the end. My output is the 2nd line in the diff and professor's output is the first based
on the order in which I called diff. 

I suspect the problem in professor's code to be around this while block due to incorrect indexing for the closing parentheses which is why it puts the closing parentheses before taking account of the missing spaces.

<img width="754" alt="Screen Shot 2022-03-10 at 6 20 31 PM" src="https://user-images.githubusercontent.com/97698918/157789698-952d4344-192e-4cce-8966-e6fe800102b2.png">


## TEST 2:

The next test I'm examining comes frome line 884 from results.txt which leads us to test file 497.md

<img width="208" alt="Screen Shot 2022-03-10 at 6 14 53 PM" src="https://user-images.githubusercontent.com/97698918/157789107-c1aaf10e-a283-4242-ae34-cfb6c3c6486f.png">

Upon previewing, we can see that there is a link that is the correct output:

<img width="736" alt="Screen Shot 2022-03-10 at 6 15 32 PM" src="https://user-images.githubusercontent.com/97698918/157789169-64ea8f25-d0cd-494c-a3b8-fcb9605c54f6.png">

However, both our results.txt files produce the incorrect output. Professor's provides no link "> []", and mine has 2 extra back slashes and is missing a 
parentheses at the end "< [foo\(and\(bar\]".

The problem in the code that reflects this error in professor's results.txt might be around here since there is an extra space which is the reason why professor's link isn't being coverted into a link. 

<img width="480" alt="Screen Shot 2022-03-10 at 6 21 23 PM" src="https://user-images.githubusercontent.com/97698918/157789789-8862997c-5ce2-4b47-bc9a-b635f95e6241.png">



