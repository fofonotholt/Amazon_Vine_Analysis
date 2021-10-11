# Amazon_Vine_Analysis
Bootcamp Module 16

## Overview of the analysis
The main goal of the project is to analyze written reviews of the Amazon Vine Program to see if there is a bias towards reviews from the vine memberd of the program. The Vine program is a service in which companies, such as SellBy, pay a small fee to Amazon, so users associated with the program. Those users are in turn required to writte a review. We will be working with Video Games, which is a very popular category in the moment, so we can see if the paid members, tend to be biased and can affect the results.

## Results
Analyzing the data with PySpark, using Google Colab, Amazon Web Services and pgAdmin we can see the following results:

- As we can observe, The total number of reviews is 40,565. Of those reviews 40,471 are from non vine members and 94 are form vine members. So vine members make up less than 1% fo the total reviews.
<img width="456" alt="Captura de Pantalla 2021-10-10 a la(s) 21 22 14" src="https://user-images.githubusercontent.com/85461477/136724685-b53d3b0f-c28e-4955-a70f-6ac845c0220a.png">
<img width="282" alt="Captura de Pantalla 2021-10-10 a la(s) 21 22 21" src="https://user-images.githubusercontent.com/85461477/136724687-cf1d58ad-7078-40c5-9e30-ffaeca1d4c82.png">


- Out of the 40,565 reviews, 15,711 were five-stars reviews, which is aproximatly 38.73%. 24,854 are not 5 stars reviews, which is aprox. 61.27%.
<img width="680" alt="Captura de Pantalla 2021-10-10 a la(s) 21 26 43" src="https://user-images.githubusercontent.com/85461477/136725020-35c9dfaf-8d49-4521-b083-e16d5941bd02.png">


What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
- We can see 51.06% of vine members gave a 5 star review to the product, meanwhile 38.70% of non vine members gave a 5 star review to the product.
<img width="1032" alt="Captura de Pantalla 2021-10-10 a la(s) 21 30 40" src="https://user-images.githubusercontent.com/85461477/136725264-fc823fba-3f16-4289-90ec-7673ba9acfce.png">
<img width="1043" alt="Captura de Pantalla 2021-10-10 a la(s) 21 34 04" src="https://user-images.githubusercontent.com/85461477/136725382-b707a828-0707-4044-9ece-f7865eb3045f.png">



## Summary
We can observe there is a slight bias of Paid members to give a 5 star review to the product. We appreciate there is a higher rate in vine member (51.06%) vs the non vine member (38.70%). Also there are fewer vine members, maybe if we can get a larger sample, we migh see if there is a change or the tendency continues.

A good Analysis to determine if there is a bias, would be te plot the results and view the distribution from both groups.
