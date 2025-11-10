# Debug Task 01

There’s no bug in this task. Add your own user number after the report name instead of XZ. For example, ‘Z_DEBUG_01_USER01’.

## Steps

1. In **SAP GUI** transaction `SE38`, enter `Z_DEBUG_01_USERXZ`, and click **Display**.
    
![alt text](solution_images/Afbeelding1.png)

2. Run the program by clicking **Direct Processing** or by pressing **F8**.
   
![alt text](solution_images/Afbeelding2.png)

3. Examine the output.
   
![alt text](solution_images/Afbeelding3.png)

4. Go back by clicking **Back** or pressing **F3**.
   
![alt text](solution_images/Afbeelding4.png)

5. Put a breakpoint on **line 7** and run the program again.

![alt text](solution_images/Afbeelding5.png)

6. Once the program runs in debugger mode, it stops at line 7.  
   - Double-click on `lv_a`, `lv_b`, and `lv_sum` to see the values of each variable.
     
![alt text](solution_images/Afbeelding7.png)

7. Press **Single Step** or **F5** once. Examine how the value for `lv_sum` changes.
   
![alt text](solution_images/Afbeelding6.png)

8. Press **Continue** or **F8** again so the program executes.
    
![alt text](solution_images/Afbeelding8.png)
