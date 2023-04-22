# Lab Report 2 - Servers and Bugs
---
*Today we will focus on:*
```
1. Writing a Web Server 
2. Explaining Bugs
3. Something I Learned
``` 
---

## **Part 1: Writing a Web Server**

---

## **Part 2: Explaining Bugs**
- A failure inducing input:
```
@Test 
public void testReversed2() {
  int [] input2 = {1, 2, 3, 4, 5};
  assertArrayEquals(new int {5, 4, 3, 2, 1}, ArrayExamples.reversed(input2));
```
- An input that doesn't induce a failure
```
@Test 
public void testReversed2() {
  int [] input = { 3 };
  assertArrayEquals(new int { 3 }, ArrayExamples.reversed(input));
```
- The Symptom
![Image](symptoms2.png)

- The Bug
 
  Before:
  ```
  static int[] reversed(int[] arr) {
    int[] newArray = new int[arr.length];
    for(int i = 0; i < arr.length; i += 1) {
      arr[i] = newArray[arr.length - i - 1];
    }
    return arr;
  }
  ```
  After:
  ```
   static int[] reversed(int[] arr) {
    int[] newArray = new int[arr.length];
    for(int i = 0; i < arr.length; i += 1) {
      newArray[arr.length - i - 1] = arr[i];
    }
    return newArray;
  }
  ```
  Explanation:
  
  Before fixing the bug, it was returning the old array "arr" when we want to return the new array "newArray". Swaping the "arr" to "newArray" in the return statement would fix the problem of returning the new array. The other problem in reversed was in the for loop where it was setting all the values of the new array to 0. To fix this, you need to swap the order inside the loop to newArray[arr.length - i - 1] = arr[i] so that it would return the input in reversed order. The reason why the one test didn't fail was because there was only one number so the reversed order would be the same as the input no matter what.
  
---

## **Part 3: Something I Learned**

Something I learned from this weeks lab is that in order to access juint on vs code, you have to run a pretty specific command unlike what we do in CSE 12 where we just click the run button. It's more tedious on vs code but you end up with the same outputs. 
