# 📊 AURORA SOUND FEST 2025 ANALYSIS  

The main objective of this project is to analyze how Aurosa Sound Fest performed in 2025, regarding costs, attandances, music gerne, total revenue. And also to forecast how the festival will perform in coming years.

(Its important to note that all the data found in the following analysis is made up, it was a project completly from scratch. Creating everything from python with different file such as:

- Artist_list that contained twenty made up artists, six music gernes and six countries, later all of this was entered into a loop that randomly assigned an Id number, a gerne, a counrty of origin and a performance fee and then put on a list. 

- Performance_list that contained the dates of the three days of the festival were decided, start times for the performances and a duration time for each, then it was put into  a loop when a date, start time and duration time were randomly assigned to an artist and later put in a list.

- Sponsors_list that contained five made up sponsors, an assigned contribution amount that then its put into a loop to enumarate and later put in a list.

- Stage_list three stage names were created and then in a loop an Id number, and capacity was assigned to each stage.

- Ticket_Type three ticket types were created based on what is usually found in normal concerts, a price was assigned then a loop was used to enumarate and give a number Id, and then put into a list.

- Ticket_Vendor contains purchased date, fifteen cities and a set amount of tickets to sell, then put into a loop that randomly assigned an Id number, a ticket type Id (1-3 from the previous list), performance Id number, a purchased date, a custumer age and a custumer city.

- Vendor_list twenty vendors were put in a list some real some made up, then three categories were created to clasify what the vendors sold (food, drinks, merch), and three set amounts of commission (10%, 15% & 20%), then a loop to enumarate that randomly assigned a commission and a category to each vendor.

- Vendors_sales here the loop was to assign to each category a unit price between a range of (30.000 -60.000) to food, (15000, 25000) to drinks and (50000, 90000) to merch then a quantity sold was a random choice between (1-10) and lastly a multiplication of unit price and quantity sold.

Then all the data was taken to SQlite to clean it out and start making the calculations of the different questions to showcase this project.

Finally it was taken to Powe BI and put visually.

Lastly important to note that all this calculation were made in Colombian pesos, but since the analysis is being made in english the terms "Billions ot Billion" have to be used, but it is not refering to USD. For clarification  (one billion pesos) in english is the sames as (mil millones de pesos) in spanish, so on the graphics when something shows for example (20 mil M) that is in spanish but it is the same as saying (20 Billions). Also because of the pre setting of Power Bi that were not able to be changed it is shown that way.

## 🗂 Index

* ### [ Performance Analysis.](https://github.com/daniSanClemen98/Music-Festival-Revenue-Analysis-/edit/main/README.md#-performance-analysis )


---

## 🎨 Performance Analysis

<img width="987" height="489" alt="image" src="https://github.com/user-attachments/assets/e4772bab-101b-4048-acfe-2c582683b7c8" />



## 🎨 Custumer Insights

<img width="874" height="489" alt="image" src="https://github.com/user-attachments/assets/1794e21f-f20e-4792-9eae-f046ceaff2f7" />


## 🎨 Vendor Analysis

<img width="863" height="484" alt="image" src="https://github.com/user-attachments/assets/bbef4997-ab35-4710-b388-8cba0fed0b1f" />


## 🎨 Ticket Revenue

<img width="872" height="490" alt="image" src="https://github.com/user-attachments/assets/b0090dfb-b9ab-46ed-8f03-933a373494e4" />


## 🎨 Forecast Revenue

<img width="847" height="486" alt="image" src="https://github.com/user-attachments/assets/c7e816e4-ab4d-4bbf-9500-dda5610f222c" />


## 🔍 Which Genre Generated The Most Revenue?

<p align="center">
<img width="832" height="476" alt="image" src="https://github.com/user-attachments/assets/a1da0e4e-aa2b-4947-8582-c7cc0a28d465" />
</p>
As it can be seen, out of all the music gerne the ones that generated the most were "Merengue" and "Pop", which happen to be the gernes with the most artist at the festival. 
It can also be appreciated that reggaeton is the third most profitable music gerne, demostraring the big relationship between medellin and this music. 
The following two are "Rock" and "Salsa" showing the lasting rock scene that has excited in Medellin since the 80's, even though salsa didn't make over 10k million it still made a healthy amount of revenue must likely because it is still a city in latin America. 
Lastly Alternative making the least amount of money could be explained by it only having one artist and the city's rather smalle Alternative scene.


## 🔍 Which Stage Had The Highest Attendance?

<p align="center">
<img width="839" height="477" alt="image" src="https://github.com/user-attachments/assets/825560ca-417f-43f0-a07e-d60a16bf4c28" />
</p>

Now when it comes to the stages, it can be seen that the stage with the biggest attendance was "La Colina" which is consitent given the fact that it is the stage with the biggest capacity (Over 40.000).

In second place "El pico" with a capacity of over (23.000); however it could be argured that is the stage that produced the most revenue because it was the stage on which some of biggest artist perfmored.

Lastly "LLuvia" with a capacity of over (20.000) was only two points behind, which ilustrates that it was still very profitiable.

## 🔍 Which Artist Had The highest "Cost per Attendance"

<p align="center">
<img width="851" height="479" alt="image" src="https://github.com/user-attachments/assets/c2bdb00a-eb24-406c-aaea-68948fb1fc31" />
</p>

To show the five artists that pulled the most people, starting with "Aurora Blaze" a rock artist, followed by "las Rhythm" an all female rock band, in third place "Electric Tide" a salsa act, then "Denis Benny" is the first merengue artist, and finally "timi 2" another rock artist. Given this it can be infired that even if Rock wasn't the most profitable music gerne it was able to attract the most people given the artist there to represent it.


## 🔍 What Age Group Attended Most?

<p align="center">
<img width="805" height="483" alt="image" src="https://github.com/user-attachments/assets/192e7c5e-8161-45ff-954e-6363831867b6" />
</p>

As it can be seen the first three age groups "46-55","26-35" y "36-45" are very close, meaning they almost had the same amount of attendees over (26,000) people and shows a rather big contrast with the age group of "18-25" that had around (21.000) attendees.


## 🔍 Top 5 Cities By Attendance

<p align="center">
<img width="578" height="494" alt="image" src="https://github.com/user-attachments/assets/f9c3a292-c4cd-4c54-b96f-b8ff1141c280" />
</p>

As it can be shown that most attendees are from Colombia, the biggest one being people from Medellin, followed by San Antonio, then Cartagena and Cali, and lastly Santiago. 


## 🔍 VIP vs General Purschase Ratio

<p align="center">
<img width="749" height="425" alt="image" src="https://github.com/user-attachments/assets/7b83150a-e33d-4590-9deb-7505383bfc8e" />
</p>

Out of VIP and General admition the ratio is of 0.62%, Very close.


## 🔍 Which Vendor Category Made the Most?

<p align="center">
<img width="754" height="475" alt="image" src="https://github.com/user-attachments/assets/eba50be6-9b54-45d5-b019-50700f24d76f" />
</p>

It is safe to infer that people bought fast food most during the festival, this could be because it is faster to get a meal and its cheaper. The only vendor that isn't a fast food one would be "Dulces Lu" but given the fact that its a very famous candy shop and fast serving people are drawn to it. And this five were able to earn over (300.000) each.


## 🔍 Which Vendor Was Not Profitable For The Festival (Commission)?

<p align="center">
<img width="717" height="473" alt="image" src="https://github.com/user-attachments/assets/3b3ea831-3ab8-400f-bc73-912e1ceadb40" />
</p>

Now for the vendors that earned the least amount of money all under (12.000) each and in comparision to the top earnest there is a clear and big gap. This could be explained by the products that these vendors offer such things as deserts, paitries cofee etc. 


## 🔍 Ticket Revenue per Date

<p align="center">
<img width="809" height="453" alt="image" src="https://github.com/user-attachments/assets/b81ba8cd-0c42-41aa-8f10-4587f1898435" />
</p>

As it can be seen the day that made the most revenue was october tenth, a friday that was able to make over (36.990 billions), followed by the eleventh and the twelveth that made almost the same amount around (23 billions) each.


## 🔍 Revenue per Ticket Type

<p align="center">
<img width="809" height="430" alt="image" src="https://github.com/user-attachments/assets/ea68f2b4-95ed-4090-818b-0f31898a81b3" />
</p>

This is a similar graph to the one of "VIP vs General Purchase Ratio", but it is not because that one showed how many tickets were purchases and compred one two of the three ticket type, this one show how much each type made and compares them. The biggest revenue was made from platinum with over (40.4 billions), followed by VIP with over (28.4 billions) and lastly General with a (14.8 billions) amount. From this it can be seen that the spending power was large for the atendees of the festival.


## 🔍 Forecast Revenue

<p align="center">
<img width="801" height="468" alt="image" src="https://github.com/user-attachments/assets/fe3a84a1-f291-43b6-b7a5-655776f6bd81" />
</p>

In order to calculate how much money the festival would make in 2026 compared to 2025 a 10% increment was used, given how succesful the festival with a total revenue of over (83.6 billions). And so the calculation would suggest a revenue of over (92,2 billions) for Aura Soun Fest 2026.


## 📖 Conclusion

