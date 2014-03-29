Payment Module : Zaakpay
*****************************
   
Zaakpay - Simplifying payments in India 

Our aim is to solve the payment pain points for eCommerce in India.
		
**************************************************************************************		

An installation procedure for the module:
   
- Get a merchant account from ZAAKPAY
- Unzip the contents of the module (or upload the unzipped folder named commerce_zaakpay) at 
../sites/all/modules/commerce/modules/payment/
- Enable the module at ../admin/build/modules
- open ../sites/all/modules/commerce/modules/payment/commerce_zaakpay/posttozaakpay.php and 		  ../sites/all/modules/commerce/modules/payment/commerce_zaakpay/response.php .Then, enter 
your secret key in both the files.
- Enable Zaakpay as a payment method
- Enter your Zaakpay Merchant id and Secret key, set the Zaakpay payment mode 
to Live(Value = 1) or Test(Value = 0) and save the changes.
		
****************************************************************************************	

DESCRIPTION :

When you Extract the zip file, it has five files
- commerce_zaakpay.info
- commerce_zaakpay.module
- posttozaakpay.php
- response.php
- checksum.php

These are simple PHP files with different extensions 

* commerce_zaakpay.info - This is simple file which has information about the payment module.
* commerce_zaakpay.module - This is the core file which includes all the funcionalities for the module like posting cart information to Zaakpay with checksum and getting the response etc ..,  
* posttozaakpay.php - This is the php file which is responsible for posting the form to the Zaakpay API.
* response.php - This is the php file used to receive the response from Zaakpay API.			
* checksum.php - Cotains general functions to find checksum.
										
***************************************************************************************

SPECIAL NOTES :

- Create a custom field for phone number named "phone number" name its machine name as "field_phone_number" at checkout page. 


****************************************************************************************

For further details you can mail it to developers@zaakpay.com