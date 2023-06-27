# Repeat-customer-prediction

This is fictitious data from a possible company in the travel industry. Most customers only travel with the provider once in a lifetime. However, some customers are returning, these are called repeaters.

In order to optimize the marketing, the customer would like to implement an NBO (Next-Best-Offer) system that predicts which of the previous customers have a high probability of returning in the next year. The goal is to exclude customers with a very low probability of repeating from marketing campaigns and thus reduce costs. E.g. for printed advertisements and catalogues.


 ## Data

1) customer_data

This is a sample of the master data of the travelers. So every traveler is included once with a unique customer_id (kunden_id).

 

2) booking_data

These are all bookings from the respective customer sample. Usually there are several people in one booking. Every traveler (kunden_id) in a booking (buchungsnr = id) receives an entry here. Beware: some variables relate to the entire booking. e.g. number of persons or total price

 

3) export_regio

These are regional data at postcode level. Can be linked to the other data via the zip code.

