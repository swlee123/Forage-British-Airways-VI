# Forage-British-Airways-VI
(Forage)[https://www.theforage.com/dashboard] is an open access platform designed to unlock exciting careers for students by connecting them with our company-endorsed Virtual Work Experience Programs.

## British Airways Virtual Internship

This VI is separated into 2 tasks :

## First Task : Web Scraping to gain company INsights
Scrape and analyse customer review data to uncover findings for British Airways

Customers who book a flight with BA will experience many interaction points with the BA brand. Understanding a customer's feelings, needs, and feedback is crucial for any business, including BA.

The data will be very messy and contain purely text. I performed data cleaning in order to prepare the data for analysis. When the data is clean, I perform my own analysis to uncover some insights.More details is included in the google colab notebook.

The first thing to do will be to scrape review data from the web. For this, you should use a website called (Skytrax)[https://www.airlinequality.com/].
I used python BeautifulSoup for this part.

Finally, I summarised my findings within a single PowerPoint slide to be submmited.

## Second Task : Predicting Customer Buying Behaviour
Build a predictive model to understand factors that influence buying behaviour by using the data in **Customer Booking.csv** 

For this task, I used an algorithm that easily allows me to output information about how each variable within the model contributes to its predictive power. For example, a RandomForest is very good for this purpose.More details is included in the google colab notebook.

After training my model, I evaluated how well it performed by conducting cross-validation and outputting appropriate evaluation metrics (confusion matrix). Furthermore, I created a visualisation to interpret how each variable contributed to the model. Finally,I summarised my findings in a single slide to be submitted for evaluation on Forage website. 
