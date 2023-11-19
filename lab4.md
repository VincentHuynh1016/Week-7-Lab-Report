# Step 4 (Log into ieng6)

1. First clicked on the terminal `<left mouse button>`
2. Typed in my ieng6 account '<cs15lfa23jn@ieng6.ucsd.edu>'

![image](https://github.com/VincentHuynh1016/Week-7-Lab-Report/assets/114731503/6825cc41-50c9-4a1d-b74b-de4c18f56fef)

# Step 5 (Clone your fork of the repository from your Github account (using the SSH URL))

1. I cloned the repository using the SSH URL
   - Typed `<git clone git@github.com:ucsd-cse15l-s23/lab7.git>`

2. Clicked `<enter>` and then the repository was now in my ssh.

![image](https://github.com/VincentHuynh1016/Week-7-Lab-Report/assets/114731503/800ca226-edcb-4b8d-8289-31ff7428bfe1)

# Step 6 (Run the tests, demonstrating that they fail)

1. `<cd>` into the lab7 directory
2. I then compiled the code first : Typed in  `<-cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java>`
3. After I ran the code to demonstrate that the code has failed the tests : Typed in: `<java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExamplesTests.java>`

![image](https://github.com/VincentHuynh1016/Week-7-Lab-Report/assets/114731503/ca60611f-4a5e-4c4b-ba20-5fd478cd30e1)

# Step 7 (Edit the code file to fix the failing test)

1. In the terminal I typed in `<vim>` and then next to the `vim` command I typed in `<ListExamples.java>` and then `<enter>`
2. I pressed `<j>` 43 times to move down the code to where I needed to fix.
3. Then I typed in the `<l>` key to move to the right 11 times
4. I alternated between `<x>` and `<h>`, `x` was to delete the character and `h` was used to move to the left.
    - I used `<x>` 6 times
    - I used `<h>` 5 times
5. Then I pressed the `<i>` key to activate insert
6. Typed in `<index2>`
7. Pressed the `<esc>` key to get out of the insert method
8. Pressed the `<:>`key and types in `<wq>` and pressed `<enter>` to save and get out of the vim command

#### Before:
![image](https://github.com/VincentHuynh1016/Week-7-Lab-Report/assets/114731503/75716253-050d-46ad-841a-870b7f058a86)

#### After:
![image](https://github.com/VincentHuynh1016/Week-7-Lab-Report/assets/114731503/8a91fef6-3ec5-4230-a047-638d1a8d0d72)





