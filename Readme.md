# Couse Schedules Part 2: Working with Dirty PDF and CSV Files

## Instructions
1. **Read through the Markdown in the `Part2.md` file.**   
    - You will notice all kinds of formatting tricks to make Markdown behave nicely.
    - Right click on the file in the editor tab and select `Show Markdown Preview`. The rendered document should appear in all its glory. The preview even updates if you edit anything in the `Part2.md` file.
    - Close the preview tab. The editor panel should expand to reclaim the space. 
2. **Edit and run the `course_schedules_tabula.py` module as follows:**
    - Open `course_schedules_tabula.py` in JupyterLab. 
    - Uncomment the last line of the module so it looks like this:
        ```python
        print(scrape_undergrad_course_booklet('tabula-201801CourseBooklet.csv'))
        ```
    - Launch a bash Terminal in JupyterLab. Ask your neighbors if you don't know how. 
    - Use the `cd`,`ls`,and `pwd` commands to navigate into this folder. Again, ask for help. 
    - Run `python3 course_schedules_tabula.py` to run the module. You should see about 1300 courses flash past, in JSON format.
    - Recomment the last line of the module so it looks like this:
        ```python
        # print(scrape_undergrad_course_booklet('tabula-201801CourseBooklet.csv'))
        ```
3. **Walk through the code line by line as directed in the `Line-by-Line-Trace.ipynb` notebook.**   
    - Don't cheat. Actually run it one cell at a time.
    - This is what it looks like when we are testing code. We take it apart and test each piece using dummy data where needed. Ideally, you want to test each snippet before you move on. That's a great way to buold large programs without a ton of hard to find bugs. If you test after each line of code then any bugs you find are likely to be on the last few lines you wrote. 

