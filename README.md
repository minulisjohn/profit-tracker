Profit Tracker App
Implementation-
1. Backend -
  1. Implemented using SpringBoot, JPA and H2 database
  2. Exceptions are handled using @ExceptionHandler and @ControllerAdvice annotations in SpringBoot
  3. Profit is calculated as TotalSoldPrice - TotalSoldQty*(TotalPurchasePrice/TotalPurchasedQty)
  4. Insert queries are available in data.sql file
  
2. Frontend -
  1. A single page application is implemented using React
  2. Links are handled using Router in React
  3. Client side validations are handled using Javascript
  

Assumptions -
1. Calculate Profit Module -
  1. For calculating profit, the start date is considered as the start day of the current year
  2. Either category or product can be included in the search criteria
  
 
Improvements -
1. Tests for backend(JUnit) and frontend(Jest)
2. Webpackaging for frontend(Webpack)
3. CORS can be improved in production by allowing only the required domain

Screenshots -
Screenshots are attached in Screenshots file
