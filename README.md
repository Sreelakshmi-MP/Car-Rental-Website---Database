# Car-Rental-Website-Database

### Business Case
-----------------------
World On Wheels (WOW) Rentals is a car rental company operating in the United States and is continuously planning to expand it’s operations in the US. They provide rental services in NY, Washington DC, Philadelphia, Boston and other states. WOW maintains both a collection of corporate customers and individual customers in their service.
Corporate customers are those who work for corporations who have an agreement with WOW Rentals to use their services in exchange for a discounted car rental rate. WOW’s website provides the capability to register for an account, automatically links corporate users with corporate accounts, lets users create, update and delete rental bookings, allows them to browse available vehicles (and those vehicle’s locations), and allows the users to pay for invoices they have incurred from rentals. The same behavior is maintained for Individual customers except that their discounted coupons can vary.

### Our Approach
---------------------
We’ve designed a backend database for WOW Rentals, originally using Oracle Data Modeler and ultimately with Django as a backend web framework. Our implementation makes it easy for users to perform basic CRUD (Create, Read, Update, Delete) functions, taking the load of managing these of employees, while still offering employees an easy and intuitive way to view, manage and edit user data if necessary. We’ve assumed that a user registering with the email address “email@<CompanyName.com” is a corporate user if CompanyName is in our corporations table else the customer will be treated as an Individual customer.
