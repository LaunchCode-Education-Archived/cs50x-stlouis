##### [Module 3](../..)

# Prep for Class 2

Before coming to [Class 2](../class2), please complete the following tasks...

##### Module 2 Review
Task | Resource Type | Link | Instructions
-----|------|------|-------------
Study | CS50 Study | <a href="https://study.cs50.net/?toc=loops,ascii,functions,argv" target="_blank">loops, ascii, functions, argv</a>  | Some additional review of topics from Modules 1 and 2.

***

##### Lecture
Task | Resource Type | Link | Instructions
-----|------|------|-------------
Watch | Lecture | <a href="https://www.youtube.com/watch?v=JovNemG-iu8" target="_blank"> Week 3, continued</a> | This lecture introduces Merge Sort, a sorting algorithm that out-performs the ones we've seens so far, running in O(n log n) time. Merge Sort is implemented using recursion, a technique in which a function calls itself. This lecture also talks a bit more about what goes on when we compile our programs using `make`.

***

##### Merge Sort
Task | Resource Type | Link | Instructions
-----|------|------|-------------
Read | Lecture Notes | <a href="http://cdn.cs50.net/2015/fall/lectures/3/w/notes3w/notes3w.html#merge_sort" target="_blank">Lecture Notes: Week 3, continued / Merge Sort</a> | These notes detail how Merge Sort is implemented and why it is fundamentally more efficient than the others.
Watch | Doug's Playlist | <a href="https://www.youtube.com/watch?v=sWtYJv_YXbo&index=6&list=PLhQjrBD2T382Bh-sc1w74c4V6_G2byC-T" target="_blank"> Merge Sort</a> | Doug Lloyd talks in depth about Merge Sort.
Watch | Shorts | <a href="https://www.youtube.com/watch?v=EeQ8pwjQxTM" target="_blank"> Merge Sort</a> | Rob Bowden illustrates Merge Sort with a live demo using those styrofoam cups you love.

***

##### Recursion
Task | Resource Type | Link | Instructions
-----|------|------|------
Watch | Lecture | <a href="https://www.youtube.com/watch?v=8Ba7SgCN2XY&index=9&list=PLhQjrBD2T383Xfn0zECHrOTpfOSlptPAB" target="_blank">Week 4</a> | Watch the first 25 minutes only. We are jumping ahead to some Week 4 content so we can dive a little more deeply into recursion.
Read | Lecture Notes | <a href="http://cdn.cs50.net/2015/fall/lectures/4/m/notes4m/notes4m.html#recursion" target="_blank">Week 4 / Recursion</a> | Review the notes from lecture where David revisits the previous example of a recursive algorithm.
Read | Lecture Notes | <a href="http://cdn.cs50.net/2015/fall/lectures/4/m/notes4m/notes4m.html#sigma" target="_blank">Week 4 / Sigma</a> | These notes walk through the recursive implementation of the `sigma` function.
Follow-Along | Walkthrough | <a href="https://www.youtube.com/watch?v=C-J0fKmwKmw&list=PLhQjrBD2T382SQnebs5bf6BkngrHTbJKg&index=10" target="_blank">sigma-0</a> | David builds a non-recursive implementation of the `sigma` program, which calculates the sum of the integers 1 through n. <br> You can find the pseudocode for this walkthrough <a href="../../../../../../helpful-resources/modules/module-3.html#class-2-task-sigma-0" target="_blank">here</a>.
Follow-Along | Walkthrough | <a href="https://www.youtube.com/watch?v=GSY5bEv3gX8&index=11&list=PLhQjrBD2T382SQnebs5bf6BkngrHTbJKg" target="_blank">sigma-1</a> | Now David re-implements `sigma` using recursion! <br>You can find instructions to start this walkthrough <a href="../../../../../../helpful-resources/modules/module-3.html#class-2-task-sigma-1" target="_blank">here</a>.
Read | Resource | [Sigma Breakdown](../resources/sigma-breakdown) | Here we try to lay out the process of what really happens as the `sigma` function processes the answer for a particular number. After reading this resource, you are encouraged to step through your copy of the program in the IDE Debugger, just like they did in class. | 
Watch | Doug's Playlist | <a href="https://www.youtube.com/watch?v=VrrnjYgDBEk" target="_blank"> Recursion</a> | Doug talks about recursion and gives some more examples, including calculating the factorial of a number, and something called the Collatz Sequence.
Watch | Shorts | <a href="https://www.youtube.com/watch?v=t4MSwiqfLaY" target="_blank"> Recursion</a> | Zamyla Chan talks some more about recursion. In the second half she starts talking about binary trees, and you will see some code that looks unfamiliar. You can stop as soon as you feel like the video is no longer helping solidify your understanding of recursion.
Do | Exercise | [Fibonacci](../exercises/fibonacci) | Flex your recursion muscles by writing a program that derives the classic Fibonacci Sequence.

***

##### Sorting Algs Summary
Task | Resource Type | Link | Instructions
-----|------|------|-------------
Watch | Doug's Playlist | <a href="https://www.youtube.com/watch?v=B6l7AJYgCOI" target="_blank">Algorithms Summary</a> | Doug gives a final recap of all the different sorting algorithms and how they compare. <br>You can also check Helpful Resources <a href="../../../../../../helpful-resources/Supplementary-Resources/algorithms-summary.html" target="_blank">here</a> for a supplemental resource on Algorithms.</a>
Study | CS50 Study | <a href="https://study.cs50.net/binary_search?toc=bubble_sort,insertion_sort,selection_sort,merge_sort" target="_blank">bubble sort, insertion sort,<br> selection sort, merge sort</a> | One last review of these algorithms, this time via CS50 Study.

***

##### Compiling, Header Files
Task | Resource Type | Link | Instructions
-----|------|------|-------------
Read | Lecture Notes | <a href="http://cdn.cs50.net/2015/fall/lectures/3/w/notes3w/notes3w.html#compiling" target="_blank">Week 3, continued / Compiling</a> | Read about Code Compilation, the process by which your computer turns the code you write into instructions the machine can execute
Watch | Shorts | <a href="https://www.youtube.com/watch?v=CSZLNYF4Klo" target="_blank"> Compilers</a> | Watch this short about compilers
Watch | Shorts | <a href="http://www.youtube.com/watch?v=U3zCxnj2w8M" target="_blank"> Clang, Make</a> | Watch this short about Clang and Make, two tools used to manage the building and compilation of code projects
Watch | Shorts | <a href="https://www.youtube.com/watch?v=ED7QtgXDShY" target="_blank"> Libraries</a> | Watch this short about libraries
Watch | Section | <a href="https://youtu.be/XRvvitgap5Y?t=2549" target="_blank"> Compilation Process</a> | Watch this lecture on the compilation process. Feel free to stop at the 59 minute mark. 
Read | Resource | [Spread Out](../resources/spread-out) | Here's an example of a program that starts off written as one big file, but is subsequently reorganized into a few smaller, easy to understand files.
Do | Exercise | [Delmar House of Tires](../exercises/house-of-tires) | Here we ask you to fix a program by pulling out some code from another very similar program into a new helper file, so that both programs can share the helper file and you don't have to rewrite any code.

***

##### Bitwise Operators
Task | Resource Type | Link | Instructions
-----|------|------|-------------  
Read | Lecture Notes | <a href="http://cdn.cs50.net/2015/fall/lectures/3/w/notes3w/notes3w.html#bitwise_operators" target="_blank">Week 3, continued / Bitwise Operators</a> | THIS IS OPTIONAL. Check out these notes for a brief discussion of Bitwise Operators, which allow you to manipulate values at the level of individual bits (1s and 0s). Neat stuff!

***

### Now you can head to [Class 2](../class2)!
