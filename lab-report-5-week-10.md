# CSE-15L Lab Report 3

After calling diff on the professor's markdown-parse results.txt and my markdown parse (markdown-parse-3) results.txt (results2.txt) I got this:

<img width="597" alt="Screen Shot 2022-03-10 at 6 03 07 PM" src="https://user-images.githubusercontent.com/97698918/157787922-c41ff080-f836-46f6-bece-73c847300fea.png">
<img width="606" alt="Screen Shot 2022-03-10 at 6 03 23 PM" src="https://user-images.githubusercontent.com/97698918/157787962-d9d7ed58-7c56-46ee-bf9b-ab7fb7cede36.png">

## TEST 1:

Looking at the diff I will examine line 880 of the results.txt which leads me to test file 495.md. Upon previewing, I can see that my output "> [foo(and(bar))]"
matches the previewed output from VScode for this test file.<img width="491" alt="Screen Shot 2022-03-10 at 6 05 18 PM" src="https://user-images.githubusercontent.com/97698918/157788151-434a067c-7f5f-44bd-98c3-7a1061f32f0e.png">

Whereas the professor's output "< [foo(and(bar]" misses 2 parentheses in the end. My output is the 2nd line in the diff and professor's output is the first based
on the order in which I called diff. 

## TEST 2:

The next test I'm examining comes frome line 884 from results.txt which leads us to test file 497.md

<img width="208" alt="Screen Shot 2022-03-10 at 6 14 53 PM" src="https://user-images.githubusercontent.com/97698918/157789107-c1aaf10e-a283-4242-ae34-cfb6c3c6486f.png">

Upon previewing, we can see that there is a link that is the correct output:

<img width="736" alt="Screen Shot 2022-03-10 at 6 15 32 PM" src="https://user-images.githubusercontent.com/97698918/157789169-64ea8f25-d0cd-494c-a3b8-fcb9605c54f6.png">

However, both our results.txt files produce the incorrect output. Professor's provides no link "> []", and mine has 2 extra back slashes and is missing a 
parentheses at the end "< [foo\(and\(bar\]".




