# Opportunity - Potential Value Sets Amount Flow 

## Use Case : User wants to update the “Potential Value”  custom field value from the Lead object on the Opportunity object after the lead is converted in the Salesforce Sales Cloud. 

![image](https://github.com/Mtalvadi/potentialvalueflow/assets/83495051/6d6851b6-e8a8-4108-a711-7434e543b0c6)

## Constraint : While conversion configuration, there is no option to directly map Potential Value field to the Opportunity “Amount” field. 

![image](https://github.com/Mtalvadi/potentialvalueflow/assets/83495051/f5568b6c-c0bc-4fe7-bdbc-2c5ce1d7a95f)

## Pre-requisite :

-	Custom field named - “Potential Value” of currency data type is created on Lead & Opportunity object.
-	These two fields are mapped under Lead object configuration.
-	Record triggered type (Opportunity - Potential Value Sets Amount) flow is configured and activated.


## Solution/Automation : 

1. Create a new lead record and enter the values for required field along with Potential Value field. 

![image](https://github.com/Mtalvadi/potentialvalueflow/assets/83495051/f9c81d79-6d2c-4ee6-a584-baad355aa365)

2. Click on “Convert” button on top right-hand side and convert it to create a new opportunity record.

![image](https://github.com/Mtalvadi/potentialvalueflow/assets/83495051/d21998d7-90d3-4189-8c33-96807e7161c1)

3. Once converted, go to the Opportunity record and check the Amount field value. It would be the exactly same as Potential Value field (Potential Value field can be hidden or removed from the Opportunity page layout later as below is just for demonstration purpose).

![image](https://github.com/Mtalvadi/potentialvalueflow/assets/83495051/0b3a5961-a381-4428-ae02-5ea4a9704010)



