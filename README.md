# Comparing-2-Excel-Sheets-and-get-the-Differences-between-them-by-using-Python
The  approach I have used in Python is by taking referance from YouTube: 
https://www.youtube.com/watch?v=2JgnvsaWuHk&list=PLaso8-OZjhbyFd_L1hGu_i-5yPwVaR9lK&index=5
By using this approach, I have got the Output of the Differences in the mentioned path of Excel Sheet and it was giving lot of required details by camparing 2 Excel Sheets and showing Differences between each Column of 2 Excel Sheets.
As I have used datacompy Pandas Library, so it was giving the desired Output and was also giving lot of details between the 2 Excel Sheets.
DataComPy is a Pandas library open-sourced by capitalone. It was started with an aim to replace PROC COMPARE for Pandas data frames. It takes two dataframes as input and gives us a human-readable report containing statistics that lets us know the similarities and dissimilarities between the two dataframes.
pip install pandas
pip install numpy
pip install xlrd
pip install openpyxl
pip install datacompy


So I have used another approach for writing Automation Script in Python for Comapring 2 Dynamic Excel Sheet & store the output into another Excel Sheet.
As my entries in each excel sheets are high and not limit upto 10, so I got the resolution for this by setting limit from this website: https://github.com/capitalone/datacompy/issues/45
After that, I was facing issue in storing the Output in Excel Sheet as by executing this code, I was getting Output in Console and not storing Output data in to the Excel Sheets.
So I have taken references from my previous code to store the Output in the Excel Sheet.
Initially while storing Output, I was facing challenges to store Output in Excel Sheet because the Output which was coming is not in the systamatic tabular form, so Excel Sheet was not accepting that data while using .xlsx
I have used another method to store the data in Notepad as .txt instead of storing it into Excel Sheet as the Output hich was coming was not in a systematic tabular form. I was getting the Output in Text File properly.
After discussing with Sachin, he has given me the resolution for storing the Output into the Excel Sheet just by mentioning .xls format. 
I was also getting the Output in Excel Sheet by using .xls but in Excel Sheet, the Output which I was getting is that it was storing all the values in 1 Colums itself.
There was a many benefits while using this approach is because, in this approach I was getting accurate and desried differences in the Output and it also giving lot more information for both the Excel Sheets in the Output and I will proceed further by using this approach only for Execution.
As there is least drawback while using this approach. But then too, there are some drawbacks are there when using this approach for Execution.
There should be atleast one Qnique Column has to be there, so that we can compare the values by considering the Qnique Column in both the Excel Sheets.
As the Output is coming is in detailed format in which there are some sentenes are also there and the data coming as an Output is not in a systematic tabular form, so it is difficult to store Output in Excel Sheet by using .xlsx
We can use .txt to store Output in Text Format or we can use .xls for storing the Output in Excel Sheet. But then too, when we store Output in Excel Sheet by using .xls format, we get warning while opening Excel Sheet.
There is a drawback for storing Output, is that first we have to store the Blank Excel Sheet ot Blank Text File in whatever way we want to store the Output results, then only it will store the Output into it and It is not auto generating any Output file by itself.
The other drawback for storing Output is that, we can not overrite the existing File which we have mentioned to store the Output.
![image](https://user-images.githubusercontent.com/77016896/122560627-6f6f4b00-d05e-11eb-9e93-96d420fe13a4.png)
The  approach I have used in Python is by taking referance from YouTube: 
https://www.youtube.com/watch?v=2JgnvsaWuHk&list=PLaso8-OZjhbyFd_L1hGu_i-5yPwVaR9lK&index=5
By using this approach, I have got the Output of the Differences in the mentioned path of Excel Sheet and it was giving lot of required details by camparing 2 Excel Sheets and showing Differences between each Column of 2 Excel Sheets.
![image](https://user-images.githubusercontent.com/77016896/122560671-7eee9400-d05e-11eb-8e95-24b41c62e80b.png)
