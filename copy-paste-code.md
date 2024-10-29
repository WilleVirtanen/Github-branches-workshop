## Instructions 
1. Create a new branch, name it something like "multiplication". Once the branch has been created, copy the following code and place it inside of Calculator.java
2. Commit, push and publish the code, then change back over to your main branch. 
3. Once you are on your main branch, perform the following steps:
    - **If you're using Github Desktop**: 
        - Find the "Merge into **main**" alternative in your menu. 
        - Choose your new branch and press "create a merge commit"
        - Follow the instructions

    - **If you're using VS Code**: 
        - Press `Ctrl + Shift + P`
        - Type `Git: Merge`
        - Choose the branch you want to merge from
Don't forget to make sure you commit and push your changes!  

**Did you manage to complete it?** Great! Now try some more things out on your own.  
Why not create another branch where you also make changes to add/subtract? 

## Code to copy+paste
The following is some example code that you can use to test out merging branches. 
### Multplication
```java
public class Calculator {
    public double add(double a, double b) {
        return a + b;
    }

    public double subtract(double a, double b) {
        return a - b;
    }

    public double multiply(double a, double b) {
        return a * b;
    }
}
```