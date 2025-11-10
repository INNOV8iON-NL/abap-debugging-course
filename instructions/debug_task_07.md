# Debug Task 07

Add your own user number after the report name instead of XZ. For example, ‘Z_DEBUG_07_USER01’.

## Steps

1. In **SAP GUI** transaction `SE38`, enter `Z_DEBUG_07_USERXZ`, and click **Display**.  
2. Take some time to observe the report to understand the expected outcome. Run the program by clicking **Direct Processing** or by pressing **F8**.  
3. Examine the output.  
4. Go back to the report.  
5. Put a debugger point on **line 6**, and run the program by clicking **Direct Processing** or by pressing **F8**.  
   - Inspect variables `lv_total`, `lv_discount`, and `lv_final`.  
   - Observe how the logic of the **IF statement** executes.  
6. Determine what causes the unexpected behavior.  

7. Check file **Debugging Solutions**.  
