# Debug Task 06

Add your own user number after the report name instead of XZ. For example, ‘Z_DEBUG_06_USER01’.

## Steps

1. In **SAP GUI** transaction `SE38`, enter `Z_DEBUG_06_USERXZ`, and click **Display**.  
2. Take some time to observe the report to understand the expected outcome. Run the program by clicking **Direct Processing** or by pressing **F8**.  
3. Examine the output.  
4. Go back to the report, and put a debugger point on **line 12**.  
5. Run the program by clicking **Direct Processing** or by pressing **F8**.  
6. Double-click on variables `lv_cust_type` and `lv_discount` to see their values during processing.  
7. Click **Single Step** or **F5** a couple of times, and observe how the values for `lv_cust_type` and `lv_discount` are changing. Run the debugging process multiple times if necessary.  
8. Determine why Customer Type C results in 0% discount.  
9. Click **Execute** or press **F8** so the report is processed.  

10. Check file **Debugging Solutions**.  
