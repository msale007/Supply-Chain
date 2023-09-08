
## Decode NAICS Code and Categorize Them to Industrial Secotrs


n this folder, we first cleaned and preprocessed the NAICS dataset.


As a second step, we decided to use NAICS structure codes as a basis for decoding NAICS codes. We then categorize all commodities into 20 different categories (based on two digits).


Third, we calculated the frequency of each commodity code in the NAICS dataset.


Next, we developed a ***dynamic model*** to decode the NAICS commodity codes and categorize them based on the desired number of digits.


After applying statistical analysis, we represented the frequency of commodity codes based on new codes categories (in this case, 3 digit codes).


Then, we filtered the previous plot for the top 10 commodities. 





## Aggrageting NAICS and Fairlead_OnTime Data


As a next step, we extracted the codes based on the primary codes. A total of 816 data points were collected in the end. 


Upon merging two datasets (NAICS & Failead_OnTime), we obtained 12610 records. 


In the next step, we calculate the number of orders (PO_ID) placed for each vendor aggregated by NAICS code, as well as the number of orders ordered for each ITEM_ID aggregated by NAICS code.


We constructed two plots to illustrate the number of orders exceeding 30 per vendor and the number of orders exceeding 6 per item.






