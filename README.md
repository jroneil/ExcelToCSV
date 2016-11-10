# ExcelToCSV
Export excel to csv (single and multiple sheets)
Application will convert multiple sheet and single sheet excel files to a single csv file.
Excel files with extenstions xls and xlsx.

To run file open a command window
Type at the command prompt java –jar export <source Dir> <targetDir>  debugOnOff

#Examples
Debug on
java -jar Excelcsv.jar "C:\\xlstocsv\\excel" "C:\\xlstocsv\\csv" true

Debug Off
java -jar Excelcsv.jar "C:\\xlstocsv\\excel" "C:\\xlstocsv\\csv"


Debug True will show comments
