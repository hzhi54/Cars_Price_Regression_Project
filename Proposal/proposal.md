# Proposal

## Idea and Questions to Answer:

My idea of the project is to able to predict used cars sell price given the features of the cars. The model I will be creating will be an linear regression model. The linear regression model will take features of the car and the target value will be the car price. The features of the car will be **price, model, make, mileage, body-type, color, engine, location**. Some of the features will become a dummy variable for example the **color** feature and other there will be data cleaning need to be done so that I can get the right type for each features.

## Who is this for?

The benefit for this project is for people who tries to sell their car so that they can get an estimate of the price for their car. For people who are not very good with cars and wanted to sell their car with a price that seems right, they could use my linear regression model to get an estimation. This also useful for people who tries to buy an used car and not knowing the car market. By applying the features they want, they will also get an estimate of how much the car will cost and negotiate from there to get a better price.

## Where my Data From?

My main source of my data will be comming from www.carfax.com where it is a website that will show used car and all their features and prices. I will use web scraping tools mainly beautiful soup to extract data from the website. If there are many click on things I have to do during the project, I will also use Selinium to help me navigate the browser to help me extract information.

## EDA and Modeling:

After getting all my data from the used car website, I will do some exploratory data analysis before modeling. I want to make sure that my data are in the right format and have a well understanding of the data. Cleaning data and creating dummy variable are important in this process before began creating a linear regression model. They will play an impactful role when data types like **color, model, make** and other features that will effect the prices of the car.

## Other tools:

Some other tools I might use is **Seaborn** to create some visualization during my EDA process of the data. For me, I will able to understand the data visually and not just with plain text. In order to store the data somewhere during the extracting phase of the project, I will use SQLite to store my data or something new like MongoDB. 

## MVP:

I will assume that my MVP will contain my linear regression model and the prediction of the model. I will also include the chart with my modify data to show the dummy variables I made.
