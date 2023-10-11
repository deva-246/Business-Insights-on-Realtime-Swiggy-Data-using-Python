# Business-Insights-on-Realtime-Swiggy-Data-using-Python
Data analysis on a part of real time Swiggy data to gain insights and make business based decisions.

# Datasets
The fields present in items dataset are,

      1. id 
   
      2. order id
   
      3. Name of the item
   
      4. is_veg / not

   
The fields present in Orders dataset are,

      1. id
      
      2. order id
      
      3. order_total
      
      4. Restaurent Name
      
      5. Order Time

      6. Rain mode

      7. On time / not

# Business Insights 

1. **Unique Items that are ordered**

   There are 164 unique items present in the dataset, which are been delivered by swiggy.
   
![image](https://github.com/deva-246/Business-Insights-on-Realtime-Swiggy-Data-using-Python/assets/75877347/50243034-36fe-46ce-bd85-8dc2dc85ebab)

![image](https://github.com/deva-246/Business-Insights-on-Realtime-Swiggy-Data-using-Python/assets/75877347/348136a8-c490-42b0-a5ff-e066482cd83a)


2. **Count of Veg and Non veg Items**

   There were **12** **Non veg** items
   **180 Veg items**
   and a **new category(undefined)** - Maybe Desserts - **1 item**

![image](https://github.com/deva-246/Business-Insights-on-Realtime-Swiggy-Data-using-Python/assets/75877347/bc3edb70-5162-4baa-8e44-c8e9e07d4556)


3. **Details on Chicken based dishes**

   The value -1 denotes the absence of chicken and other positive valuesdenotes the presence of the word chicken.
   
   ![image](https://github.com/deva-246/Business-Insights-on-Realtime-Swiggy-Data-using-Python/assets/75877347/819dcd83-c16c-41d3-9b00-fe5d94839b5f)

   In order to filter the chicken based dishes we can access with the chickenfound field value.

   ![image](https://github.com/deva-246/Business-Insights-on-Realtime-Swiggy-Data-using-Python/assets/75877347/bbb42964-d7be-4742-98de-5466c05e0d70)
   

4. **Items that are ordered the most**

   To know the most ordered items - we can group the items by their name along with the count of it's order. As the default result displays in ascending order use sort_values() function with ascending=False as it's parameter

   ![image](https://github.com/deva-246/Business-Insights-on-Realtime-Swiggy-Data-using-Python/assets/75877347/f3e7d9a1-1c1f-483b-a928-909cf5db524a)


   **Classic Mac & Cheese** is the most ordered item according to the dataset.
  


5. **Count of distinct orders**
   
   There are 95 unique orders.
    
   ![image](https://github.com/deva-246/Business-Insights-on-Realtime-Swiggy-Data-using-Python/assets/75877347/8ef18417-94d8-41df-bfea-0653aa532e53)
   

6. **Unique Restaurents where the orders are placed**
   
   There are **49** unique restaurents which have recieved orders.
   
   ![image](https://github.com/deva-246/Business-Insights-on-Realtime-Swiggy-Data-using-Python/assets/75877347/d25f77d6-3223-40d0-8e93-3e4e47256662)

7. **Top Restaurents with high number of orders**

   ![image](https://github.com/deva-246/Business-Insights-on-Realtime-Swiggy-Data-using-Python/assets/75877347/ef2fe329-ac05-4188-89e1-ac116f6b65b4)

   ![image](https://github.com/deva-246/Business-Insights-on-Realtime-Swiggy-Data-using-Python/assets/75877347/936a327e-7a6c-4366-a8e0-6643e0233135)

   ![image](https://github.com/deva-246/Business-Insights-on-Realtime-Swiggy-Data-using-Python/assets/75877347/5f040e64-5971-4530-b9f0-cd46ca8466b0)




   
   


   

   


   


   


   


