Database Project: Rental Property Company “Miller Farm”<img width="1567" height="354" alt="image" src="https://github.com/user-attachments/assets/b6eb05b3-6bc1-4dd8-852e-f06fcd96f962" />
This project aims to create a database to help manage a rental property business. It will help keep track of things like tenants, rent payments, leases, and maintenance<img width="5123" height="158" alt="image" src="https://github.com/user-attachments/assets/5936be81-7588-4cee-8e05-c0a52f885229" />
Tables in DBDL format
TENANTS (TenantID, FirstName, LastName, Phone, SSN, DrvrLicense, BankName, BankAccount, FamilyIncome, CarLcnPlate, Under18)
PROPERTY_DETAILS (PropertyID, Address, QntRoom, QntBaths, SquareFoot, FloorNumber, isGarage, isBasement, isBalcony, StndPrice, StndMaintenance)
LEASES (LeaseID, TenantID, PropertyID, StartDate, EndDate, OutofContract, EarnestMoney)	
  FK    TenantID -> TENANTS	
  FK    PropertyID -> PROPERTY_DETAILS
PAYMENTS (PaymentID, PropertyID, PmntConfirm, PmntMonth, PmntYear, PmntPrice)	
  FK    PropertyID -> PROPERTY_DETAILS
TECH_ISSUES (IssueID, PropertyID, Description, RequestDate, Status, CompleteDate, CostExpences)	
  FK    PropertyID -> PROPERTY_DETAILS	
  FK    Status -> STATUSESSTATUSES (Status)<img width="2122" height="610" alt="image" src="https://github.com/user-attachments/assets/33f3ff50-6199-4b9e-915b-c56f0cb7b4f5" />
<img width="1047" height="429" alt="image" src="https://github.com/user-attachments/assets/3f18588b-c0f3-4e3c-aad3-87a11cc4ff1e" />
