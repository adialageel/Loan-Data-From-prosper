# Loan-Data-From-prosper


# Dataset

In this project there is three datasets such as: 
1-	Ford GoBike System Data - Available at the bottom of the page
2-	Flights
3-	Loan Data from Prosper with Prosper Data Dictionary to Explain Dataset's Variables
4-	PISA Data with PISA Data Dictionary to Explain Dataset's Variables

I chose Loan Data from Prosper since I’m a computer engineering graduate and I’m interested in financial data and banking, so since this data related to peer to peer lending and it’s lending through online services, so I that’s why I chose to visualize this dataset.
This dataset contains 113937 row (loans) and 81 columns that’s contain some prosperities.   



# Summary of Findings

# Univariate Exploration


1-Employment Status:

You can see from the plot, the unemployed and retired and part time employee have low potential to get loan.
<img width="468" alt="image" src="https://user-images.githubusercontent.com/83476407/122645908-84fb7800-d125-11eb-8cb0-6e52a5fe67fb.png">

 

2- Income Range:
As we can see from the below chart for 0$ and unemployed almost cannot borrow.
<img width="468" alt="image" src="https://user-images.githubusercontent.com/83476407/122645922-93e22a80-d125-11eb-86c3-9e5068383b88.png">

 
3- Loan Status:
From the chart we can see almost 40,000 loans are completed and the current are not completed yet.

 <img width="468" alt="image" src="https://user-images.githubusercontent.com/83476407/122645926-9775b180-d125-11eb-94f8-2e7bcca7f793.png">







4-	Prosper Score:
From the graph the score for people is between 4 to 8 and at 4 we can see the highest
<img width="468" alt="image" src="https://user-images.githubusercontent.com/83476407/122645932-9a70a200-d125-11eb-8126-813ae033c45b.png">


 
5-Borrower APR:
We can notice that the graph almost skweed to the right, the graph tell us the highest value is at 0.36


<img width="432" alt="image" src="https://user-images.githubusercontent.com/83476407/122645943-9fcdec80-d125-11eb-85d0-78c86ab24fc3.png">


 
6- Monthly Loan Payment
Here we are focusing on the payments for the borrower.
We can notice from the chart that the payment less than 2000 and rarely above 2000, we can also see that the graph is skewed to the right:

 <img width="468" alt="image" src="https://user-images.githubusercontent.com/83476407/122645957-aceadb80-d125-11eb-9893-f5b0b13595c2.png">


7- Profession
We can see that the most profession by Electrical engineers, computer programmer and others

 <img width="376" alt="image" src="https://user-images.githubusercontent.com/83476407/122645965-b3795300-d125-11eb-8faa-b7bc37120998.png">


Bivariate Exploration

1)	Quantitative vs. Quantitative
We compared two variables that we are interested.
We can see from the plots that there is no relationship between the estimated return and the actual return.

 


<img width="393" alt="image" src="https://user-images.githubusercontent.com/83476407/122645968-b8d69d80-d125-11eb-8edf-b3af792310b0.png">










2)	Quantitative vs. Qualitative
In this section we will check the relationship between the expected returns with the income and credit rating.

<img width="367" alt="image" src="https://user-images.githubusercontent.com/83476407/122646010-e15e9780-d125-11eb-8343-cd70a74b64d2.png">

 
As we can notice from the graphs the relationship between the income and expected return is negative relationship.

And from the boxplot below we can see the Highest return can be got when investing in borrowers.


3)	Qualitative vs. Qualitiative

As we can notice from the chart below, the income with the range 25,000 - 49,999 has the highest credit ratings and for large amount of income didn't get high credit rating.

<img width="421" alt="image" src="https://user-images.githubusercontent.com/83476407/122645981-c3913280-d125-11eb-96cc-c89cbbbd9ae4.png">

 

Multivariate Exploration
1)	What we are focusing here in this sections is the corrolation between the rating for Prosper + Term and tbe borrower Annual Percentage Rate (ARP).

<img width="468" alt="image" src="https://user-images.githubusercontent.com/83476407/122645988-ca1faa00-d125-11eb-9895-26e4d4774a79.png">

 

We can notice that the tirm has little effect on the loan amount with the ARP.


2)	We can notice that from the plots below the loan amount and ratings has positive relationship. Since AA ratings take extra loans the relationsship between borrower's ARP with the amount of loan becomes positive.
 


<img width="468" alt="image" src="https://user-images.githubusercontent.com/83476407/122645991-ce4bc780-d125-11eb-9202-2eb77f58dda4.png">






3)	 what we can notice after checking the ratings of for E rating it gets the highest borrower ARP then there is the rating D .

For the second graph we can see that for not employed we've got the highest borrower APR.



<img width="403" alt="image" src="https://user-images.githubusercontent.com/83476407/122645997-d441a880-d125-11eb-8c22-989d4a4412f4.png">
<img width="394" alt="image" src="https://user-images.githubusercontent.com/83476407/122646000-d6a40280-d125-11eb-92b1-3dc365a9f526.png">


 
 





Key Insights for Presentation
•	For not employed or zero income has low opportunities to get loans
•	Almost 38,000 loans are completed and the current by 50,000 are not completed yet.
•	Computer programmer is the most profession for borrowing.

