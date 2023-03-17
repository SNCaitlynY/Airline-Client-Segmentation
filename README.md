# Airline-Client-Segmentation

### Goal
The objective of the project was to understand the customer segmentation of Sun Country Airline and provide recommendations to increase membership and boost customer booking rates. The data used for the analysis included flight information variables (serviceCity, startDate, airlinecode), passenger demographic variables (age, postalcode, gender), and transaction details variables (bookingchannel, memberstatus, cardholder).

### Data Preprocessing
To preprocess the data, we cleaned it by defining a primary key (Cus_ID = EncryptedName + birthdateid + GenderCode) and created features such as UFly Membership Status, Age, Gender, Card holders, Number of trips, BookingChannel, Total amount spent & number of discounts, Upgrade & downgrade, and Number of trips by class.

### Clustering Analysis
We then used the block randomization technique to take a sample of the data and performed K-mediods clustering (cluster number = 5) to segment the customers. We visualized the results to see how elite customers/first-class travelers performed in different clusters.

### Result
We identified five customer segments and made recommendations based on the cluster characteristics to help Sun Country Airline improve its customer experience and compete in the travel market. The recommendations included focusing on periods after the Christmas holidays to attract potential customers via promotion code, boosting customer booking rates on the website by offering discounts on the first several rides and free bags on the first trip, implementing senior travel assistance programs, and promoting the airline on social media.


Overall, the project's findings provided valuable insights into customer segmentation, and the recommendations provided actionable strategies to improve customer engagement and drive business growth for Sun Country Airline.
