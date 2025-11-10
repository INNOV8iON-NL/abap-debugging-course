# Debug Task 05

Add your own user number after the report name instead of XZ. For example, ‘Z_DEBUG_05_USER01’.

## Steps

1. In **SAP GUI** transaction `SE38`, enter `Z_DEBUG_05_USERXZ`, and click **Display**.  
2. Run the program by clicking **Direct Processing** or by pressing **F8**.  
3. Examine the output.  
4. Put a breakpoint on **line 8**. Run the program by clicking **Direct Processing** or by pressing **F8**.  
5. Examine the variables of the `SELECT SINGLE` statement. Press **Single Step** or **F5** to let the `SELECT` statement fill up with values.  
6. Determine what causes the error.  
7. Click **Execute** or press **F8** so the report is processed.  

8. Check file **Debugging Solutions**.  
