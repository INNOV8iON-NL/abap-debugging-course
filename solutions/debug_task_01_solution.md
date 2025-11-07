# Debug Task 01

There’s no bug in this task.

## Steps

1. In **SAP GUI** transaction `SE38`, enter `z_debug_01`, and click **Display**.  
![alt text](solution_images/Afbeelding1.png)

2. Run the program by clicking **Direct Processing** or by pressing **F8**.
   <img width="325" height="103" alt="Afbeelding2" src="https://github.com/user-attachments/assets/df1ec33a-a66b-4ef3-a280-bee5cdf57221" />


4. Examine the output.  
![alt text](Afbeelding3.png)
5. Go back by clicking **Back** or pressing **F3**.  
![alt text](Afbeelding4.png)
6. Put a breakpoint on **line 7** and run the program again. 
 ![alt text](Afbeelding5.png)
7. Once the program runs in debugger mode, it stops at line 7.  
   - Double-click on `lv_a`, `lv_b`, and `lv_sum` to see the values of each variable.  
   ![alt text](Afbeelding6.png)
8. Press **Single Step** or **F5** once. Examine how the value for `lv_sum` changes.  
![alt text](Afbeelding7.png)
9. Press **Continue** or **F8** again so the program executes.  
![alt text](Afbeelding8.png)
