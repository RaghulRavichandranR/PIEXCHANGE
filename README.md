# PIEXCHANGE
REST API to Access Customer Database

STEPS TO TEST :
	Import the Project from Github in NetBeans IDE/n
	Right Click -> Clean &Build
	Right Click -> Test Restful WebServices



API END POINTS :

Method Name : findCustomersByStartsWithPhoneNumber
Inputs Required: Partial Starting Digits of the PhoneNumber
Expected Response: Customer Information matching with the Corresponding phone number


Method Name : findCustomersByEndsWithPhoneNumber
Inputs Required: : Partial Ending Digits of the PhoneNumber
Expected Response: Customer Information matching with the Corresponding phone number


Method Name : findCustomersByContainsPhoneNumber
Inputs Required: partial phoneNumber
Expected Response: Customer Information matching with the Corresponding phone number


Access Point: findCustomerByPhoneNumber
Inputs Required: phoneNumber
Expected Response: Customer Information with the Corresponding phoneNumber


Access Point: findCustomerByFirstName
Inputs Required: firstName
Expected Response: Customer Information with the Corresponding firstName



Access Point: findCustomerByLastName
Inputs Required: lastName
Expected Response: Customer Information with the Corresponding lastName


Method Name : findCustomerByFirstAndLastName
Inputs Required: firstName & lastName
Expected Response: Customer Information with the Corresponding firstName and lastName


Method Name : findCustomerByUserID
Inputs Required: UserID
Expected Response: Customer Information with the Corresponding UserID


Method Name : findUserByUserFIrstNameAndPhoneNumber
Inputs Required: firstName & phoneNumber
Expected Response: Customer Information with the Corresponding firstName and phoneNumber


Method Name : findUserByUserLastNameAndPhoneNumber
Inputs Required: phoneNumber & lastName
Expected Response: Customer Information with the Corresponding phoneNumber and lastName
 

QUERY:
CREATE TABLE CUSTOMERS (USERID INTEGER NOT NULL, "FIRST_NAME" VARCHAR(50) NOT NULL,"LAST_NAME" VARCHAR(50),"PHONE_NUMBER" VARCHAR(11), PRIMARY KEY (USERID));




