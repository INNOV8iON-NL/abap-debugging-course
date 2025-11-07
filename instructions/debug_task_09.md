# Debug Task 09

## Steps

1. In **SAP GUI** transaction `SE38`, enter `z_debug_09`, and click **Display**.  
2. Run the program by clicking **Direct Processing** or by pressing **F8**.  
3. Examine the output.  
4. Go back to the report. Set a debugger point on **line 10**, and start **Direct Processing** / **F8**.  
5. Observe the different variables of the **LOOP** statement and **IF** statement.  
   <details>
     <summary>Hint</summary>
     
   You can also double-click `SY-TABIX` to watch its value change.
   </details>
6. Set a watchpoint to observe when `lv_matnr` is skipped.  
   <details>
     <summary>Hint</summary>
     
   You can set a watchpoint to show up when the watched variable is empty by typing `= ''` in the **Free Condition Entry**. Make sure to include a space after the `=` sign to avoid an error in the condition.
   </details>
7. Determine why there is one line where the material number is skipped.  
8. Check file **Debugging Solutions**.  