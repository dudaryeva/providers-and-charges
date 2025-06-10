The raw_data includes 3 tables: charges, providers, and charge_codes. The charges table is the main table, which is connected by IDs with the providers and charge_codes tables.


сharges = list of practice sales with the following columns:
id = primary key 
customer_id = patient id
unit_cost = price per unit 
quantity = qty of items purchased
amount = total amount 
discounted_base_charge_amount = total amount after discount 
charge_code_id = id from charge_codes table 
provider_id = id from providers table 
charge_input_date = date when provider enter data into the system 
charge_service_date = date when the service was provided to patient
charge_name = charge name 

providers = list of practice providers 
id = primary key
firstname = provider first name
lastname = provider last name 
fullname = provider full name

charge_codes 
id = primary key
name = charge name
created_at = date when it was created in the database
updated_at = date when it was updated in the database 

![Screenshot 2025-06-10 180244](https://github.com/user-attachments/assets/77f02907-ab89-4a2e-98d0-205368905bb4)
![Screenshot 2025-06-10 180301](https://github.com/user-attachments/assets/dae50422-038a-49e1-8fdb-7a69bb97d981)
![Screenshot 2025-06-10 180316](https://github.com/user-attachments/assets/787b4dea-f732-4d96-ad8d-2bc67c44b269)
![Screenshot 2025-06-10 180340](https://github.com/user-attachments/assets/7d078ba7-b246-42f7-956d-699ac6781d07)

