Take note that this instructions assumes you know unix terminal commands, and that you have python installed on your system.

1. ensure that all files are in their respective folders. you can refer to the images folder for an overview of step 1. you should have a data folder to store the insendi analytics files, a class_list folder to store class list and the class list from insendi. ensure that the insendi analytics files are stored correctly with their course names for example data_and_deciscions or data_analytics_in_buisness_for_mathematicians, or marketing_and_sales etc.
2. open a terminal and move into the directory where you have the class_analytics.py file (extract_class_analytics folder).
3. if you are not runing anaconda, please run this in the terminal "pip install -r requirement.txt" without the quotation of course :).
4. now run in the terminal "python class_analytics.py [data] [class_name]" without the square brackets and quotation. note that the class name should be in the format SCHOOL_ClassName_class for example "HENKEL_Beta_Class"
5. choose y or n when asked if you have a class list. if you have already extracted a list for you class type 'y', else type 'n' and proceed to type in the name of insendi class list file name without '.csv'.
6. choose y or n when asked if you want to extract sections or all class analytics.
7. when you type in y, you will be asked to specify the days you want to extract separated by comma (for example 1,5 means day 1 to day 5. 1,1 means extract for only day 1) whereas when you type no the process continues.
8. sit back and enjoy :). you should find the extracted analytics files in the analytics folder. the master file contains the combined analytics.

For any further clarification(s), reach me on 
email: ayanful@iiafrica.org
telephone: +233247289712
