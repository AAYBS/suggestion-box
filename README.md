# Suggestion :see_no_evil: :hear_no_evil: :speak_no_evil: Box

# :bulb: Ideas :bulb:
* Have a great idea? 
* You need to automate some of your boring stuff?

Just create an [issue](https://github.com/AAYBS/suggestion-box/issues/new) with the description and together we can build it !!!

# :checkered_flag: Start :checkered_flag:

If you don't know where to start check this awesome book:
https://automatetheboringstuff.com/ 
 *For automation of tasks a software named 'RoboTask' which is helpful in checking emails,launching files,moving or backing up data,etc.  
# Also,Python can be helpful for these tasks.
 *An illustration for sorting an excel sheet containing movie names and year of release is given as;
     import pandas as pd
     excel_file='movies.xls'  //movies is the name of the excel file
     movies=pd.read_excel(excel_file)
     movies.head()
     movies_sheet1 = pd.read_excel(excel_file, sheetname=0, index_col=0)
    movies_sheet1.head()
    movies_sheet2 = pd.read_excel(excel_file, sheetname=1, index_col=0)
    movies_sheet2.head()
    movies_sheet3 = pd.read_excel(excel_file, sheetname=2, index_col=0)
    movies_sheet3.head()
    movies = pd.concat([movies_sheet1, movies_sheet2, movies_sheet3])
    movies.shape
    (5042, 24)
