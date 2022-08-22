# W2_pandas_project_Lucia_Costilla

![giphy (2)](https://user-images.githubusercontent.com/110810531/186027194-6f7dccec-38a3-4686-80d2-80dbc3b0f247.gif)



Based on the knowlege aquiered during the Pandas Labs at Ironhack, we followed some procedures to clean, analyse and present our conclusios from the data "Shark Attacks" obtained at Kaggle: "Global Shark Attacks"


### The Cleaning - 1º Part:

1) Firstly, I've imported some libraries and created a copy of the original Database to be able to reverse any unnecessary drop of colums or rows. 
2) After checking the shape of the DataFrame, I've started to clean dirty columns. That means eliminating empty spaces or re-naming some columns in order to be asier to work with those.
3) The next step was dropping duplicates
4) Lastly checking wich informaton was null in more than 5 columns in order to have the data as clear as possible

### The Cleaning - 2º Part:

1)Once the basic cleaning was made, I've checked which information was important for me to drive some conclusions. Therefore, the information that was NaN, I've replace it for Unknown. 
2) Every information that was important for my analysis such as Country, Year, Sex, Fatality, Activity and Species, was reduce only to the information that was not Null/NaN. That gives consistency when doing graphs. 


### The Analysis:

1) Firstly I've imported certain libraries that helped me to create graphics.
2) Secondly, in order to show how many "NaNs" were at the database, I've shown a Heatmap per column.
3) As I noticed some of the information from the cleaning part was not compleatly correct, I also replaced some values with correct values/strings, in order to show the information from "sex" correctly. The same happened with Species, where all the information was still mixed up. 
4) After the analysis of this columns data, I've created Bar Charts for data in columns "Sex", "Fatal", "Country" and "Activity". 
5) As It was needed to check the progression of the shark attacks, I've also created an histogram with the "year" column, just taking values from 1900 until 2020.
6) Lastly, on the "species" column I've draw a Pie Chart with the top 5 different species. 






