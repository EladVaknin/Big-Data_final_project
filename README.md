# Big-Data cloud project
The target of the project is create and desigen a delevery system in MVC model with big-data clouds and databases.
In this project  we used in this tools : Reddis ,Fairebase ,MongoDB and BigML.

All the data and the status prsent in dashboard that includes the pages:
* dashboard - the main page, shows the month delevery status and data graphs.
* deliveries- present unique QR code status per package for tracking.
* analitical - present the conclusion from BigML prosess.

**The project's diagram:**
![image](https://user-images.githubusercontent.com/74238558/141679522-b6630606-affd-4698-b5c7-2f020fd53295.png)




## Part  A - Generator 
In this section we create the data with a simulator and export the data to a JSON file, create the server and connect all the tools in its redis implementation.
The JSON data incloulds id, items ,diteals about the buyer ,loaction and adress.
The fairebase got and save all the data then we use to reddis that he our middelware and connect all the tools.
Every packege got unique QR code that represent the data and the tracking status.

**Unique QR Shipping Status :**
![WhatsApp Image 2021-11-14 at 14 15 47](https://user-images.githubusercontent.com/74238558/141680652-6ae029fc-8935-4e5c-8c9c-4c454b2adc1a.jpeg)

 
## Part B - Analaysis 
In this part we analaysis the data to see the conclusions.
We pull the relevent data from mongoDB that save tha data for long time and convert him to CSV file.
Now to analaysis the data we used in BIgML tool in association model - 
the association model analaysis the connection bitween two items.
This model looks for some connection between the two items based on Big Data, for example in many orders whoever ordered a table has a reasonable chance that he also ordered a chair.
We presented the results we got on a page called Analytical as mentioned above.

**Analitical page :**
![WhatsApp Image 2021-11-14 at 14 16 04](https://user-images.githubusercontent.com/74238558/141680747-84930083-97fb-4cf7-8d35-a77f49c18261.jpeg)







# Participants
Elad Vaknin
Gidon Avziz
Liad Nagi
