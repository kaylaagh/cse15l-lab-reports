# Lab Report 4 - Reproducing Tasks 
---
*Today we will focus on:*
```
1. Logging into ieng6
2. Clone your fork of the repository from your Github account
3. Run the tests, demonstrating that they fail
4. Edit the code file to fix the failing test
5. Run the tests, demonstrating that they now succeed
6. Commit and push the resulting change to your Github account (you can pick any commit message!)
``` 
---

## **Part 1: Logging into ieng6**

- Screenshot:


  ![Image](ieng6.png)


- Keys Pressed: 
  1. ssh <space> cs15lsp23eg<shift+2>@ieng6.ucsd.edu <enter>
  2. enter password


- Summary:


---

## **Part 2: Clone your fork of the repository from your Github account**

- Screenshot:
  
  ![Image](clone.png)

- Keys Pressed: 
  
  git <space> clone <space> <command+v>

- Summary:
  
---

## **Part 3: Run the tests, demonstrating that they fail**

- Screenshot:
  
  ![Image](failures.png)

- Keys Pressed: 
  
  1. cd <space> lab7 <enter>
  2. ls <enter>
  3. javac <space> -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar ListExamplesTests.java <enter>
  4. java <space> -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExamplesTests <enter>
  

- Summary:
  
  ---

## **Part 4: Edit the code file to fix the failing test**
  
- Screenshot:
  
  ![Image](fixedcode.png)

- Keys Pressed: 
  
  1. vim <space> <shift+l>List<shift+e>Examples.java<enter>
  2. <shift+;> :44 <enter>
  3. lllll
  4. r<2>
  5. <shift+;> :wq <enter>
  

- Summary:
  
## **Part 5: Run the tests, demonstrating that they now succeed**

- Screenshot:
  
  ![Image](success.png)

- Keys Pressed: 
 
  1. javac <space> -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar ListExamplesTests.java <enter>
  2. java <space> -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExamplesTests <enter>
  

- Summary:
  
  ---
