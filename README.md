# excel_interview_qsns
1.diffrence between COUNT,COUNTA,COUNTBLACK
*+Advanced Excel:
*1.What is VLOOKUP and its syntax?
  VLookUP is vertical LookUp .It is uses to Retrieve the data from table to another Excel . VLOOKUP(Lookup_value,table_arr,col_index,Match_type)
  -Lookup_val :the value we are searching for
  -Table_array:the table from which we are extracting the data
  -col_index: The position of the required column in the table array
  -match_type: exact match(0) or Approximate match(1)

  
*2.What are the limitations of VLOOKUP?
  -we can extract only right side data of lookup column using VLOOKUP/ the lookup column should be the first column of the table array
  -we have to provide the column index manually 

  
*3.What is pivot table in excel?
  -Pivot table in excel uses to summarise the data.For ex If we have an Employee data We can caluclate maximum Total salary by city or avg salary by dept. [Alt N V T]
  
*4.What is report?
  -Summary of data
  
*5.What is dashboard?
  -Collection of reports/ collection of charts 
  
*6.What is the difference between SUMIF and SUMIFS
  -SUMIF uses to calculate the sum of values based on a single condition and SUMIFS is used to calculate sum of the values based on multiple conditions
  -the sum_range is the last parameter in SUMIF whereas sum_range is the first parameter in SUMIFS
   SUMIF(criteria_range1,criteria1,sum_range)
   SUMIFS(sum_range,criteria_range1,criteria1,criteria2...)

   
*7.WHat is the differnce between COUNTIF and COUNTIFS?

*8.WHat is the differnce between AVERAGEIF and AVERAGEIFS?

*9.WHat is the differnce between MAXIF and MAXIFS?

*10.How do you Identify duplicates i Excel?
 We can identify duplicates in Excel in 3 ways:
 -Using highlight dupliacte values in consditional formatting
 -using PIVOT table (if count>1)
 -Using COUNTIF
 
11.How do you remove duplicates in Excel?
  2 ways:
  -Using a short cut (Alt A M)
  -using UNIQUE function
  
12.What is the difference between SUBSTITUTE and REPLACE?
  -REPLACE used for the positional replacement in the text where as SUBSTITUTE is a character based replacement in a text
  -REPLACE has 4 parameters whereas SUBSTITUTE has only 3 parameters 
  -REPLACE do the replacement in a specified position but SUBSTITUTE replace a character in all the matching places in a text by default
  -REPLACE(old_text,start_num,num_chars,new_text)
  -SUBSTITUTE(text,old_text,new_text)
  
13.What is the differnce between VLOOKUP and HLOOKUP ?
  VLOOKUP and HLOOKUP both uses to extract data from one table to another table to another table.The only differnce between them is 
    -VlOOKUP used whenever the table_array is in vertical
    -HLOOKUP used whenever the table_array is horizontal

14)Can a pivot table uses mutliple sources of data
Yes, we can create


15) What is cponditional formatting
 Formatting the cell based on a condition , the shortcut for conditonal formatiing in ALT H L

16) What is data valadition
 Verifiying, validating the data before taking it from the users, or resticting the user input data to certian conditions

  
    



  
 

