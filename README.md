# A Simple WebScraper
Use it to access any tables you find in a website on your spreadsheet.

## Accessing the website 
Open the notebook in jupyter notebook or Google Colab and start running each shell by pressing 'shift' + 'enter'.

The program will ask you to input the link to the website. 
Copy it and paste it in the input box.
![image](https://github.com/Kev-Daran/WebScraper/assets/81677957/dbeaef83-b90c-4517-a1d1-d93863e349d0)

## Accessing the table
In case the website has multiple tables, consider the first table as the number '1' and specify which table you want.
![image](https://github.com/Kev-Daran/WebScraper/assets/81677957/d5c2ac2e-4e59-4d93-8068-a3e9dbe18906)

If an incorrect table position has been entered, you will encounter the following message.
Recheck the table's position.
![image](https://github.com/Kev-Daran/WebScraper/assets/81677957/e1cfe968-7483-419c-9b5a-9b38ae60c92a)

## Accessing the spreadsheet
The spreadsheet will be saved as a '.csv' file in your environment as 'scraped_data.csv'.
![image](https://github.com/Kev-Daran/WebScraper/assets/81677957/c814780c-b28e-444f-a6a7-e2538703071a)

In Google Colab, you will have to download the file from your environment. 

Open the csv file with any spreadsheet application.

![image](https://github.com/Kev-Daran/WebScraper/assets/81677957/537d99aa-8c35-494a-8806-fdb08a1ef680)

The program also loads the file into a dataframe for further processing if required.
![image](https://github.com/Kev-Daran/WebScraper/assets/81677957/7aa3d19a-8ee9-401a-990c-d5b50c11375a)


Note: This webscraper will only work for relatively small scale websites. Some websites provide api to access their services. Some websites do not allow the use of webscrapers.
